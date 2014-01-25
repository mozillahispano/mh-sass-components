mh-sass-components
==================

Estilos de componentes compartidos para la web de Mozilla Hispano.

Este repositorio está hecho para ser utilizado como submódulo de Git en un directorio dentro del repositorio del sitio web.

Para añadirlo al proyecto ejecuta:

```
  git submodule add git://github.com/mozillahispano/mh-sass-components.git <directorio-de-css>/base
```

Después, para utilizarlo como base para los estilos del sitio:

```sass
  @import "base/all";
```
