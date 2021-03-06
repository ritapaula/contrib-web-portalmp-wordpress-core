# contrib-web-portalmp-wordpress-core

El software alojado en proyectos "contrib" se ofrece tal cual, sin garantía de ningún tipo, expresa o implícita. La Universidad de Vigo no hace responsable de su uso ni de los daños u otras responsabilidades derivadas del mismo.

En particular, la Universidad de Vigo: No se compromete a atender peticiones de actualización del software. No dará ningún tipo de soporte ni formación relativa al mismo.

La utilización del software implica la aceptación de las condiciones de uso.

# Description

WordPress plugin with basic and common elements for Universidade de Vigo.

# Installation

This section describes how to install the plugin and get it working.

1. Upload the plugin files to the `/wp-content/plugins/wpcoreuvigo` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress

# Development

This plugin uses Webpack to prepare and compile frontend resources (CSS, Javascript, images, fonts, etc.)

The steps to compile are:

1. Install dependencies with yarn: `yarn`
2. To compile and build:
`yarn build`
`yarn build:production`
`yarn build:admin`
`yarn build:admin:production`

3. To develop with browsersync:
`yarn start`
`yarn start:admin`

# How to deploy

To deploy this plugin you can use a script based in node that copy and compress all necessary files and folders. Then you can use that zip to distribute and install in WordPress.

Execute: `yarn deploy`

This command, compilem, build and zip files and folders.

# Changelog

Please refer to CHANGELOG.md
