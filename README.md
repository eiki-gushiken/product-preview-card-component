# Solução do exercício do Frontend Mentor - Product preview card component

Esta é uma solução para o [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). 

### O desafio

Usuários devem ser capazes de:

- Ver o layout da página mais otimizado em cada dispositivo
- Ver o botão interativo com `hover` em "Add to Cart"

### Feito com

- HTML5
- CSS
- CSS Flexbox

### O que aprendi?

Consegui por em prática meus conhecimentos sobre HTML e CSS, revisando temas que já havia estudado e fixando eles melhor na cabeça.
Tive algumas dificuldades no quesito de escolher algumas tags HTML que poderiam ser mais semânticas e mais adequadas nesse caso, e com a responsividade do site, como mudar a imagem de acordo com o tamanho da tela do dispositivo.
Para resolver isso, utilizer a tag `picture`, que funcionou perfeitamente.

```HTML
    <picture class="imagem-produto">
      <source srcset="./src/images/image-product-mobile.jpg" media="(max-width: 576px)">
      <img src="./src/images/image-product-desktop.jpg" alt="Imagem">
    </picture>
```
