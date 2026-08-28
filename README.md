# Caça Ofertas — GitHub Pages

Pacote pronto para hospedar as duas versões no mesmo repositório.

## Estrutura

- `/index.html` → página principal (Versão 2 — tráfego pago)
- `/v1/index.html` → Versão 1
- `/v2/index.html` → Versão 2
- `/comparar.html` → comparação V1 x V2

## URLs depois de publicar

Se o repositório se chamar `caca-ofertas`:

- Principal: `https://SEU-USUARIO.github.io/caca-ofertas/`
- V1: `https://SEU-USUARIO.github.io/caca-ofertas/v1/`
- V2: `https://SEU-USUARIO.github.io/caca-ofertas/v2/`
- Comparador: `https://SEU-USUARIO.github.io/caca-ofertas/comparar.html`

## Como publicar

1. Crie um repositório público no GitHub, por exemplo `caca-ofertas`.
2. Envie **todo o conteúdo desta pasta**, preservando as pastas `v1` e `v2`.
3. Abra `Settings > Pages`.
4. Em `Source`, escolha `Deploy from a branch`.
5. Selecione a branch `main` e a pasta `/ (root)`.
6. Clique em `Save`.

## Meta Pixel e Google Analytics

Os arquivos HTML possuem comentários no `<head>` indicando onde colar os scripts do Meta Pixel e Google Analytics/Google Ads.

Para um teste A/B manual, use links separados de V1 e V2 nos conjuntos de anúncios e compare cliques/Leads.


## Atualização visual

A imagem principal foi substituída pela arte promocional enviada, no lugar da logo, nas versões principal, V1 e V2.
