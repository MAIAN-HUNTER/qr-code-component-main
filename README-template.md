# Frontend Mentor - QR code component

Olá, Este é o meu primeiro projeto feito pelo frontend mentor e estou muito feliz de compartilha-lo com o mundo!

## Ideias, Planejamento e Execução
incialmente, pensei em fazer do projeto o mais simples e objetivo possivel, com uma fonte padrão "Roboto" do google-fonts. Simples, porem legivel e eficaz. O minimo de linhas também para tornar mais rapida a leitura do usuario. Optei também por classificar paragrafos, titulos e design por tags HTML e classes CSS para maior versatilidade na manipulação de estilos tanto das fontes, como imagem QR code e o design das bordas. decidi também estilizar o componente QR code para diferentes resoluções de dispositivos para desktops com resoluções distintas e smartphones.

### O que eu aprendi

principalmente estilizações no CSS. classes no CSS e tags no HTML podem trabalhar em conhunto para maior precisão no  design. o uso de media queries tambem em resoluções de diferentes dispositivos tamém foi um otimo desafio para meu entendimento da ferramenta na melhora do design

Pontos de destaque das tags HTML e classes CSS:

```html
<section class="container">
    <div class="attribution">
        <img src="src/images/image-qr-code.png" alt="">

      <h1>Improve your front-end skills by building projects</h1>

      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>


    </div>
</section>
        <p class="credits">Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
        Coded by <a href="#">MAIAN-HUNTER</a>.</p>
```
```css
img{
    border-radius: 16px;
    max-width: 100%;
    
}

.attribution{
    display: flex;
    flex-wrap: wrap;
}

.attribution h1{
    padding: px;
    font-size: 30px;
    text-align: center;
}

.attribution p{
    display: flex;
    flex-wrap: wrap;
    text-align: center;
}

p{
    margin-left: 10px;
    margin-bottom: 10px;
}
@font-face {
    font-family: 'roboto';
    src: url('../../design/fonts/Roboto-Regular.ttf');
}
body{
    margin: 50px;
    font-family: 'roboto';
    
}

.container{
    display: flex;
    justify-content: center;
    border: 1px solid;
    border-radius: 16px;
    padding: 30px;
    margin: 400px;
    max-width: 100%;
    align-items: center;
}

/* For desktop */
@media (max-width: 3440px){
    .container{
        max-width: 500px;
        margin: 300px;
        margin-left: 1000px;
    }
    .credits{
        margin-left: 800px;
    }
    
}

@media (max-width: 1024px){
    .container{
        max-width: 390px;
        margin: 90px;
        margin-left: 200px;
    }
    .credits{
        margin-left: 100px;
    }
    
}

@media (max-width: 1440px){
    .container{
        max-width: 390px;
        margin: 90px;
        margin-left: 400px;
    }
    .credits{
        margin-left: 100px;
    }
    
}

/* For smartphones */
@media (max-width: 768px) {
    
    .container{
       min-width: 300px;
       margin: 80px;
   }
   .credits{
    margin-left: 0px;
   }
 }
```
### Desenvolvimentos futuros
Javascript, React e Back end. pretendo trabalhar com a vasta biblioteca de informações destas linguagens para melhor desenvolvimento profissional pois não estou muito familiarizado com as mesmas  

### sites com recursos Úteis

- [site W3schools](https://www.w3schools.com/css/css_rwd_intro.asp) - Este site me auxiliou a me localizar melhor nas diversas ferramentas de estilizações que o CSS tem a oferecer. Com certeza será um site que salvarei nos Favoritos.

## Autor
- Frontend Mentor - [@MAIAN-HUNTER](https://www.frontendmentor.io/profile/MAIAN-HUNTER)
- Linkedin - [Maian-Lucas](https://www.linkedin.com/in/maian-lucas-1a796026a/)

## Conhecimentos
92% de meu conhecimento foi adquirido pelo curso de programação Dev Quest, oa outros 8% foram de documentações de sites da internet como o proprio Frontend Mentor, W3schools e de videos da plataforma youtube.