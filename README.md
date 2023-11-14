# proyecto-final-life-experience

#  Life Experience

## Proyecto final para curso de desarrollo web de CoderHouse

> Este proyecto se basa en la creación de un sitio web para la contratación de servicios de salas de escape en la ciudad de Buenos Aires.

### Herramientas utilizadas:
- HTML5
- CSS3
- BOOTSTRAP

![SCAPE ROOMS](https://images.unsplash.com/photo-1569002925653-ed18f55d7292?q=80&w=2070&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D "SCAPE ROOMS")

### El sitio consta de 5 páginas HTML relacionadas entre sí, y una página extra dónde se utilizó Bootstrap. Dicha página es la de *sedes*, en la barra de navegación.

Para acceder al quinto HTML, hay que hacerlo desde el index, clickeando en la segunda sala de la parte de abajo, llamada *Futurix Hogares*.

Un detalle. Quería mencionar una posible falla, que en realidad solo pasa con el inspector. Es probable que la descubras solo, pero por las dudas quería mencionarlo para que sepas que lo tuve en cuenta pero no encontré forma de solucionarlo sin usar JS.
En el index hay tres imagenes con hover para agrandar las imagenes, y al llegar al media query de 425 px se transforma en un carrousel. El problema está en que el inspector activa el hover con el click y lo deja activado como si fuera un active, entonces al llegar a la medida 425 px y clickear para cambiar de foto, todo funciona bien, pero el problema es que si volves a agrandar la medida sin desclickear la foto queda activado el hover, y cuando vuelve a la medida superior a 425 la imagen esta agrandada y queda mal, pero se arregla al clickear de nuevo afuera de la imagen. Abriendo el sitio desde un celular directamente no pasa eso, se ve normalmente. 
