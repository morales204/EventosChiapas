# Registro de Conflicto: index.html

## Archivo afectado:
`index.html`

## Descripción del conflicto:
Se presentó un conflicto al intentar hacer `merge` entre la rama `index` y la rama `main`. Ambas ramas modificaron la misma sección del archivo HTML (`div.slider-txt`), específicamente el contenido del encabezado y el párrafo.

### Conflicto detectado:
```html
<<<<<<< index
<h1>Chiapas</h1>
<p>Lorem eventos</p>
=======
<h1>Eventos para chiapas</h1>
<p>Evento de todos los tipos</p>
>>>>>>> main

Se decidió conservar el contenido más informativo de la rama main. El bloque final quedó así:
 <h1>Chiapas</h1>
<p>Evento de todos los tipos</p>

