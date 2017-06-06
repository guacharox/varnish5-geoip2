Imagen Varnish 5.1.2 (Incluye Módulo libvmod-geoip2).

Esta imagen de contenedor docker está basada en un SO. Debian Jessie-Slim
la cual registra el repositorio PackageCloud.io para la descarga del paquete 
oficial varnish en su última versión.

Esta imagen instala automaticamente las dependencias para compilar los módulos
libvmod-geoip2 y libmaxminddb  en su última versión.
https://github.com/fgsch/libvmod-geoip2
https://github.com/maxmind/libmaxminddb

Dependencias.
- make
- gcc
- libtool
- pkg-config
- python-docutils
- autoconf
- automake

Referencia.

http://varnish-cache.org/docs/5.1/installation/index.html
