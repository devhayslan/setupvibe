# Skill: markdown-format

Aplique as regras de formatação Markdown a todos os arquivos `.md` do projeto SetupVibe.

## Regras obrigatórias

Todo arquivo Markdown neste projeto deve seguir estas regras:

1. **Títulos** — usar `#` hierárquico (H1 → H2 → H3), sem pular níveis.
2. **Tabelas** — colunas alinhadas com pipes `|`, sempre com linha separadora `|---|---|`.
3. **Blocos de código** — sempre com linguagem especificada (` ```bash `, ` ```js `, etc.).
4. **Links** — formato `[texto](url)`, nunca URLs soltas.
5. **Listas** — hífens `-` para itens não ordenados; números para ordenados.
6. **Linhas em branco** — uma linha em branco antes e depois de títulos, blocos de código e tabelas.
7. **Sem HTML inline** — não usar tags `<br>`, `<b>`, `<i>` etc. dentro do Markdown.
8. **Formatação de link no rodapé** — todo arquivo `.md` deve conter no final um link de referência apontando para o arquivo de formatação:

```markdown
---
> Siga o guia de formatação: [Markdown Format Guide](.claude/commands/markdown-format.md)
```

## Como aplicar

Para cada arquivo `.md` modificado ou criado:

1. Verifique se as regras acima estão respeitadas.
2. Corrija espaçamento, alinhamento de tabelas, e blocos de código sem linguagem.
3. Adicione o rodapé de link de formatação caso esteja ausente.
4. Nunca remova conteúdo — apenas formate.

## Arquivos do projeto

Os principais arquivos Markdown são:

- `README.md`
- `CLAUDE.md`
- `GEMINI.md`
- `AGENTS.md`
- `docs/README.md`
- `docs/desktop/en/README.md`
- `docs/desktop/en/tmux.md`
- `docs/desktop/en/pm2.md`
- `docs/server/en/README.md`

## Invocação

Use `/markdown-format` para verificar e formatar todos os arquivos `.md` do projeto conforme as regras acima.
