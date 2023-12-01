# Portfolio V2
Nova versão do meu portofolio.

## Conteudo

- [Portfolio V2](#portfolio-v2)
  - [Conteudo](#conteudo)
  - [Visão geral](#visão-geral)
    - [Links](#links)
  - [Meu processo](#meu-processo)
    - [Feito com](#feito-com)
    - [O que eu aprendi](#o-que-eu-aprendi)
    - [Desenvolvimento contínuo](#desenvolvimento-contínuo)
    - [Recursos úteis](#recursos-úteis)
  - [Autor](#autor)

## Visão geral

<!-- ### Rascunho -->

<!-- ![](/src/imagens/Portofolio.png) -->
<!-- <div>  -->
  <!-- <img align="center" height="150em" src="/src/imagens/Contato.png" /> -->
  <!-- <img align="center" height="150em" src="/src/imagens/Sobre.png" /> -->
  <!-- <img align="center" height="150em" src="/src/imagens/Habilidades.png" /> -->
<!-- </div> -->

### Links

- Codigo na web URL: [GitHub](https://github.com/Akherox/portofolio-v2)
- Site ao vivo URL: [Vercel Pages](https://portfolio-v2-akherox.vercel.app/)

## Meu processo

### Feito com

- Semântica de HTML5 linguagen de marcação, CSS e JavaScript.

### O que eu aprendi

Chamar variaveis do CSS no arquivo HTML

```html
<a href="#" class="logo">Bryan. <span class="animate" style="--i:1;"></span></a>

<div class="bx bx-menu" id="menu-icon"><span class="animate" style="--i:2;"></span></div>
```
```css
.logo .animate,
.navbar .animate,
#menu-icon .animate,
.home.show-animate .animate {
    animation: showRight 1s ease forwards;
    animation-delay: calc(.3s * var(--i));
}
```
Usar variaveis no CSS
```css
:root {
    --bg-color: #081b29;
    --second-bg-color: #112e42;
    --text-color: #ededed;
    --main-color: #00abf0;
}

body {
    background: var(--bg-color);
    color: var(--text-color);
}
```

### Desenvolvimento contínuo

Fazer um código mais limpo (menos repetições).

### Recursos úteis

- [Recurso de exemplo de portofolio](https://portofolio-akherox.vercel.app/)
- [Recurso de exemplos CSS](https://codepen.io/)
- [Recurso de icones](https://boxicons.com/?query=up)
- Esses sites me deram ideias para desenvolver o meu "Portofolio V2" e usar os icones.

## Autor

- Linkeding - [Bryan Bravo](https://www.linkedin.com/in/alex-bravo-008-mk)
