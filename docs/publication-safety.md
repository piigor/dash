# Checklist de publicação segura

Use este checklist antes de adicionar qualquer novo arquivo ao repositório público.

## Dados e arquivos

- [ ] Nenhum `.pbix`, `.pbit`, `.xlsx`, `.xls`, `.csv`, `.zip` ou export privado foi adicionado por engano.
- [ ] Não há dados de clientes, contratos, colaboradores, telefones, e-mails ou identificadores.
- [ ] Nomes de empresas, fornecedores, sistemas e caminhos internos foram removidos ou generalizados.
- [ ] Valores financeiros, metas e volumes reais foram mascarados, agregados ou substituídos por exemplos.
- [ ] Logotipos e marcas internas foram removidos ou substituídos quando necessário.

## Consultas e metadados

- [ ] Não há credenciais, tokens, strings de conexão ou nomes de servidores.
- [ ] Não há consultas M, SQL ou DAX que revelem tabelas, projetos, datasets ou regras internas protegidas.
- [ ] Não há caminhos locais, nomes de usuário ou comentários internos.
- [ ] O material público descreve o método sem afirmar resultados que não podem ser comprovados publicamente.

## Git antes do commit

```bash
git status --short
git diff --check
git diff --cached --name-only
```

Verifique também os arquivos staged por padrões de risco:

```bash
git diff --cached --binary | strings | grep -Ei \
  'AIza|sk-[A-Za-z0-9]|ghp_[A-Za-z0-9]|password|secret|token|\\.pbix|\\.xlsx|server=|database=' \
  || true
```

A ausência de uma ocorrência não substitui a revisão humana. O objetivo é reduzir o risco de publicar material privado por acidente.
