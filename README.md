Configurar geany
----------------

Abri Constuir ->  Establecer comandos de construccion  y en Ejecutar: cd ..; yarn dev  %e/%f

Con eso cuando arrancas apretas f5 y se prende el browser, los cambios van viendose automaticamente


Configurar yarn
---------------

entrar a donde se ubica el package.json y escribir

``` 
$ npm install
```

para exportar crear la carpeta pdf y escribir por ejemplo

```
$ yarn build presentacion/curso2-dia3.md --print pdf/slides.pdf
```