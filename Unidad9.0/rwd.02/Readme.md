# Implementa un par de patrones de les videos anteriores para revisar las diferentes soluciones.

## Mostly Fluid

* En el siguiente ejemplo con la vista más pequeña, cada div que se encuentre dentro de la clase contenido se apila verticalmente.
* Una vez que el ancho de la pantalla alcanza los 600 píxeles, el div de contenido principal permanece en width: 100%, mientras que el div del otro contenido,el del secundario se muestra como dos columnas debajo del div del contenido principal.
* Pero  al superarse los 800 píxeles, el div del contenedor adopta ancho fijo y se centra en la pantalla.

* [Link al GhPages](https://alexzarazuaa.github.io/web-interface-design/Unidad9.0/rwd.02/Mostly_fluid/index.html)

* [Link al html](./Mostly_fluid/index.html)

## Layout shifter
* Cuando la pantalla sea más pequeña, el contenido se apila verticalmente, pero cambia considerablemente a medida que se agranda la pantalla, con un div a la izquierda y dos div apilados a la derecha.

* [Link al GhPages](https://alexzarazuaa.github.io/web-interface-design/Unidad9.0/rwd.02/Layout_Shifter/index.html)

* [Link al html](./Layout_Shifter/index.html)


## Off canvas

* En este patron, en lugar de apilarse el contenido verticalmente, se usa una declaración **transform**:_ translate(-250px, 0)_ para ocultar dos de los div del contenido fuera de la pantalla mediante la propiedad. 

* Además he usado un poco de código Javascript mostrar los divs agregando una clase abierta al elemento para hacerlo visible. 
* Y medida que se ensancha la pantalla, el posicionamiento fuera de esta se elimina de los elementos y estos se muestran dentro de la ventana de visualización visible.


* [Link al GhPages](https://alexzarazuaa.github.io/web-interface-design/Unidad9.0/rwd.02/OffCanvas/index.html)

* [Link al html](./OffCanvas/index.html)
