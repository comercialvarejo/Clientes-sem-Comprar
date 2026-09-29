# Painel — Clientes sem Compra em Setembro

Painel com o ranking de vendedores e a lista de clientes que não compraram no mês, com envio da planilha de cada vendedor pelo WhatsApp.

O `index.html` é autossuficiente: os dados e as planilhas (.xlsx) já estão embutidos no próprio arquivo, então não há outras pastas para subir.

## Publicar no GitHub Pages

1. Suba `index.html`, `.nojekyll`, `robots.txt` e este `README.md` na raiz do repositório (branch `main`).
2. No repositório: **Settings → Pages → Build and deployment**.
3. Em *Source* escolha **Deploy from a branch**, selecione `main` e a pasta `/ (root)`, e clique em **Save**.
4. Em 1 a 2 minutos o painel fica disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Atualizar os dados

Basta substituir o `index.html` por uma versão nova (mesmo nome) e fazer o commit. O Pages republica sozinho.

## Observação sobre privacidade

O painel contém nomes de clientes e valores de compra. O `robots.txt` e a meta tag `noindex` evitam que buscadores indexem a página, mas em repositório público qualquer pessoa com o link consegue abrir.
