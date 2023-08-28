<h1>#1 HTML-Curso de FreeCodeCamp</h1>

<h2>Proyecto de FreeCodeCamp con HTML y Git</h2>

En este curso voy a aprender HTML por parte de FreeCodeCamp. Y agradezco mucho por la información de calidad y más interesante que es muy práctico.

<h2>HTML y sus elementos</h2>
Es un lenguaje de marcado de hipertexto, este es el que da forma principal a las páginas webs dandole texto, cuadros de textos, entre otros. 
Ahora, este lenguaje tiene caracteristicas que permite al navegador comprender como debe comportarse ante el usuario al momento de interactuar.
HTML esta conformado principalmente por elementos, de las cuales son las que se ponen en práctica en el curso:
<ul>
  <li>H1 - H6: Este elemento es principalmente para darles encabezados a las páginas webs, dando prioridar de importante por el número 1 como más importante hasta el número 6 como menos importante, ádemas, es importante que el elemento h1 se deberá usar una vez por páginas y usarse sus desendencias si se busca tener encabezados.</li>
  <li>p: Es un elemento que se utiliza para dar párrafos a la página.</li>
  <li>main: <em>Elemento único</em>. Es de suma importancia para personas con discapacidades, que habitualmente acceden a la web a través de programas especiales como los navegadores de voz. Es la que permite clasificar de otros elementos como header y footer.</li>
  <li>a: Llamado elementos anchor, este elemento contiene un enlace que te llevará a otra página con el elemento anchor.</li>
  <li>section: Es una elemento que marcar contenido en un documento HTML y ayuda a ser útil la accesibilidad y la usabilidad del contenido, así como para mejorar la estructuración y la organización del contenido.</li>
  <li>ul: Elemento para comenzar una lista desordenada.</li>
  <li>ol: Elemento para comenzar una lista ordenada.</li>
  <li>li: Elemento que va entre el elemento ul y la cual llevara los nombres de la lista.</li>
  <li>figure: Actua como un section, que encierra una información como una imagen, ilustración, un diagrama, fragmento de código, o un esquema al que se hace referencia en el texto principal, pero que se puede mover a otra página o a un apéndice sin que afecte al flujo principal.</li>
  <li>figcatption: Le da una pequeña descripción a lo que tiene dentro un elemento figure. Es decir, que tiene que existir un figure para tener un figcaption.</li>
  <li>em: Elemento que pone el texto en cursiva.</li>
  <li>strong: Elemento que sobrea más fuerte el texto que esta entre el elemento strong.</li>
  <li>form: Elemento encargado para crear un formulario.</li>
  <li>button: Sirve para crear botones, importante, si esta en un bloque de código que tiene un action, este hace que se direccione automáticamente la información donde tiene la URL del action, ya sea, de un formulario por ejemplo. No olvidar, este elemento es inline como el elemento input, que quiere decir que solo ocupa su tamaño y no una línea completo como los otros elementos.</li>
  <li>label: Se utilizan para ayudar a asociar el texto a un elemento como los input que tiene type de radio.</li>
  <li>fieldset: Se utiliza para agrupar elementos input y label relacionados dentro de un formulario web</li>
  <li>legend: Actua como una descripción dentro de los elementos fieldset y los input de radio para darle a entender a los usuario de que trata el tema.</li>
  <li>footer: Conocido como de pie de páginas, como la parte final de la página web que se desea mostrar.</li>
  <li>head: Es una de las estructuras principales que debe de tener el archivo html.</li>
  <li>title: Este elemento indica que nombre tiene la página web.</li>
  <li>!DOCTYPE html: Esta cadena especial es conocida como una declaración y se asegura de que el navegador intente cumplir las especificaciones de la industria.</li>
</ul>

<h2>Elementos con auto-cierre</h2>
<ul>
  <li>img: <strong>Auto-cierre</strong>. Elemento que se sirve para añadir imagenes en el archivo html y se cierra automaticamente. Este elementos siempre va a llevar atributos que son las que permiten direccionar la imagen donde se encuentra y colocarle un nombre a la imagen para cuando no carge y se lea por el lector del navegador.</li>
  <li>input: <strong>Auto-cierre</strong>. Permite recolectar datos desde un formulario web de diferentes formas. Puedes crear fácilmente un campo de contraseña (password), un botón de reinicio (reset) o un control para permitir a los usuarios seleccionar un archivo desde su computadora. Recodar que este elemento es inline que solo se concentra en su tamaño y solo ocupa eso en pantalla como el elemento button</li>
  <li>meta: Elemento que sirve para incluir información (metadatos) de referencia sobre la página: autor, título, fecha, palabras clave, descripción, etc.</li>
  
</ul>

<h2>Atributos de los elementos</h2>
Los atributos HTML son palabras especiales usadas dentro de la etiqueta de apertura de un elemento para controlar el comportamiento del elemento.
Los siguientes atributos mostrados en el curso son:
<ul>
  <li>src: Este atributo es la que contiene el link de donde esta ubicado cierto archivo.</li>
  <li>alt: Aquí se pone el nombre de la imagen para cuando no sea cargada.</li>
  <li>target: Aquí se usa con el ¨_blank¨ para cuando se haga click donde se encuentre ubicado este atributo, se abra otra pestaña con la imagen.</li>
  <li>action: Se puede encontrar dentro del elemento form para decir donde va a mandar los datos registrados del formulario.</li>
  <li>type: Este atributo sirve para que el usuario puede interactuar e indicar que tipo va a ser. Clasificando algunos valores que puede tener este artributo</li>
      <ul>
        <li>Texto: Indicarle que es de tipo texto que debe introducir el usuario.</li>
        <li>Contraseña: Lo que escriba el usuario se vera con "*" para ocultar el texto por seguridad.</li>
        <li>submit: Este valor permite que el type sea de datos de envio.</li>
        <li>radio: Es un valor de opciones multiples que solo se pondrá seleccionar una de ellas.</li>
        <li>checkbox: Es un valor de opciones multiples que se pondrá seleccionar uno o varias de ellas.</li>
      </ul>
  <li>name: Sirve para representar los datos que están siendo enviados. En los radio-button pueden ser seleccionados al mismo tiempo. Para solucionar se debe de dar un atributo name con el mismo valor para que solo uno sea seleccionable en los radio-button.</li>
  <li>placeholder: Nos da una idea de que tipo de información debemos escribir en un elemento input.</li>
  <li>required: Este atributo hace que sea obligatorio llenar o verificar algún input.</li>
  <li>id: Este es un atributo especifico en HTML y debe tener un valor único en toda la página.  Su propósito es identificar el elemento al vincularlo (usando un identificador de fragmento), en scripts u hojas de estilo (con CSS) que se vera cuando se use javascrit o css.</li>\
  <li>for: Este atributo se utiliza para determinar el ID del elemento de entrada al que se debe asociar el título</li>
  <li>value: Permite que al momento de enviar una información acompañado del atributo name, sea especifico que tipo de valor tiene y se suele poner el valor del mismo id que tienes.</li>
  <li>checked: Atributo que hace que este marcado automáticamente una opción en campos de opciones multiples.</li>
  <li>lang: Atributo que indica que idioma tiene la página.</li>
  <li>charset: Atributo encargada de indicar al navegador el tipo de codificación que debe utilizar para representar la información de forma correcta y que todo se vea bien. Actualmente se usa con un valor como "UTF-8" que hace que acepte todo tipo de letras, letras especiales, tildes, entre otros.</li>
  
</ul>
