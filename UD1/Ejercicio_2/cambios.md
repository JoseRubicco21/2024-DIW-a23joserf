## Errores visibles

- Poca identidad de marca
- Mala utilización de colores
- Mala utilización de elementos para llamar la atención
- Mala agrupación de elementos
- Funcionalidad que entorpece el uso de la página
- Poco intuitiva
- Mala elección de tipografia para el caso de uso.
- Mala estructuración a nivel de maquetación.
- Uso de etiquetas no descriptivas.
- Mal uso de tamaño de tipografias.
- Mal uso de destaque de contenido. El contenido poco importante es el que mas salta a la vista.

## Listado de cambios

### Colores y representación de marca

En principio todo esta muy por todos lados. Es muy caótico, especialmente para un sitio de noticias.

Por ende se eligirá una paleta de colores mucho más sencilla compuesta por los siguientes colores:

- background: #dad2bc;
- background-dark: #a99985;
- background-darker: #6d6050;
- accent-light: #f5f1ed;
- text-light: #dacccc;
- text: #252323;
- text-dimmed: #4d4a4a54;

### Tipografia

Se cambiará a una tipografia mucho más seria de tipo Serif para la lectura e identidad de la marca.

### Estructuración

#### Html

Se restructura la página para mover todos los anuncions a un aside a la derecha.

Dejando las noticias como contenido principal y la barra de navegación a la izquierda. Todas los links relacionados con redes sociales serán movidos al footer.

Los terminos de uso y condiciones estarán en el footer, resaltados por negrita y como un link que redirige al mismo..

Se renombraran las etiquetas por aquellas cuyo valor sea más significativo.

#### CSS

Se restructura el css tal que este dividido en grupos coherentes. Todas las animaciones serán movidas al fondo, y comentadas.

### Imagenes

El uso de imagenes deberia ser limitado a imagenes .jpg y de bajo pesaje. No se quiere descargar una cantidad enorme de datos al cargar la página, sería recomendable cambiar la imagen a una jpg.

### Popup

El popup será lanzado una sola vez, al iniciar la página y no con un `setTimeout`, Aunque preferiblemente se optaria por no tener esto.
