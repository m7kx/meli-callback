# meli-callback

Página estática usada como Redirect URI de um app OAuth do Mercado Livre:
`https://m7kx.github.io/meli-callback/`.

Ela não envia dados a lugar nenhum (CSP `default-src 'none'`, sem script externo, `no-referrer`):
só mostra a URL com `code` e `state` para colar em `meli-core exchange-code --redirect-url '...'`.
