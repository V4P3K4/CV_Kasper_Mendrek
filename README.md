# CV_Kasper_Mendrek
10 códigos HTML básicos para páginas web (con ejemplos)
Alejandra Rubio Bravo Alejandra Rubio Bravo 22/07/2019
El lenguaje secreto de la tecnología
Estando en el proceso de creación de tu página web, puede que te hayas topado en internet con términos como editor HTML, código HTML o etiquetas HTML.  


Aunque la mayoría de las plataformas para crear sitios web (como WordPress) son bastante fáciles de utilizar y no requieren de grandes conocimientos técnicos, conocer más sobre HMTL te ayudará a entender conceptos de programación y te preparará para cuando sea hora de modificar o mejorar la apariencia de tu sitio web.

Por eso, en esta ocasión te compartimos algunas nociones básicas del tema, así como los 10 códigos HTML que debes conocer, acompañados de ejemplos para que aprendas a utilizarlos.

¿Qué es el HTML?
Las siglas HTML vienen de “Hyper Text Markup Language” o Lenguaje Marcado de Hipertexto.

Los códigos HTML son el lenguaje universal que se utiliza para crear y dar formato a los sitios web. Funcionan en cualquier sistema operativo (Windows, Mac, Linux, etc.) y con cualquier navegador (Chrome, Explorer o Mozilla).

Usa HTML para dar formato a tu página web

Aunque no se trata de un lenguaje de programación muy sofisticado, saber manejar HTML te permite insertar otros códigos más potentes, como los de Javascript, por ejemplo. Ahora veamos el elemento de base de la sintaxis del HTML: las etiquetas.

Etiquetas HTML
El lenguaje HTML está conformado por un sistema de etiquetas en serie o tags, que incluyen instrucciones que los navegadores traducen como:

Imágenes
Texto
Hipervínculos
Listas de palabras
Tablas, etc.
Así, para que un elemento de este tipo pueda ser leído, la etiqueta debe tener dos partes: una etiqueta de inicio (<etiqueta>) y una de cierre (</etiqueta>) entre guiones (< >).

Por ejemplo, las etiquetas <strong> y </strong> definen un texto en negrita. Si en nuestro documento HTML escribimos una frase con el siguiente código:

<strong>Este texto va en negritas.</strong>
El resultado será:

Ejemplo de código HTML

¡Inténtalo tú mismo! Inserta el código anterior en un visualizador HTML.

Como seguro habrás notado, la etiqueta inicial sirve para definir el comportamiento del contenido (por ejemplo, si un texto irá en negritas o si tendrá un tamaño específico), y la de cierre le indica al navegador hasta dónde debe llegar ese comportamiento. Para construir los “cierres” sólo necesitas agregar una diagonal (/) al inicio de la etiqueta.

Recuerda: de no poner la etiqueta de cierre, todo lo que escribas después de la etiqueta de inicio se desplegará con ese formato.
 

Cabe destacar que no todas las etiquetas necesitan forzosamente un “cierre”. Por ejemplo, el código <br> para introducir saltos de línea es considerado un “elemento vacío” y puede ir por sí solo en cualquier parte del cuerpo del texto.

Para la creación de sitios web completos, usar documentos HTML te permitirá tener organizados en un solo lugar todos los códigos que vayas a usar en cada página. Este documento lo puedes elaborar en el editor de textos de tu preferencia (Microsoft Word o el mismo bloc de notas), y solo debes asegurarte de guardarlo como .html u otro formato web (es un documento por cada página).

Estructura básica HTML
Antes de ver los códigos básicos, debes saber que la primera línea de tu documento HTML siempre debe contener la etiqueta <!DOCTYPE html>. Esto hará que el código de tu sitio sea legible en cualquier navegador.

Ahora bien, un documento HTML bien armado tiene cuatro etiquetas esenciales para que el contenido se distribuya correctamente. Estas son:

1. HTML
<html> está al inicio de un documento HTML e indica a los navegadores que la página tiene código HTML para que pueda leerlo de esa forma. Siguiendo la sintaxis del lenguaje, la etiqueta de cierre </html> será el último elemento del documento.

2. Encabezado
<head> es la etiqueta que se utiliza para el encabezado de la página. Su principal función es contener toda la información del funcionamiento del sitio. Debido a esto, es un código encriptado que las personas que entran a la página no pueden ver.

3. Título de la página
<title> es la etiqueta que da a tu sitio un nombre para que los usuarios puedan identificarlo. Es el título que puedes ver en las pestañas del navegador.

4. Cuerpo
<body> es la etiqueta que contiene todos los elementos individuales del sitio. O dicho de otra forma, comprende todo el contenido visible del sitio. Aquí podrás insertar texto, imágenes, videos o cualquier otra funcionalidad que desees mostrar.

Ejemplo de las cuatro etiquetas esenciales:

<html>
	<head>
		<title>Mi página de ejemplo</title>
	</head>
	<body>
	Aquí va el contenido
	</body>
</html>
Si creas un documento .html con este código y lo abres en tu navegador, verás algo como esto:
