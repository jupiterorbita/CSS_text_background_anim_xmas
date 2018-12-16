# Chirstmas CSS Background Text Animation

### by [John Misirlakis](https://www.linkedin.com/in/misirlakis/)  

<p align="center">
  <img style="border:1px solid red"  src="./img/preview_merry_xmas.gif">
</p>

### [check it out here](https://jupiterorbita.github.io/CSS_text_background_anim_xmas/)

sample  css for background animation:

```css
.animated {
  background: url("img/text-bg.png") no-repeat;
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
  -webkit-text-fill-color: transparent;
 
  animation: moveBg 90s linear infinite;
  -webkit-animation: moveBg 90s linear infinite;
}

@keyframes moveBg {
  0% {
    background-position: 0% 30%;
  }
  100% {
    background-position: 100% 50%;
  }
}
```
