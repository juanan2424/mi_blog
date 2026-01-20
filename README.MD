# Práctica: Uso de Git y GitHub para un sitio web estático

## Fase 1: Preparación local y primer commit

Se crea la carpeta de trabajo del proyecto (`mi_blog`) y dentro de ella los archivos básicos del sitio web: `index.html`, `style.css` y `script.js`.  
A continuación, se inicializa un repositorio Git local, lo que genera la carpeta oculta `.git`, donde Git almacena el historial de versiones y la información necesaria para el seguimiento de cambios.

Antes de realizar commits, se configura la identidad del usuario (nombre y correo electrónico), que quedará asociada a cada cambio registrado.  
Una vez preparados los archivos, se añaden al área de *staging* y se realiza el primer commit, que guarda la plantilla inicial del sitio como punto de partida del proyecto.

## Fase 2: Creación del repositorio remoto y primer push

Tras completar la fase local, se crea un repositorio remoto en GitHub con el mismo nombre del proyecto. Este repositorio permitirá almacenar el código en la nube y mantener una copia sincronizada del trabajo.

El repositorio local se vincula con el remoto mediante una URL (HTTPS o SSH) utilizando el nombre `origin`. Una vez realizada la asociación, se lleva a cabo una pequeña modificación en los archivos del proyecto y se registra un segundo commit.  
Finalmente, se ejecuta el primer `git push`, que sube los commits al repositorio remoto y establece la rama `main` como referencia principal.

## Fase 3: Personalización y control de versiones

En esta fase se realizan cambios visibles en el sitio web, como la modificación de textos en el archivo HTML, el ajuste de colores y estilos en el CSS y la personalización del comportamiento del JavaScript.  
Cada grupo de cambios relacionados se guarda en un commit independiente, lo que facilita el seguimiento de la evolución del proyecto y permite identificar claramente cada modificación en el historial.

Este enfoque fomenta buenas prácticas en el uso de Git, ya que los commits son pequeños, claros y fáciles de entender.

## Fase 4: Publicación con GitHub Pages

Por último, se activa GitHub Pages desde la configuración del repositorio remoto, seleccionando la rama `main` como fuente de publicación.  
Tras unos minutos, GitHub genera una URL pública desde la que se puede acceder al sitio web. De este modo, el proyecto queda publicado en Internet y accesible desde cualquier navegador.