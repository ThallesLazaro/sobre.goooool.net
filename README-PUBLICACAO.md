# Publicação de sobre.goooool.net no GitHub Pages

O pacote foi preparado para ser enviado diretamente à raiz do repositório.

## Estrutura

- todos os arquivos ficam na mesma pasta;
- as páginas públicas são arquivos sem extensão, como `videos`, `faq` e `guia-tecnico-automatico`;
- `index.html` continua sendo a página inicial e `404.html` continua sendo a página de erro;
- os endereços públicos ficam limpos, como `https://sobre.goooool.net/videos`, sem `.html` e sem barra final;
- `CNAME` aponta para `sobre.goooool.net`;
- `sitemap.xml`, `robots.txt`, `llms.txt` e `llms-full.txt` acompanham a publicação;
- `.nojekyll` mantém os arquivos exatamente como estão no repositório, sem front matter ou processamento adicional.

## Como publicar

1. Extraia o ZIP.
2. Envie todos os arquivos para a raiz do repositório do GitHub Pages.
3. Em **Settings → Pages**, publique a branch/pasta em que esses arquivos foram enviados.
4. Mantenha o arquivo `CNAME` na raiz para o domínio personalizado.
5. Depois da publicação, teste `/`, `/videos`, `/faq` e `/guia-tecnico-automatico`.

Não é necessário adicionar `permalink` às páginas.
