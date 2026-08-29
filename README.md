# Caça Ofertas — GitHub Pages

Pacote pronto para hospedar seis landing pages no mesmo repositório.

## Estrutura

- `/index.html` → página principal (Versão 2 — tráfego pago)
- `/v1/index.html` → Versão 1
- `/v2/index.html` → Versão 2
- `/comparar.html` → comparação V1 x V2
- `/beleza/v1/` → Beleza & Autocuidado — V1 (clean/confiança)
- `/beleza/v2/` → Beleza & Autocuidado — V2 (tráfego pago)
- `/mamae-bebe/v1/` → Mamãe & Bebê — V1 (clean/confiança)
- `/mamae-bebe/v2/` → Mamãe & Bebê — V2 (tráfego pago)

## URLs depois de publicar

Se o repositório se chamar `caca-ofertas`:

- Principal: `https://SEU-USUARIO.github.io/caca-ofertas/`
- V1: `https://SEU-USUARIO.github.io/caca-ofertas/v1/`
- V2: `https://SEU-USUARIO.github.io/caca-ofertas/v2/`
- Comparador: `https://SEU-USUARIO.github.io/caca-ofertas/comparar.html`
- Beleza V1: `https://SEU-USUARIO.github.io/caca-ofertas/beleza/v1/`
- Beleza V2: `https://SEU-USUARIO.github.io/caca-ofertas/beleza/v2/`
- Mamãe & Bebê V1: `https://SEU-USUARIO.github.io/caca-ofertas/mamae-bebe/v1/`
- Mamãe & Bebê V2: `https://SEU-USUARIO.github.io/caca-ofertas/mamae-bebe/v2/`

## Como publicar

1. Crie um repositório público no GitHub, por exemplo `caca-ofertas`.
2. Envie **todo o conteúdo desta pasta**, preservando as pastas `v1`, `v2`, `beleza`, `mamae-bebe` e `assets`.
3. Abra `Settings > Pages`.
4. Em `Source`, escolha `Deploy from a branch`.
5. Selecione a branch `main` e a pasta `/ (root)`.
6. Clique em `Save`.

## Meta Pixel e Google Analytics

Todas as páginas usam o Meta Pixel `1595527468878177`. As páginas gerais originais foram preservadas sem alteração. As novas páginas enviam, em cada clique de WhatsApp, o evento padrão `Lead` com `content_name` e `content_category`, mais o evento personalizado `WhatsAppJoinClick` com `grupo`, `landing` e `cta_placement`.

Identificação dos novos grupos:

- Beleza & Autocuidado: `grupo: beleza_autocuidado`, `landing: v1` ou `v2`
- Mamãe & Bebê: `grupo: mamae_bebe`, `landing: v1` ou `v2`

Para um teste A/B manual, use links separados de V1 e V2 nos conjuntos de anúncios e compare cliques/Leads.


## Atualização visual

A imagem principal foi substituída pela arte promocional enviada, no lugar da logo, nas versões principal, V1 e V2.
