# gacetilla-facttic
Gacetilla de presentación de la Federación de coopertivas de trabajo de tecnología, innovación y conocimiento


### Contenido

En `source` está cada página de la gacetilla en svg, realizado con Inkscape.

En `pdf` se encuentran las mismas páginas guardadas en formato pdf.

En la raiz se encuentra `gacetilla-facctic.pdf` y `resumen-facttic.pdf`. El primero contiene las 12 páginas unidas. El segundo es un resumen en una sola página.

### Edición

Para realizar cambios en el documento, se debe hacer sobre los archivos svg de la carpeta source y gurdar una copia en formato pdf en la carpeta correspondiente.

Para volver a generar el documento combinado, desde consola posicionados en la raiz del repositorio, se debe ejecutar el siguiente comando:

    pdfunite pdf/pagina_* gacetilla-facttic.pdf

**`pdfunite` es parte del paquete poppler-utils**

Instalación con apt-get:

    sudo apt-get update && sudo apt-get install poppler-utils
