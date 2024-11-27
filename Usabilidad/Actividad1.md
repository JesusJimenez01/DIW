# Actividad 1 - Ejercicios sobre usabilidad
Realizar los ejercicios de usabilidad propuestos en el apartado 3 de esta página: [https://www.eniun.com/tutorial-usabilidad-web/](https://www.eniun.com/tutorial-usabilidad-web/)

## 3.7.1 Ejercicio sobre usabilidad en los textos
El texto del ejercicio presenta varios errores que dificultan su usabilidad, empezando por la segunda linea del codigo HTML ```(<h3>La Revolución de la informática</h3>)``` que es un h3 cuando al ser el titulo debería ser h1 para mejorar la presentación ```(<h1>La Revolución de la informática</h1>)```. 

Luego **cambiaría el tamaño** del texto que actualmente es de 12px como se puede ver en la linea 5 del archivo CSS ```font-size: 12px;``` y lo aumentaría unos cuantos pixeles para mejorar la legibilidad por ejemplo ```font-size: 16px;```. También se podría **cambiar la fuente** que actualmente es 'Times New Roman' ```(font-family: 'Times New Roman', Times, serif;)``` y se puede poner otra más atractiva visualmente como puede ser 'Roboto' ```(font-family: 'Roboto', sans-serif;)```. Además, mejoraría los párrafos **añadiendo una división** más clara entre ellos y **dividiendo** el primer fragmento en algún párrafo más ya que es demasiado extenso y cambiaría el color para añadir más contraste y que el texto se vea mejor.

Por último, pondría la información más importante en **listas** para hacer el texto más comprensible, como se podría hacer añadiendo una lista para las acciones para mejorar la seguridad que se menciona en el texto.

## 3.7.2 Ejercicio sobre usabilidad en formularios
Para empezar, **aumentaría el tamaño del texto** para que se vea todo mejor y **cambiaría el título** para hacerlo más descriptivo, luego, **añadiría un asterisco rojo** al lado de las secciones que sean obligatorias.
También **añadiría un ```placeholder```** dentro de los ```input``` para que el usuario tenga más claro del tipo de dato que debe introducir y el botón de enviar lo pondría de un **color más llamativo** y **aumentaría el tamaño** para que sea más visible para el usuario, y además, haría que al pulsarlo apareciese un **mensaje de "feedback"** en el que diga si se han enviado los datos de forma exitosa o ha ocurrido algún error.
Por último, **cambiaría la fuente** del texto para que tenga un aspecto más moderno y sea visualmente agradable.

## 3.7.3 Ejercicio sobre usabilidad en imágenes
Hice algunas mejoras en el código HTML y CSS para que las imágenes sean más fáciles de usar. Primero, **añadí un texto alternativo** a la etiqueta <img> para que los usuarios puedan entender de qué se trata la imagen: ```<img src="https://www.eniun.com/wp-content/uploads/Curso-Visual-Studio-Code.png" alt="Captura de pantalla de un curso sobre Visual Studio Code">```
También hice que la imagen se **ajuste mejor** en diferentes pantallas, cambiando su ancho al 100% y limitando el tamaño máximo a 300px: ```.image-container img {
  width: 100%; /* Hacer la imagen responsiva */
  height: auto;
  max-width: 300px; /* Limitar el tamaño máximo */
}```
Además, **mejoré el contraste** del texto sobre la imagen de fondo. **Cambié el color** del texto a blanco y le agregué una **sombra** para que sea más fácil de leer: ```.background-image {
  color: #ffffff; /* Cambiar el color del texto para mayor contraste */
  text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.7); /* Agregar sombra al texto */
}```

## 3.7.4 Ejercicio sobre usabilidad en el espaciado de los elementos
En este ejercicio, empezaría **aumentando el margen** de los titulos "h" para que se vea claramente y así darle una mayor importancia, además de que mejoraría la legibilidad. Tambíen **aumentaría la distancia entre párrafos** para que la página esté menos sobrecargada y sea más atractiva visualmente. luego, a la barra de navegación le **añadiría más espacio** entre las opciones y adémas le pondría un **color de fondo** y haría que al **pasar el ratón** por encima el fondo se vuelva un poco más oscuro, esto mejoraría el aspecto y modernizaría el diseño, además de hacer que sea mucho más fácil de ver. Por último, cambiaría la tabla y la haría lo **más grande** posible para que ocupe todo el largo de la pantalla y en cada fila **alternaría tonos de grises suaves** para que se distingan mejor las diferentes filas y todo sea más fácil de ver, además de añadir un **efecto hover** para que al pasar el ratón el fondo se vuelva más oscuro y así sea más cómodo para que el usuario interactúe.


