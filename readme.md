
# Landing-page
Este es un ejemplo tomado del [video base](https://www.youtube.com/watch?v=7zdFJulzXb4&list=PLnunbwZjHqMO-JII_HBf5TAzdzaBJP34w&index=15) donde se diseña el frontend de una [landing page](https://my-irobot.netlify.app) usando Boostrap. 
***


## Tecnologías usadas
- node (para inatalar bootstrap)
- Live Sass Compiler (para compilar el archivo sass, este es una extensión de VSC)
- Boostrap (estilos)
- purgeCss  (reducir el tamaño del archivo css de boostrap)
- Netlify.app (lugar donde se despliega)


## Descripción del proyecto
Este es un sencillo proyecto frontend donde se diseña una pequeña web, para ello se usa Bootstrap, es un proyecto importante pues se hace uso del concepto de filas y columnas de bootstrap.

En este proyecto se usa Bootstrap instalado, lo que permite que se puedan persolalizar los estilos via el archivo `styles.scss`

Se usa live Sass Compiler, lo cual lo que hace es tomar todo el código de Bootstrap y crear con ello un archivo `*.css` con absolutamente todo el código de Bootstrap.

Se usa `purgecss` de manera opcional para reducir el tamaño del archivo css que genera boostrap con solo los elementos usados realmente en la web, para su comprensión se sugiere se revise en el archivo [package.json](./package.json) el script personaliazdo `purge`

En la carpeta dist, esta guardada a mano aquello elementos que se suben a [Netlify](http://www.netlify.app)
***

## Para proximas versiones
Principalmente terminar de escribir el contenido real de la web

### Maolink software
Version. 1.0.0

Julio 2022




