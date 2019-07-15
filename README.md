# Ejemplo de aplicación desarrollada en AngularJs


## Descripción

Esta aplicación de ejemplo está desarrollada con la finalidad de presentar mis habilidades en JavaScript
y AngularJs. Sientete libre de descargar el código, revisarlo y comentarlo.

## Prerequisitos

### Git

- Descargar e instalar git [aquí][git-home].

### Node.js

- Descargar e instalar [Node.js][node].
- Instalar las dependencias de la aplicación: `npm install`


## Acerca de la aplicación

- La versión de AngularJs utilizada es la 1.7.x
- Se implementa [http-server][http-server] como servidor web de la aplicación.
- No existe un servidor de contenidos para la aplicación, en su lugar se utiliza archivos JSON para ese proposito.
- La interfaz de la aplicación utliza bootstrap 4.


### Ejecutar la aplicación

- Ejecutar `npm start`.
- En el navegador web escribir la dirección [http://localhost:3300/](http://localhost:3300/).


**Notas:**

*


## Descripción del sistema de archivos de la aplicación

```
client/                  --> directorio raiz de la aplicación
  assets/                --> directorio para las dependencias de la aplicación de AgunlarJs
    css/                 --> directorio para las hojas de estilo en cascada
    img/                 --> directorio para las imagenes
    js/                  --> directorio para los archivos JavaScript
    lib/...              --> directorio para angular, bootstrap y sus dependencias
    sfx/                 --> directorio para los archivos de audio
  views/                 --> directorio para los `layout`s adicionales
    index.html           --> `layout` de la aplicación
node_modules/...         --> 3rd party libraries and development tools (fetched using `npm`)
package.json             --> Node.js specific metadata, including development tools dependencies
package-lock.json        --> Npm specific metadata, including versions of installed development tools dependencies
```

## Contacto

Para más información sobre el desarrollo de la aplicación pueden escribirme a sotelo.enrique@gmail.com


[node]: https://nodejs.org/
[git-home]: https://git-scm.com/
[http-server]: https://www.npmjs.com/package/http-server