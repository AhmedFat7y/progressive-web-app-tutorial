# Progressive Web App Tutorial

Simple workflow using grunt to build HTML pages with HTML and Sass. The workflow also features a lot of optimizations like building SVG-sprites, properly injecting dependencies into Sass and Jade files, files and directory structure that would speed up development and a lot more.

More information and details about the configurations will be posted shortly.

## Requirements

* NodeJS
* NPM
* Grunt
* Sass
* Bower

## Installing the requirements

- NodeJS and NPM, check nodejs website.
- Grunt -> after installing nodejs, install `grunt-cli` using `npm install -g grunt-cli`.
- Bower -> after installing nodejs, install `bower` using `npm install -g bower`.

## Steps

- Install the node packages using `npm install`.
  - Use `sudo npm install` if faced with any permission error.
- Install the front-end packages using `bower install`.
  - If you face any permission error reading `/Users/Andreas/.config/configstore/` change the ownership of that folder to your user. Check this link for more info [Getting a permission error when installing with bower](http://stackoverflow.com/questions/29865913/getting-a-permission-error-when-installing-with-bower "Stackoverflow Question").


## Serving the HTML and creating a build

- Run `grunt serve` to see the live HTML.
- Run `grunt` to create a build. A build is created in the directory called `dist`.

## Acknowledgement
This workflow is taken from [Simple Html Project Grunt Workflow](https://github.com/ahmadalfy/simple-html-project "Github Repository").
[Ahmad Alfy](https://github.com/ahmadalfy "Alfy's Github Profile") is my mentor, the one who taught me to write semantic web pages and optimize my work flow.
