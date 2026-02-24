# Flexbox y Flex Direction

En esta lección vimos cómo funciona **Flexbox** y cómo organizar elementos dentro de un contenedor.

## Contenedores flex
Cada vez que le pones `display: flex` a un elemento, ese elemento se vuelve un **contenedor flex**.  
- `.container` es el contenedor grande que contiene todo el bloque de imágenes.  
- `.img_block` es un contenedor dentro de `.container` que organiza cada imagen individualmente.

## Dirección de los elementos (`flex-direction`)
- Por defecto, los elementos se colocan uno al lado del otro (**row**).  
- Cambiando a **column**, se apilan uno sobre otro.

## Contenedores anidados
Cada contenedor solo afecta a sus hijos directos:  
- `.container` centra y organiza todo el bloque de imágenes.  
- `.img_block` organiza las imágenes dentro del bloque, sin afectar al contenedor grande.

## 🎯 Clases de alineación principal
### 🟢 center
- justify-content: center;

Centra los elementos en el eje principal.
Como la dirección por defecto es row, el eje principal es horizontal.

- align-items: center;
Centra los elementos en el eje secundario (vertical en este caso).

👉 Resultado: centrado perfecto en ambos ejes.


### 🔵 flex-start
Coloca los elementos al inicio del eje principal.
Es el valor por defecto.

👉 Resultado: las imágenes aparecen pegadas al lado izquierdo.

### 🔴 flex-end
Coloca los elementos al final del eje principal.

👉 Resultado: las imágenes se alinean a la derecha.

### 🟡 space-between
El primer elemento se pega arriba.
El último se pega abajo.

👉 REsultado: No hay espacio arriba ni abajo. El espacio restante se distribuye entre ellos.

### 🟠 space_around
Distribuye espacio alrededor de cada elemento.

👉 Resultado: El espacio de arriba y abajo es la mitad que el espacio entre elementos.

### 🟣 space_evenly
Distribuye el espacio exactamente igual entre:

Parte superior

Entre elementos

Parte inferior

👉 Resultado. Todo el espacio es uniforme.










