# Flexbox y Flex Direction

En esta lección vimos cómo funciona **Flexbox** y cómo organizar elementos dentro de un contenedor.

## Contenedores flex
Cada vez que le pones `display: flex` a un elemento, ese elemento se vuelve un **contenedor flex**.  
- `.container` es el contenedor grande que contiene todo el bloque de imágenes.  
- `.img_blocks` es un contenedor dentro de `.container` que organiza cada imagen individualmente.

## Dirección de los elementos (`flex-direction`)
- Por defecto, los elementos se colocan uno al lado del otro (**row**).  
- Cambiando a **column**, se apilan uno sobre otro.

## Alineación dentro del contenedor
- `justify-content` mueve los elementos a lo largo de la dirección principal (horizontal o vertical según el flex-direction).  
- `align-items` centra los elementos en la dirección perpendicular.

## Contenedores anidados
Cada contenedor solo afecta a sus hijos directos:  
- `.container` centra y organiza todo el bloque de imágenes.  
- `.img_blocks` organiza las imágenes dentro del bloque, sin afectar al contenedor grande.
