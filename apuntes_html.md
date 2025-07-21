# Apuntes HTML

## Definición de HTML

HTML es un lenguaje de marcado que se utiliza para crear la estructura y el contenido de las páginas web. Permite definir elementos y etiquetas que representan diferentes tipos de contenido, como títulos, párrafos, imágenes y enlaces. Estos elementos son interpretados por los navegadores web para mostrar el contenido correctamente al usuario.

## Estructura básica de un documento HTML

Un documento HTML se estructura utilizando etiquetas HTML que envuelven el contenido. La estructura básica de un documento HTML es la siguiente:

```html
<!DOCTYPE html>
<html>
<head>
  <title>Título de la página</title>
</head>
<body>
  Contenido de la página
</body>
</html>
```

## Elementos y etiquetas

En HTML, los elementos se definen utilizando etiquetas. Cada etiqueta tiene una estructura básica, que consiste en una etiqueta de apertura y una etiqueta de cierre, que envuelven el contenido.  

Los atributos son especificaciones de los elementos los cuales van dentro de las etiquetas, por ejemplo `style` dentro de un `<p>`, `href` en un enlace o `src` en una imagen.

**Ejemplo:**

```html
<p>Este es un párrafo de texto.</p>
```

En este ejemplo, la etiqueta `<p>` se utiliza para definir un párrafo de texto. La etiqueta de apertura `<p>` indica el inicio del párrafo, y la etiqueta de cierre `</p>` indica el final del párrafo.

## Etiquetas fundamentales

- `<!DOCTYPE html>`: Define el tipo de documento como HTML5.  
- `<html>`: Envuelve todo el contenido de la página.  
- `<head>`: Contiene información meta y enlaces a archivos externos.  
- `<title>`: Define el título de la página que se mostrará en la pestaña del navegador.  
- `<body>`: Contiene el contenido principal de la página.

## Algunas etiquetas comunes utilizadas en HTML

- `<h1>` a `<h6>`: Se utilizan para definir encabezados de diferentes niveles.  
- `<p>`: Se utiliza para definir párrafos de texto.  
- `<a>`: Se utiliza para crear enlaces.  
- `<img>`: Se utiliza para insertar imágenes.  
- `<ul>` y `<li>`: Se utilizan para crear listas no ordenadas.  
- `<ol>` y `<li>`: Se utilizan para crear listas ordenadas.  
- `<div>`: Se utiliza para agrupar elementos y crear divisiones en la página.

## Ejemplos y demostraciones

### Ejemplo de un párrafo de texto:

```html
<p>Este es un párrafo de texto.</p>
```

### Ejemplo de un encabezado:

```html
<h1>Este es un encabezado de nivel 1</h1>
```

### Ejemplo de una lista no ordenada:

```html
<ul>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <li>Elemento 3</li>
</ul>
```

### Ejemplo de un enlace:

```html
<a href="https://www.usbcali.edu.co">Este es un enlace a la página de la USB</a>
```

### Ejemplo de una imagen:

```html
<img src="enlace/ruta-imagen.jpg" alt="texto alternativo" width="50" height="100">
```
