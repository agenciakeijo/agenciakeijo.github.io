# agenciakeijo.github.io

Landing page da Keijo Digital, publicada em https://agenciakeijo.github.io

- `index.html` — a página (HTML, CSS e JS num arquivo só), com meta tags, Open Graph, Twitter Card e JSON-LD (organização, site, oferta do Raio-X e FAQ)
- `favicon.svg` — ícone ij da marca
- `apple-touch-icon.png` (180×180) e `icon-512.png` (512×512) — ícones em PNG gerados do `favicon.svg`
- `og-image.png` (1200×630) — imagem de compartilhamento (Open Graph / Twitter)
- `robots.txt` e `sitemap.xml` — rastreamento por buscadores
- `llms.txt` — resumo factual da agência para buscadores de IA

Se mudar o texto principal, o FAQ ou o logo, lembre de atualizar também o JSON-LD no `<head>` (o texto das respostas precisa ser idêntico ao do FAQ visível) e regenerar o `og-image.png`.

Para publicar: este repositório precisa se chamar `agenciakeijo.github.io` e pertencer à organização `agenciakeijo` no GitHub. Em Settings → Pages, escolha "Deploy from a branch", branch `main`, pasta `/ (root)`.
