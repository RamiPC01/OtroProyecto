# Este es mi archivo README inicial
## Propósito de los archivos README

Los archivos README son los encargados de contener toda la información que el autor o autores del proyecto de software que consideren necesarias. Generalmente contienen los objetivos del proyecto, instrucciones de instalación del software, su uso, propósitos etc... Aporta información además sobre los requisitos del sistema, la estructura o simplemente documentación adicional para los desarrolladores interesados en trabajar con el proyecto o simplemente colaborar con él. En conclusión, esta clase de archivos es de gran importancia para dar información relevante a las personas ajenas al proyecto que quieran saber sobre él. En este caso nuestro archivo README será un recopilatorio de ejemplo de la Sintaxis Básica y Avanzada de GIT, para aprender y familiarizarnos con esta clase de sintaxis de los archivos de tipo .md.

-------------------

### Índice del README

1. [Sintaxis Básica](#sintaxis-básica)
   
  - [Encabezados](#encabezados)

  - [Estilos de Textos](#estilos-de-textos)

  - [Citado de Texto](#citado-de-texto)
  
  - [Código de Cita](#código-de-cita)
  
  - [Modelos de Color](#modelos-de-color)
  
  - [Vínculos](#vínculos)
     - [Vínculos Relativos](#vínculos-relativos)    
  
  - [Enlaces de Sección](#enlaces-de-sección)
  
  - [Imágenes](#imágenes)
    - [Imágenes con etiquetas HTML](#imágenes-con-etiquetas-html) 

  - [Listas](#listas)
    - [Listas anidadas](#listas-anidadas)
      
  - [Listas de tareas](#listas-de-tareas)
  
  - [Mencionar personas y equipos](#mencionar-personas-y-equipos)
  
  - [Hacer referencia a propuestas y pull requests](#hacer-referencia-a-propuestas-y-pull-requests)
  
  - [Hacer referencia a recursos externos](#hacer-referencia-a-recursos-externos)
  
  - [Cargar activos](#cargar-activos)
  
  - [Usar emojis](#usar-emojis)
  
  - [Párrafos](#párrafos)
  
  - [Notas al Pie de Página](#notas-al-pié-de-página)
  
  - [Alertas](#alertas)
  
  - [Ocultar el contenido con comentarios](#ocultar-el-contenido-con-comentarios)
  
  - [Ignorar formato de Markdown](#ignorar-formato-de-markdown)
  
  - [Inhabilitar la representación del lenguaje de marcado](#inhabilitar-la-representación-del-lenguaje-de-marcado)

-------------------

# Sintaxis Básica

## Encabezados

Para poner encabezados en los archivos README hay que poner el carácter #, entre 1 y 6 de ellos, dependiendo del número que pongamos se harán encabezados de los diferentes niveles.

# Encabezado de primer nivel
## Encabezado de segundo nivel
### Encabezado de tercer nivel
#### Encabezado de cuarto nivel

## Estilos de Textos

#### Estilo Negrita
El estilo bold usa esta sinxasis ** ** o __ __ pero tambien tiene métodos abreviados de teclado como pueden ser `Command + B en MAC y Ctrl + B para Windows y Linux`.

**Este texto está en negrita con `**`** 

__Este también pero con `__`__.

#### Estilo Cursiva
El estilo cursiva usa esta sinxasis * * o _ _ , y tambien tiene métodos abreviados de teclado como pueden ser `Command + I en MAC y Ctrl + I para Windows y Linux`, *este texto está en cursiva* y _este también pero con otra sintaxis_.

#### Estilo Tachado
El estilo tachado usa esta sinxasis ~~ ~~ , y no tiene métodos abreviados de teclado, ~~este texto está tachado~~.

#### Estilo Cursiva en negrita y anidada
El estilo cursiva en negrita y anidada usa esta sinxasis ** ** y _ _ , y no tiene métodos abreviados de teclado, **este texto está en _cursiva y negrita anidada_**.

#### Estilo Todo en negrita y cursiva
El estilo todo en negrita y cursiva usa esta sinxasis *** *** , y no tiene métodos abreviados de teclado, ***este texto está en todo negrita y cursiva***.

#### Estilo Subscript
El estilo todo Subscript y cursiva usa esta sinxasis <sub> </sub> , y no tiene métodos abreviados de teclado, Este tipo de estilo se utiliza para poner <sub>subíndices</sub>.

#### Estilo Superscript
El estilo todo Superscript usa esta sinxasis <sup> </sup> , y no tiene métodos abreviados de teclado, Este tipo de estilo se utiliza para poner <sup>superíndices</sup>.

## Código de cita
Para hacer citas en los textos hay dos maneras diferentes , una de ellas es utilizando las comillas simples como vimos anteriormente, `Texto de Ejemplo`. O bien poniendo comillas triples ``` para poner párrafos enteros citados. Por ejemplo:

Algunos comandos básicos de git son:
```
git status
git add
git commit
```

## Citado de texto
Para citar texto utilizamos el símbolo `>`

> Esto es una cita de texto

## Modelos de color

Podemos resaltar partes de texto según nuestras necesidades gracias a las diferentes maneras que nos ofrece git baseándose en la sintaxis de los archivos .md.

Por ejemplo, el formato de color puede ser en hexadecimal:  `#ffffff`, en formato RGB:  `rgb(R,G,B)` o en formato HSL:  `hsl(H,S,L)`. Cabe destacar que la previsualización de los colores solo se verán en issues, pull requests o en debates, por lo que en este documento no estará disponible ya que no es ninguno de esos tipos.

## Vínculos

La sintaxis para crear vínculos en las partes del texto que nos interesa es escribiendo el texto entre corchetes `[]` y la URL a la página a la que queremos vincular entre paréntesis `()`.

Podemos hacer un vínculo así:  [Página de mi Perfil de GitHub]([https://pages.github.com/](https://github.com/RamiPC01/)).

### Vínculos Relativos
O también podemos hacer vínculos relativos a otros documentos de nuestro repositorio especificando esta vez en el espacio de la URL la ruta relativa a nuestro directorio o archivo, en este caso es a `lib/estilos.css`.

Por ejemplo:  [Enlace relativo a estilos.css](lib/estilos.css)

## Enlaces de Sección

Se pueden observar mismamente en los encabezados de este archivo, ya que si pasamos el ratón por encima de ellos podemos ver que aparece un icono tipico de un enlace que podemos interactuar con él.

## Imágenes

Se pueden mostrar imágenes en el archivo utilizando el símbolo `!` seguido de la descriptción de esta entre corchetes `[]`, y por último el enlace a la imágen entre paréntesis `()`.

![Descripción de la imagen de prueba del Octocat de github](https://myoctocat.com/assets/images/base-octocat.svg)

### Imágenes con etiquetas HTML

Otra forma de poner lás imágenes es con la etiqueta `<picture></picture>`. En ella podemos especificar una imágen dependiendo del tema que tengamos especificado en Git, tanto el claro como el oscuro. Una descripción para la imágen y en el apartado de `src` pegamos el enlace a las imágenes que queremos que aparezcan.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

## Listas
Podemos crear listas tanto ordenadas como desordenadas dependiendo de los caracteres que utilicemos, por ejemplo con `-, * o +` antes del texto, haremos listas desordenadas.

- DAM  (Hecho con `-`)
* LMSXI  (Hecho con `*`)
+ BD  (Hecho con `+`)
- CD  (Hecho con `-`)
* SI  (Hecho con `*`)
+ PRO  (Hecho con `+`)

Para crear listas ordenadas debemos poner delante de cada elemento un número y un punto `1.` y así sucesivamente.

1. DAM
2. LMSXI
3. BD
4. CD
5. SI
6. PRO

### Listas anidadas
Se puede crear una lista anidada al dejar sangría en uno o más elementos de la lista debajo de otro elemento.
Escribe los caracteres con espacio frente al elemento de la lista anidada hasta que el carácter del marcador de lista `(- o *)` se encuentre directamente debajo del primer carácter del texto en el elemento que se encuentra debajo.

1. DAM (Desarrollo de Aplicaciones Multiplataforma)
  - Asignaturas en el módulo.
    - Programación, Bases de Datos, Contornos de Desarrollo, Lenguaje de Marcas, Sistemas Informáticos.

## Listas de tareas
Para crear una lista de tareas, hay que añadir como prefijo un guion `-` y espacio , seguido de corchetes  `[ ]`. Para marcar cualquiera de los elementos de la lista una vez estea hecho, debemos marcarlo con una `x` entre los corchetes de la lista.

- [x] Acabar trabajo de GutHub de Contornos de Desarrollo
- [ ] Estudiar Programación
- [ ] Estudiar Sistemas Informáticos

## Mencionar Personas y equipos

Para mencionar a unha persoa o equipo utilizamos el caracter `@` al lado del nombre de usuario de la persona o del equipo al que queremos mencionar. Una vez hecho se enviará una notificación a la persona o equipo correspondiente

@Ramallo98 Hola buenas, ¿qué tal estás?

> Solo se notificará al usuario si tiene permiso de lectura en el repositorio o pertenece al equipo adecuado.

## Hacer referencia a propuestas y pull requests.

Para hacer referencias a propuestas y pull requests debemos escribir `#` y a continuación el número o título de la propuesta o bien del pull reequest que queremos hacer referencia.

## Hacer referencia a recursos externos

Configurando as referencias autovinculadas para un repositorio, as referencias a recursos externos de ferramentas integradas no GitHub como JIRA(realiza informes de problemas) ou Zendesk, convírtense en vínculos acortados.

Por exemplo:

Prefijo de referencia: `JIRA-`

URL de destino: `https://jira.example.com/issue?query=<num>`

Versión preliminar: `JIRA-123` se convierte en `https://jira.example.com/issue?query=123`

## Cargar activos

Se pueden adjuntar archivos en nuestros documentos de Git tanto arrastrando desde el explorador de archivos hasta el documento el la web, como copiando y pegando este mismo. Se puede realizar en incidencias, solicitudes de incorporacion de cambios, comentarios y arquivos `.md` en el repositorio.

## Usar emojis

Podemos utilizar emojis `:EMOJICODE:`, entre `:`, algunos ejemplos son:

- Emoji de Rana `:frog:`: :frog:
- Emoji de Gusano `:bug:`: :bug:
- Emoji de Escarabajo `:beetle:`: :beetle:
- Emoji Pulgar hacia Arriba `:thumbsup:`: :thumbsup:
- Emoji Pulgar hacia Abajo `:thumbdown:`: :thumbdown:

## Párrafos

Para crear diferentes párrafos a lo largo de nuestro archivo, como llevamos haciendo desde el principio de este, simplemente se deja un espacio entre líneas para crear los diferentes párrafos. Ejemplos:

Párrafo 1:  "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

Párrafo 2:  "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

Párrafo 3:  "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."

## Notas al Pié de Página

Podemos añadir notas al pié de página añadiendo el carácter `^` y un número entre corchetes `[]` al final de la linea que queremos referencia. Esta se verá al final de la página, y además podemos añadir información a esta nota a través del carácter de los dos puntos `:`, seguido de la información que queramos poner.

Con esto referenciamos a la nota al pié de página [^1].

La nota de pié de página la escribimos aquí aunque después se vea al final del documento. Ejemplo de lo escrito:  `[^1]:Ejemplo de nota a pié de página`.
[^1]:Ejemplo de nota a pié de página.

## Alertas

As alertas se basean en la sintaxis ya creada de blockquote y principalmente se utilizan para destacar información o hacer más visible partes importantes o críticas del pryecto. Dependiendo del tipo de alerta y de la importancia de estas se mostrará un color o otro. Dependiendo del tipo de alerta que queramos poner de blockquote irá despues del caracter `>`, entre corchetes `[]`, y el nombre de la alerta.

> [!NOTE]
> Nota para destacar información para los usuarios. Se mostrará de color azul.

> [!TIP]
> Comentarios o consejos para ayudar a realizar alguna acción del proyecto. Se mostrará de color verde.

> [!IMPORTANT]
> Alerta de información importante para los usuarios. Se mostrará de color morado.

> [!WARNING]
> Alerta de aviso urgente para los usuarios. Se mostrará de color naranja.

> [!CAUTION]
> Alerta de peligro para informar sobre peligros o efectos secundarios después de realizar alguna acción. Se mostrará de color rojo.


## Ocultar el contenido con comentarios

Para hacer comentarios ocultos en nuestros documentos utilizamos la sintaxis de HTML para hacer comentarios, como esta:  `<!-- Comentario -->`.

<!-- Lo que pongamos aquí dentro no estará visible en nuestro archivo -->


## Ignorar formato de Markdown

Para ignorar el formato de Markdown, debemos poner el caracter `\` antes de la linea de texto que queremos ignorar. Además también podemos hacerlo utilizando la etiqueta de HTML `<span>`.

__Este texto está en negrita y cursiva__

\__Este texto no está en negrita ni en cursiva ya que ponemos las barras `\` al principio y al final de la línea\__

<span>__Este texto no está en negrita ya que ponemos las etiquetas de `<span>`__</span>

## Inhabilitar la representación del lenguaje de marcado

Cuando realizamos la previsualización de documentos este tipo de lenguaje está activado por defecto,sin embargo si hacemos click en el botón Code al lado del botón de Preview, podemos mirar el código fuente de la página sin el lenguaje de marcado.

-------------------





