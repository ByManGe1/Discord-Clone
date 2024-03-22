### Funciones JavaScript

- Esta funcion dentro del Index.html sirve para que el usuario no pueda hacer click derecho igual que en la pagina Oficial.

```js
<script type="text/javascript">
    window.addEventListener('contextmenu', function (e) {
        e.preventDefault();
    }, false);
</script>
```
### Funciones CSS

- Esto sirve para que el usuario no pueda copiar ningun texto.
```css
    -webkit-user-select: none; 
    -moz-user-select: none; 
    -ms-user-select: none; 
    user-select: none;
```

- Esto sirve para que cuando Selecionamos la opcion de Email o Contraseña se veria con un borde blanco pues esta soluciona el borde blanco. 

```css
    outline: none; 
    border: 1px solid transparent;
```

- Estas son las mas Significantes lo demas es estetica y se puede modificar para cualquier Web.
- Gracias por Leerme TKM


