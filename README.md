# Mostrar e esconder senha do input

<p align="center">
  <img src="https://github.com/thailoeduardo/mostrar-esconder-senha/blob/master/print-1.png">
</p>

```js
var pass = document.getElementById('password');
var eye = document.getElementById('eye');
var btn =  document.getElementById('btn');

btn.addEventListener('click', showPass, false);

function showPass () {
 if (pass.type == 'password') {
  pass.type = 'text';
  eye.classList.remove('glyphicon-eye-open');
  eye.classList.add('glyphicon-eye-close');
 } else {
    pass.type = 'password';
    eye.classList.remove('glyphicon-eye-close');
    eye.classList.add('glyphicon-eye-open');
   }
};
```

<p align="center">
  <img src="https://github.com/thailoeduardo/mostrar-esconder-senha/blob/master/print-2.png">
</p>

