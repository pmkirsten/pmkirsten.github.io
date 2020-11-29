---
title: "Xwiki Tree Macro Builder"
layout: single
permalink: /xwiki_tree_macro_builder/
author_profile: true
header:
  teaser: https://i.imgur.com/U73GBzq.png
---
Este programa permite simplificar la creación de un árbol de directorios en XWiki usando el plugin de [Tree Macro](https://extensions.xwiki.org/xwiki/bin/view/Extension/Tree%20Macro)

## Requisitos previos
Java 1.8 o superior instalado
## Descarga
Solo tienes que descargar la última versión estable del programa en la zona de *Releases* de Github o bien escogiendo la última versión en el [este enlace](https://github.com/pmkirsten/xwiki-tree-macro-builder/releases/latest). 
Descargamos el archivo con extensión **\*.jar** y lo ejecutamos. No es necesario instalar.

## Uso
Únicamente es necesario pulsar sobre el botón **Selecciona carpeta...** para que nos abra una venta que nos permita seleccionar la carpeta a analizar.

![Imagen1](https://i.imgur.com/eTU9Lin.png)
![Imagen2](https://i.imgur.com/lNPr7s0.png)
![Imagen3](https://i.imgur.com/U73GBzq.png)

## Estructura
El código generado es la de una tabla de una fila y dos columnas según la [sintaxis de XWiki 2.1](https://www.xwiki.org/xwiki/bin/view/Documentation/UserGuide/Features/XWikiSyntax/), en cuya columna izquierda se encuentra el árbol con la estructura de carpetas y ficheros que hemos analizado. 

## Notas
Incluye una etiqueta al principio ***{%raw%}{{wrapper}}{%endraw%}*** y otra al final ***{%raw%}{{/wrapper}}{%endraw%}*** que es no es estándar de la [sintaxis de XWiki 2.1](https://www.xwiki.org/xwiki/bin/view/Documentation/UserGuide/Features/XWikiSyntax/), si no que es una macro propia. Es necesario eliminar dichas etiquetas para que siga los estándares de la sintaxis