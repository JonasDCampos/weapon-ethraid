# Armas — Campeões de Ethraid

Site estático (GitHub Pages). Arquivos:
- `index.html` — a página
- `data/dados.json` — TODOS os dados (armas, propriedades, blocos culturais)

## Publicar
1. Crie um repositório no GitHub e envie estes arquivos (mantendo a pasta `data/`).
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.
3. O site fica em `https://USUARIO.github.io/REPOSITORIO/`.

## Como o Lucas edita
**Pelo site:** marcar "Modo edição" → ✎ na arma (ou editar propriedades/blocos direto na aba) → "Salvar no GitHub".
Precisa de um token: GitHub → Settings → Developer settings → Fine-grained tokens → só este repositório → *Contents: Read and write*. O Lucas também precisa ser colaborador do repositório.
**Sem token:** "Baixar JSON" e substituir `data/dados.json` pelo botão *Add file → Upload files* no GitHub.
Todo salvamento vira um commit, então o histórico/desfazer é o do próprio GitHub.

Teste local: `python -m http.server` na pasta e abrir http://localhost:8000
