# Dmitriy Mossin

## Contacts

- _email:_ microcuts@yandex.ru
- _discord:_ DN˜MOH (@eldr0n-git)
- _mobile phone:_ +77011821196

## Brief info

My main goal is to improve my skills at frontend. Get the fresh air and involve in modern trends.

## Skills

Strong at HTML, CSS, jQuery, SCSS and LESS. Learning vanilla JavaScript. Using SVN.

## Code example

```javascript
function getRandomAlpha() {
  var randomAlpha;
  randomAlpha = Math.random();
  return randomAlpha;
}
function getRandomId(min, max) {
  var randomId;
  randomId = "#px" + Math.floor(Math.random() * (max - min + 1) + min);
  return randomId;
}
if (thispage == "main") {
  let pix;
  setInterval(function () {
    pix = document.querySelector(getRandomId(1, 40));
    pix.setAttribute("opacity", getRandomAlpha());
  }, 700);
}
```