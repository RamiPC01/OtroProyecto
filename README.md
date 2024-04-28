# Este es mi archivo README inicial
## Propósito de los archivos README

Los archivos README son los encargados de contener toda la información que el autor o autores del proyecto de software que consideren necesarias. Generalmente contienen los objetivos del proyecto, instrucciones de instalación del software, su uso, propósitos etc... Aporta información además sobre los requisitos del sistema, la estructura o simplemente documentación adicional para los desarrolladores interesados en trabajar con el proyecto o simplemente colaborar con él. En conclusión, esta clase de archivos es de gran importancia para dar información relevante a las personas ajenas al proyecto que quieran saber sobre él. En este caso nuestro archivo README será un recopilatorio de ejemplo de la Sintaxis Básica y Avanzada de GIT, para aprender y familiarizarnos con esta clase de sintaxis de los archivos de tipo .md.

### Índice del README

1. [Sintaxis Básica](#sintaxis-básica)
   
  - [Encabezados](#encabezados)

  - [Estilo de texto](#estilo-de-texto)

  - [Citado de texto](#citado-de-texto)
  
  - [Código de cita](#código-de-cita)
  
  - [Modelos de color compatibles](#modelos-de-color-compatibles)
  
  - [Vínculos](#vínculos)
  
  - [Enlaces de sección](#enlaces-de-sección)
  
  - [Vínculos relativos](#vínculos-relativos)
  
  - [Imágenes](#imágenes)
    -[Especificar un tema en el que se muestra una imágen](#especificar-un-tema-en-el-que-se-muestra-una-imágen) 

  - [Listas](#listas)
    - [Listas anidadas](listas-anidadas)
      
  - [Listas de tareas](listas-de-tareas)
  
  - [Mencionar personas y equipos](#mencionar-personas-y-equipos)
  
  - [Hacer referencia a propuestas y solicitudes de extracción](#hacer-referencia-a-propuestas-y-solicitudes-de-extracción)
  
  - [Hacer referencia a recursos externos](#hacer-referencia-a-recursos-externos)
  
  - [Cargar activos](#cargar-activos)
  
  - [Usar emojis](#usar-emojis)
  
  - [Párrafos](#párrafos)
  
  - [Notas al pie](#notas-al-pie)
  
  - [Alertas](#alertas)
  
  - [Ocultar el contenido con comentarios](#ocultar-el-contenido-con-comentarios)
  
  - [Ignorar formato de Markdown](#ignorar-formato-de-markdown)
  
  - [Inhabilitar la representación del lenguaje de marcado](#inhabilitar-la-representación-del-lenguaje-de-marcado)



# Sintaxis Básica

## Encabezados

Para poner encabezados en los archivos README hay que poner entre 1 y 6 #, dependiendo del número que pongamos se harán encabezados de los diferentes niveles.

# Encabezado 1
## Encabezado 2
### Encabezado 3
#### Encabezado 4




**Este texto está en negrita**

__Este también__

*Este texto está en cursiva* y _Este también_

~~Este texto está tachado~~

Algunos comandos básicos de git son:
```
git status
git add
git commit
```

Este es un texto con subíndice <sub>Subsíndice</sub>

Este es un texto con superíndice <sup>Superíndice</sup>

**Este texto está en negrita, _y esto en cursiva,_ a la vez**

***Todo este texto está en negrita y en cursiva***

> Esto es una cita

El formato de color puede ser `#ffffff`, `rgb(R,G,B)`o `hsl(H,S,L)`

Podemos hacer un vínculo así [GitHub Pages](https://pages.github.com/).

[Este es un enlace relativo a otro archivo de nuestro repositorio](lib/estilos.css)

![Imagen Octocat](https://myoctocat.com/assets/images/base-octocat.svg)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>






