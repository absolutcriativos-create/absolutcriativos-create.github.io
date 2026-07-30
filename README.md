# Kiss Me — Landing Page

Landing page de venda direta do Kiss Me (Absolut Criativos).

## Estrutura

- `index.html` — a página completa (HTML/CSS/JS em um único arquivo; as fotos já estão embutidas em base64 dentro dele)
- `assets/` — os 3 vídeos usados na página (produto no hero, demonstração do NFC, unboxing)

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub e suba **esta pasta inteira** (mantendo `index.html` na raiz e a pasta `assets` junto)
2. Vá em **Settings → Pages**
3. Em "Source", selecione a branch (geralmente `main`) e a pasta `/ (root)`
4. Salve — o GitHub vai gerar um link tipo `https://seu-usuario.github.io/nome-do-repo/`

Importante: o `index.html` referencia os vídeos pelo caminho relativo `assets/...` — não mova nem renomeie a pasta `assets`, ou os vídeos vão quebrar.
