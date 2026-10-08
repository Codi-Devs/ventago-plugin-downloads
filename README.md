# Descargas de plugins VentaGO

Repositorio público de distribución. Los archivos instalables se publican en GitHub Releases.

## WooCommerce

[Descargar plugin VentaGO para WooCommerce](https://github.com/Codi-Devs/ventago-plugin-downloads/releases/latest/download/ventago-woocommerce.zip)

[Versiones y notas de publicación](https://github.com/Codi-Devs/ventago-plugin-downloads/releases)

### Instalación

1. Descarga `ventago-woocommerce.zip`.
2. En WordPress abre Plugins → Añadir nuevo → Subir plugin.
3. Selecciona el ZIP y actívalo con WooCommerce instalado.
4. En los ajustes de VentaGO pega la clave API creada para tu negocio y conecta la tienda.

La descarga es pública. Para utilizar la integración necesitas una clave API válida y el acceso correspondiente en VentaGO.

Cada versión incluye un archivo SHA256 para comprobar la integridad del ZIP.

### Publicar una actualización

Construir el paquete desde el checkout privado del plugin, revisar versión/contenido y publicar una release estable con el archivo `ventago-woocommerce.zip` y su checksum. Mantener ese nombre para conservar el enlace de descarga. Nunca incluir los ZIP en los assets del frontend.
