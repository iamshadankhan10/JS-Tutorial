# Project related to DOM

## project link

[Click here](https://stackblitz.com/edit/dom-project-chaiaurcode?file=1-colorChanger%2Findex.html)

# Solution code

## project 1

```javascript
console.log("Shadan")
const buttons = document.queryelector(',button')
const body = document.querySelector('body');

buttons.forEach(function (button){
  button.addEventListener('click', function(e){
    if(e.target.id === 'grey'){
      body.style.backgroundColor = e.target.id
    }
    if(e.target.id === 'white'){
      body.style.backgroundColor = e.target.id
    }
    if(e.target.id === 'blue'){
      body.style.backgroundColor = e.target.id
    }
    if(e.target.id === 'yellow'){
      body.style.backgroundColor = e.target.id
    }
    

  });
});



```
