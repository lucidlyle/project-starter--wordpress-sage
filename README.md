# project-starter--wordpress-sage
This is a repo housing a simple project start for Wordpress using Sage projects

https://github.com/roots/bedrock

composer create-project roots/bedrock your-project-folder-name

- make sure you are on the latest version of WP

composer require --update-with-dependencies johnpbloch/wordpress:~4.9.8

- Update environment variables in .env file

Generate Salts: https://roots.io/salts.html


/* INSTALL THE SAGE THEME */ https://github.com/roots/sage

- cd to web/app/themes

- use dev-master to get the latest version with Blade Templates

composer create-project roots/sage your-theme-name dev-master

- cd into theme folder

- Run yarn to install dependencies

yarn

Build commands
yarn start — Compile assets when file changes are made, start Browsersync session
yarn build — Compile and optimize the files in your assets directory
yarn build:production — Compile assets for production