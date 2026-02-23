# Unidad 1 . Interfaz Gráfica de Usuario (GUI)

## Introducción
En este tema veremos como construir aplicaciones con interfaz gráfica amigable enfocadas a problemas reales. Si un ser humano quiere interactuar con una máquina necesita un medio para poder hacerlo. Ese medio es, precisamente, lo que se conoce como interfaz de usuario; la parte del sistema que interactúa con el usuario. La interfaz es un lugar de encuentro entre los bits y las personas.  Un evento es la notificación que hace un elemento gráfico cuando el usuario interactúa con él. Por lo tanto, si se realiza alguna acción sobre algún elemento de la interfaz, se dice que se ha generado un evento en dicho elemento.

Los tiempos en que solo los científicos y los desarrolladores de software podían usar los ordenadores han quedado muy atrás. Hoy en día, casi todo el mundo puede manejar un PC o una tableta, a menudo incluso sin necesitar conocimientos especializados previos. No obstante, llegar a esto no fue un camino de rosas. Para hacerlo posible, hubo que desarrollar las interfaces gráficas de usuario, un tipo de interfaz de usuario.

Los primeros conceptos de interfaz gráfica de usuario se desarrollaron en los años 70 en la empresa Xerox. Su propósito principal era permitir manejar ordenadores con el ratón y el teclado en lugar de solo con instrucciones en formato de texto. Xerox Alto fue el primer PC con una interfaz gráfica. Apple le siguió en los años 80 con el Macintosh. Con la aparición de los smartphones y las tabletas, el principio de la interfaz gráfica ha pasado por grandes cambios. Hoy en día, hay pantallas que se pueden utilizar con simples gestos y movimientos de dedos.

### Definición: ¿qué es una GUI?

La GUI es una interfaz entre la persona y la máquina. El objetivo de esta interfaz gráfica es representar el código del backend de un sistema de la forma más clara posible para el usuario para simplificarle las tareas diarias. Para esto, son muy importantes los iconos y las imágenes, ya que solo estos permiten una aplicación universal e independiente del texto. Por ejemplo, casi todo el mundo sabe cómo es un icono de wifi, mientras que la palabra varía mucho en los distintos idiomas.

<img width="1181" height="837" alt="image" src="https://github.com/user-attachments/assets/7026104c-c388-44fb-afab-7eeca08dc07f" />

### ¿Cómo funciona una GUI?

La GUI es una interfaz de usuario que permite a los usuarios comunicarse con el ordenador. Suele estar basada en la interacción a través del ratón y el teclado (aunque el control a través de gestos es cada vez más común): al mover el ratón, el puntero se desplaza en la pantalla. La señal del dispositivo se transmite al ordenador, que luego la traduce en un movimiento equivalente en la pantalla. Por ejemplo, si un usuario hace clic en un determinado icono de programa en el menú, se ejecuta la instrucción correspondiente y se abre el programa.

La GUI es, por lo tanto, una especie de traductor en la comunicación entre el humano y la máquina. Sin la GUI, tendrías que utilizar la línea de comandos para llamar a programas y aplicaciones. Esto podría representarse así (el ejemplo muestra cómo abrir el explorador):

```
  C:\User\Me>start explorer
```

### ¿Cuáles son los componentes de una GUI?

Una GUI combina el diseño visual y las funciones de programación. Por esto, ofrece botones, menús desplegables, campos de navegación, campos de búsqueda, iconos y widgets. Los desarrolladores deben tener siempre en cuenta la facilidad de uso. Los componentes más comunes de una GUI son los siguientes:
1. Campos de entrada
2. Ventana
3. Lienzo (canvas)
4. Marcos
5. Botones
6. Bloques de encabezado
7. Campos de texto

La papelera de reciclaje es un buen ejemplo de un elemento común a la mayoría de los sistemas operativos. Además, su representación gráfica tanto en Windows como en Mac es la imagen de una papelera real. De este modo, el usuario sabe de inmediato que sirve para borrar documentos y archivos.

Al escribir las GUI, los desarrolladores se basan en la programación basada en eventos, porque las acciones del usuario son impredecibles. Por esto las GUI no se pueden programar linealmente, sino que deben escribirse de tal manera que un comando solo se ejecute cuando el usuario dé la señal para este.

## 1.1 Creación de interfaz gráfica para usuarios.

La interfaz gráfica de usuario, conocida también como GUI (del inglés graphical user interface) es un programa informático que actúa de interfaz de usuario, utilizando un conjunto de imágenes y objetos gráficos para representar la información y acciones disponibles en la interfaz. Su principal uso, consiste en proporcionar un entorno visual sencillo para permitir la comunicación con el sistema operativo de una máquina o computador. Habitualmente las acciones se realizan mediante manipulación directa, para facilitar la interacción del usuario con la computadora. 

Surge como evolución de las interfaces de línea de comandos que se usaban para operar los primeros sistemas operativos y es pieza fundamental en un entorno gráfico. Como ejemplos de interfaz gráfica de usuario, cabe citar los entornos de escritorio Windows, el X-Window de GNU/Linux o el de Mac OS X, Aqua. En el contexto del proceso de interacción persona-ordenador, la interfaz gráfica de usuario es el artefacto tecnológico de un sistema interactivo que posibilita, a través del uso y la representación del lenguaje visual, una interacción amigable con un sistema informático.

 La computación gráfica o gráficos por ordenador es el campo de la informática visual, donde se utilizan computadoras tanto para generar imágenes visuales sintéticamente como integrar o cambiar la información visual y espacial probada del mundo real. El primer mayor avance en la gráfica realizada por computadora era el desarrollo de Sketchpad en 1962 por Ivan Sutherland. Este campo puede ser dividido en varias áreas: Interpretado 3D en tiempo real (a menudo usado en juegos de vídeo), animación de computadora, captura de vídeo y creación de vídeo interpretado, edición de efectos especiales (a menudo usado para películas y televisión), edición de imagen, y modelado (a menudo usado para ingeniería y objetivos médicos). El desarrollo en la gráfica realizada por computadora fue primero alimentado por intereses académicos y patrocinio del gobierno. Sin embargo, cuando las aplicaciones verdaderas mundiales de la gráfica realizada por computadora (CG) en televisión y películas demostraron una alternativa viable a efectos especiales más a las tradicionales y las técnicas de animación, los comerciales han financiado cada vez más el avance de este campo.
 
<img width="400" height="299" alt="image" src="https://github.com/user-attachments/assets/8032421a-ea04-4336-98e9-0f36cfd9b531" />

A menudo se piensa que la primera película para usar gráficos realizados por computadora era 2001: A Space Odyssey (1968), que intentó mostrar como las computadoras serían mucho más gráficas en el futuro. Sin embargo, todos los gráficos de computadora en aquella película eran la animación dibujada a mano (por ejemplo, en las pantallas de televisión se simulaba el comportamiento de las computadoras con dibujos), y las secuencias de efectos especiales fue producida completamente con efectos ópticos y modelos convencionales.La computación gráfica o gráficos por ordenador es el campo de la informática visual, donde se utilizan computadoras tanto para generar imágenes visuales sintéticamente como integrar o cambiar la información visual y espacial probada del mundo real.

El primer mayor avance en la gráfica realizada por computadora era el desarrollo de Sketchpad en 1962 por Ivan Sutherland. Este campo puede ser dividido en varias áreas: Interpretado 3D en tiempo real (a menudo usado en juegos de vídeo), animación de computadora, captura de vídeo y creación de vídeo interpretado, edición de efectos especiales (a menudo usado para películas y televisión), edición de imagen, y modelado (a menudo usado para ingeniería y objetivos médicos). El desarrollo en la gráfica realizada por computadora fue primero alimentado por interesesacadémicos y patrocinio del gobierno. Sin embargo, cuando las aplicaciones verdaderas mundiales de la gráfica realizada por computadora (CG) en televisión y películas demostraron una alternativa viable a efectos especiales más a las tradicionales y las técnicas de animación, los comerciales han financiado cada vez más el avance de este campo. A menudo se piensa que la primera película para usar gráficos realizados por computadora era 2001: A Space Odyssey (1968), que intentó mostrar como las computadoras serían mucho más gráficas en el futuro.

Sin embargo, todos los gráficos de computadora en aquella película eran la animación dibujada a mano (por ejemplo, en las pantallas de televisión se simulaba el comportamiento de las computadoras con dibujos), y las secuencias de efectos especiales fue producida completamente con efectos ópticos y modelos convencionales.


 <img width="446" height="614" alt="image" src="https://github.com/user-attachments/assets/d786a8b0-93aa-40d3-98d4-3cb0c40ed1c6" />

## 1.2 Tipos de eventos.

Los eventos son el medio cómo interactúan una clase con otras o con el propio usuario, se encargan de avisar que algo ha ocurrido y de manejarlo de una forma o de otra. Cada vez que escribimos con nuestro teclado, que hacemos clic en un botón o un link, que cambiamos el tamaño de un objeto, estamos generando eventos. Es por ello que, cuando programamos, debemos tener en cuenta la posibilidad (no siempre necesaria, pero lo será a medida que generemos clases cada vez más complejas), tanto de manejar eventos que sólo implican a nuestra clase como de generar nuestros propios eventos, de modo que los usuarios de nuestras clases (en principio nosotros mismos) puedan decidir cómo reaccionará su código ante ellos.

1. Eventos de bajo nivel. Representan entradas o interacciones de bajo nivel con elementos del interfaz gráfico (Cambio de tamaño, cambio del foco, operación con el ratón o con el teclado).

   <img width="400" height="191" alt="image" src="https://github.com/user-attachments/assets/035dc53c-7872-4072-ac9f-62de6bd8d693" />

2. Eventos semánticos. Eventos de alto nivel que encapsulan la semántica del modelo de componentes del interfaz de usuario (Hacer una acción, un cambio de estado en un elemento, etc.). No están relacionados con una clase específica de componente sino que pueden aplicarse a todos los componentes que implementen un modelo semántico similar.
3. Eventos de Foco: Hay muchas razones por las que pasa el foco de un Componente a otro, y cuando esto sucede, se genera un evento focusLost () en el Componente que pierde el foco y el que recibe el foco, genera un evento focusGained (). Es base a esta pequeña explicación, es fácil comprender que haya muchos tipos de Componentes que pueden generar este tipo de eventos, ya que cualquier Componente que pueda ganar el foco también podrá perderlo y generará esos eventos.
4. Evento de teclado: Un objeto KeyListener es instanciado y registrado para recibir los eventos del teclado keyPressed () sobre los objetos Frame, Label, Button y TextField. Cuando se pulsa una tecla, el objeto que tenga el foco en ese momento generará un evento keyPressed(), e incluso la Etiqueta responde al teclado (en este caso).
5. El objeto KeyListener determina el componente visual que ha generado el evento y presenta un mensaje en pantalla.
6. MouseEvent: Se producirá cuando el usuario efectúe un movimiento con el ratón o haga un click .

## 1.3 Manejo de eventos.

Cuando el usuario actúa sobre un componente -- pulsando el ratón o la tecla Return, por ejemplo -- se crea un objeto Event. El sistema manejador de eventos del AWT pasa el Evento a través del árbol de componentes, dando a cada componente una oportunidad para reaccionar ante el evento antes de que el código dependiente de la plataforma que implementan todos los componentes lo procese.

Cada manejador de eventos de un componente puede reaccionar ante un evento de alguna de estas formas:

Ignorando el evento y permitiendo que pase hacia arriba en el árbol de componentes. Esto es lo que hace la implementación por defecto de la clase Component. Por ejemplo, como la clase TextField y su superclase TextComponent no implementan manejadores de eventos, los Campos de texto obtienen la implementación por defecto de la clase Component. Así cuando un TextField recibe un evento, lo ignora y permite que su contenedor lo maneje.

Mediante la modificación del ejemplar de Event antes de dejarlo subir por el árbol de componentes. Por ejemplo, una sublcase de TextField que muestra todas las letras en mayúsculas podría reaccionar ante la pulsaicón de una letra minúscula cambiando el Event para que contuviera la versión mayúscula de la letra.
Reacionando de alguna otra forma ante el evento. Por ejemplo, una sublcase de TextField (o un contenedor de TextField) podrían reaccionar ante la pulsación de la tecla Return llamando a un método que procese el contenido del campo.
Interceptando el evento, evitando un procesamiento posterior. Por ejemplo, un carácter no válido se ha introducido en un campo de texto, un manejador de eventos podría parar el evento resultante y evitar su propagación. Como resultado, la implementación dependiente de la plataforma del campo de texto nunca vería el evento.

Desde el punto de vista de un Componente, el sistema de manejo de eventos del AWT es como un sistema de filtrado de eventos. El código dependiente de la plataforma genera un evento, pero los Componentes tienen una oportunidad para modificar, reaccionar o interceptar el evento antes de que el código dependiente de la plataforma los procese por completo.

## 1.4 Manejo de componentes gráficos de Control.

Las gráficas de control se utilizan en la industria como técnica de diagnósticos para supervisar procesos de producción e identificar inestabilidad y circunstancias anormales. Una gráfica de control es una comparación gráfica de los datos de desempeño de proceso con los “límites de control estadístico” calculados, dibujados como rectas limitantes sobre la gráfica.

Los datos de desempeño de proceso por lo general consisten en grupos de mediciones que vienen de la secuencia normal de producción y preservan el orden de los datos. Las gráficas de control constituyen un mecanismo para detectar situaciones donde las causas asignables pueden estar afectando de manera adversa la calidad de un producto. Cuando una gráfica indica una situación fuera de control, se puede iniciar una investigación para identificar causas y tomar medidas correctivas. Nos permiten determinar cuándo deben emprenderse acciones para ajustar un proceso que ha sido afectado por una causa especial. Nos dicen cuando dejar que un proceso trabaje por sí mismo, y no malinterpretar las variaciones debidas a causas comunes. Las causas especiales se deben contrarrestar con acciones correctivas. Las causas comunes son el centro de atención de las actividades permanentes para mejorar el proceso.

## CONCLUSIONES

Tratamos de los diferentes eventos de interfaces de usuarios que existen,  la manera de crear aplicaciones de manera en que la interfaz gráfica se vea involucrada, también de los métodos que hay para manejar los distintos eventos  componentes gráficos. Como construir aplicaciones con interfaz gráfica.

## REFERENCIAS

Cohn, M., & Morgan, B. (200111). Java,Developer’s Reference. En T. N. Michael, D. Joshi, & T. Trinko. Quinta edición. 
Lopez, R. R. (s.f.). Topicos Avanzados de programación. Obtenido de https://iscitver2011.files.wordpress.com/2011/02/1-1introduccic3b3n.pdf
TECNOLOGICO. (s.f.). Obtenido de http://topicosaprogramacion.PDF.mx/
Topico avanzado programacion. (s.f.). Obtenido de https://sites.google.com/site/topicosavprog/unidad-i
Topicos avanzados. (s.f.). Obtenido de http://topicosaprogramacion.t.mx/2012/02/eventos.PDF.html
