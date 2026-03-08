# Blog - Guia de Publicação

Este diretório guarda conteúdos de blog sem precisar exibir link na home.

## Estrutura

- `index.html`: página índice de artigos
- `posts/`: artigos publicados
- `_templates/article-template.html`: modelo base para novo artigo

## Fluxo recomendado para novo artigo

1. Copie `_templates/article-template.html` para `posts/AAAA-MM-DD-slug-do-artigo.html`.
2. Edite:
   - `<title>`
   - `meta description`
   - `canonical`
   - título `<h1>`
   - data de publicação
   - conteúdo do artigo
3. Inclua link do novo artigo em `blog/index.html`.
4. Atualize `sitemap.xml` com a nova URL.
5. Publique e solicite indexação no Google Search Console.

## Boas práticas SEO local

- Incluir termos locais com naturalidade: `Santos`, `SP`, `podologia`, `pé diabético`, `unha encravada`.
- Evitar conteúdo copiado de outros sites.
- Foco em dúvidas reais de pacientes.
- Sempre encerrar com CTA para WhatsApp.
