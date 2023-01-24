Terminal commands

Install:
npm i

Run developer mode (with server)
npm run dev

Run build project (without server)
npm run build

Run build project and loading to server for FTP. (without server)
ftp.js - configuration file
npm run deploy

Run build project and create project name zip file. (without server)
npm run zip

Run build project without create webp images. (without server)
npm run devbuild

Run create SVG sprite, icons need move to src/spriteicons,
destination folder dist/img/icons/icons.svg
(manual start if need)
npm run sprite

//------------------------------------------------------------------------------

Main files:
js/app.js
scss/style.scss

index.html - Main page
файлы html/*.htm - connected parts in Main HTML

//------------------------------------------------------------------------------

Use pseudonims:
@img = src/img
@scss = src/scss
@js = src/js

Plagin for VS Code - Path Autocomplete
Settings JSON:
"path-autocomplete.pathMappings": {
	"@img": "${folder}/src/img", // pseudonim for folder img
	"@scss": "${folder}/src/scss", // pseudonim for folder scss
	"@js": "${folder}/src/js", // pseudonim for folder js
}