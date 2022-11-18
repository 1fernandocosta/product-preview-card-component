# column-preview-card-component-main
4º Desafio Front End Mentor - Product preview card component

# Frontend Mentor - Solução de página inicial de notícias

Esta é uma solução para o [Product preview card component](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa/hub/product-preview-card-component-ktPO9Ophrj). Os desafios do Frontend Mentor ajudam você a melhorar suas habilidades de codificação criando projetos realistas. 

### Screenshot

![Screenshot](https://github.com/1fernandocosta/product-preview-card-component/main/blob/main/src/images/screenshot.jpg)

### Links

- URL da solução: [Clique para acessar o código](https://github.com/1fernandocosta/product-preview-card-component)
- URL do site: [Clique para acessar o site](https://1fernandocosta.github.io/product-preview-card-component)

## Meu processo

### Construído com

- HTML5 semântico
- CSS
- Mobile-first

### Aprendizados com desafio

Distribuição do conteúdo em CSS Grid e Media Queries - CSS.

CSS versão mobile:

```
@media screen and (max-width:375px) {
    .container{
        width: 375px;
        height: auto;
    }

    .container .img{
        display: none;
    }

    .container .img-mobile{
width: 375px;
height: 240px;
background-image: url("../images/image-product-mobile.jpg");
display: flex;
background-repeat: no-repeat;
background-size: cover;
background-position: center;
    }

    .container{
        flex-direction: column;
        height: auto;
    }

    .content {
        width: 100%;
        height: auto;
        padding: 15px 15px 25px 15px;
    }
}}
```

### Aprimoramentos futuros

Aprendendo mais um pouco a cada desafio.

## Author

- Facebook - [Fernando Costa de Morais](https://www.fb.com/1fernandocosta)
- Frontend Mentor - [@1fernandocosta](https://www.frontendmentor.io/profile/1fernandocosta)
- Linkedin - [Fernando Costa de Morais](https://www.linkedin.com/in/fernandocostademorais)
