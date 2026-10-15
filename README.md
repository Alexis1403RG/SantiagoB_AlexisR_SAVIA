# SAVIA — examen N.º 1

Proyecto estático HTML + CSS. Abrir `index.html` en el navegador. No necesita dependencias.

El sitio incluye la página Inicio y las plantillas `pages/menu.html`, `pages/equipo.html` y `pages/eventos.html` con contenido central pendiente. Siga exclusivamente las especificaciones del examen para conocer el comportamiento esperado. No modifique el tema general ni sustituya el proyecto por otro.

## Diagnóstico de cinco incidencias

| N.º 1 | Comportamiento observado | Causa técnica y ubicación | Corrección realizada | Prueba de verificación | Autor |
|---|---|---|---|---|---|
| 1 | Las tarjetas al entrar a la página desde monitor grande se encontraban de manera vertical y al hacerse pequeña la pantalla se quedaban en ese formato, por lo que no era responsivo|Las condiciones de los mediaquerys no eran correctas y en la versión sin mediaqueries los elementos se encontraban en display flex con orientación column ![alt text](image.png)|![alt text](image-1.png) Se cambió la dirección del eje a row y a column para pantallas pequeñas en el mediaquery ![alt text](image-2.png)|pantalla pequeña![alt text](image-3.png) ![alt text](image-4.png) pantalla grande|Alexis Rivera |
| 2 |Al presionar el boton nuestra carta se abría la página eventos|La referencia href estaba incorrecta ![alt text](image-5.png)|Se corrigió la referencia hacia el menu ![alt text](image-6.png) |redirige a menú ![alt text](image-7.png) |Santiago |
| 3 |El botón explorar nuestra propuesta no tenía referencia a la página|![alt text](image-8.png) No hay referencia en href|Corrección agregando la referencia indicada ![alt text](image-10.png)|El botón ahora redirecciona a la página ![alt text](image-11.png)|Alexis Rivera|
| 4 |El botón explorar nuestra propuesta es de color rojo|El color estipulado es rojo ![alt text](image-12.png)|Se cambia el color a dorado![alt text](image-13.png) |botón color dorado ![alt text](image-14.png)| Santiago|
| 5 |el logo y la navegación en pantallas pequeñas se observa en acomodo row |![alt text](image-15.png) Esto debido a que el media query así lo indica para pantallas menores a 760px |La correción es poner la orientación a column en el media query ![alt text](image-16.png)|![alt text](image-17.png) | Santiago y Alexis |

## Responsables de las funcionalidades

| Estudiante | Página asignada | Rama | Commits principales |
|---|---|---|---|
| | | | |

## Evidencias Git

| Funcionalidad/corrección | PR hacia develop | Revisor | Resultado de merge / conflicto si ocurrió |
|---|---|---|---|
| | | | |

## Verificación final
Registrar las pruebas de funcionamiento a 1280 px y 375 px, enlaces y páginas.
