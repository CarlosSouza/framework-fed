# Framework FED

## Organização dos arquivos

*(?) - opcional*

<pre>
config.rb
/css
  fonts (?)
estrutura.txt
form.html
humans.txt
imagens
index.html
js
  libs
    jquery-1.10.2.js
    modernizr-custom.js
  main.js
  plugins.js (?)
sass
  _elementos.scss
  _fontes.scss
  _reset.scss
  geral.scss
  impressao.scss
  templates.scss
</pre>

### Features

  * Simples. Ao contrário da grande variedade de *frameworks* presentes no mercado, o Framework FED preza pela simplicidade e flexibilidade uso, sem engessar a forma como os layouts são montados.
  * Mobile First + *Responsive Web Design*: framework construído com lógica para ser escalado de acordo com as diferentes resoluções de tela. As regras gerais são usadas por todas as telas e, a medida que for necessário, novas regras são adicionadas para incrementar o layout.
  * SASS: framework todo construído com base no pré-processador SASS, separando o código de desenvolvimento daquele gerado para produção.
  * Compass: em conjunto com SASS, a biblioteca Compass adiciona diversos facilitadores para criação de elementos visuais de forma intuitiva.
  * Performance: por padrão, os arquivos CSS gerados são comprimidos, eliminando espaços e quebras de linha desnecessárias. Além disso, deixamos o código HTML preparado para que puxe o arquivo *plugins.js* visando a unificação de todos os plugins JavaScript utilizados no projeto.

### Plugins recomendados

  * [Swiper](https://github.com/nolimits4web/Swiper): carrossel de imagens e conteúdo preparado para touchscreen
  * [Adaptive Images](http://adaptive-images.com/): serve imagens de diferentes resoluções dependendo do dispositivo utilizado
  * [GreenStock JS](https://github.com/greensock/GreenSock-JS): biblioteca de animação em JS, com performance superior a jQuery e ao próprio CSS3
  * [Magnific Popup](https://github.com/dimsemenov/Magnific-Popup): plugin para criação de lightboxes em geral
  * [Packery](https://github.com/metafizzy/packery): gera layouts flexíveis baseados em conteúdo modular (ex: Pinterest)