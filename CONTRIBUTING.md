# ¿Cómo ayudar en el desarrollo de los componentes SASS de Mozilla Hispano?

## Conocimientos requeridos

Los componentes básicos de estilo para desarrollo web en Mozilla Hispano están
desarrollados usando [SASS](http://sass-lang.com/). Si no has trabajado con
SASS antes, la primera lectura recomendada es la [Guía de
SASS](http://sass-lang.com/guide).

Además, si no estás familiarizado con el desarrollo web dentro del proyecto, te
invitamos a leer la [Guía para Desarrolladores de Mozilla
Hispano](http://mhdev.rtfd.org/).

## Obteniendo el código

Para comenzar a trabajar con el código fuente del proyecto, es necesario crear
un `fork` del repositorio git del mismo. Puedes usar el [Enlace de
Fork](https://github.com/mozillahispano/mh-sass-components/fork) si aún no lo
has hecho.

Luego, haz un clon local de tu repositorio:

```sh
$ git clone https://github.com/<tu usuario>/mh-sass-components.git
```

## Adoptando un componente

Elige el componente en el que deseas trabajar. Cada componente es un archivo
`_*.scss` en la raíz del proyecto, como `_forms.scss` o `_core.scss`.

Una vez sepas en qué componente deseas trabajar, revisa la [Lista de
Issues](https://github.com/mozillahispano/mh-sass-components/issues) del
proyecto y verifica si ya existe un *issue* para ese componente. Si existe,
ponte en contacto con el responsable del ticket para ver cómo puedes
ayudarlo. Si no existe, crea un nuevo ticket expresando claramente que vas a
trabajar en ese componente y asígnatelo.

## Trabajando en el componente

**Antes de comenzar a trabajar**, crea una nueva rama para el componente que
vas a desarrollar o mejorar.

```sh
$ git checkout -b <nombre del componente>
```

### Guías a seguir para el desarrollo

* [Guía de estilo de Mozilla para sitios
  Web](https://www.mozilla.org/en-US/styleguide/websites/sandstone/)
* [Implementación de Sandstone en
  LESS](https://github.com/ossreleasefeed/Sandstone/tree/master/css/sandstone)
* [Tema de Mozilla para
  DeckJS](https://github.com/groovecoder/deckjs-theme-mozilla)
* [Desarrollo de Sandstone en SASS de
  MozFR](https://github.com/mozfr/www/pull/29)

### Enviando el progreso al repositorio

Cada vez que progreses en el desarrollo del componente, haz commit y push a tu
repositorio y luego crea un `Pull Request` al repositorio de Mozilla
Hispano. Hazle ping a los desarrolladores del proyecto para que revisen los
avances y discutan contigo cualquier observación. Una vez aprobados los
cambios, tu progreso será mezclado con la rama `master` del proyecto.
