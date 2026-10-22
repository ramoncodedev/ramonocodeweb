# ramonocode · link bio

Página de link bio do Instagram [@ramonocode](https://www.instagram.com/ramonocode/). HTML e CSS puros, sem build.

## Estrutura

```
index.html          página
css/
  fonts.css         @font-face das duas fontes
  base.css          cores (variáveis), reset, contêiner e layout geral
  hero.css          retrato e reflexo na lente
  intro.css         nome, função, headline e subtítulo
  links.css         botões
  footer.css        rodapé
assets/
  fonts/            Unbounded e Bricolage Grotesque (woff2)
  img/              portrait.webp (celular) e hero.webp (computador)
```

Telas a partir de 900 px mostram o `hero.webp` em tela cheia; abaixo disso, o `portrait.webp` em coluna única.

## Antes de publicar

No `index.html`, troque `55SEUNUMERO` pelo número do WhatsApp com DDD (ex.: `5573999999999`).

## Rodar local

Abra o `index.html` no navegador, ou rode `python3 -m http.server` na pasta.
