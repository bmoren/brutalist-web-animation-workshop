# brutalist-web-animation-workshop
a workshop on brutalist web animations using animate.css &amp; friends

1. create a new index.html document
1. link to <a href="https://daneden.github.io/animate.css/">animate.css</a> CDN in the head of your document
1. link the `extendanimate.css` stylesheet from this repo
1. lay out a brutalist composition using flexbox or CSS grid. Think about what makes the elements of the web unique. what is its essence? what is its materiality? (hint: `vw` & `vh` are your friends!)
1. use the following classes to help animate!
    +  check <a href="https://daneden.github.io/animate.css/">animate.css</a> documentation for animation styles
    + `animated` make an element animated!
    + `alternate` do the animation forwards and backwards
    + `infinite` loop the animation forever
    + `duration1s` use the numbers 1-10 to change the animation to last 1-10 seconds. (you could use a custom style to go longer!)

### example element:
  ```html
  <div class="animated alternate infinite bounceInRight gradient duration4s"></div>
  ```
