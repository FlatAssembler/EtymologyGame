# EtymologyGame
A web-game about historical linguistics.

This is a web-game that simulates phonological developments of two related imaginary languages and makes tasks based on that. It can be seen live on my [website](http://flatassembler.github.io/etymologist.html). I have also written [a paper in Croatian about the algorithm used in it](https://flatassembler.github.io/Fonoloska_evolucija_jezika.docx).

`etymologist.html` uses JQuery, advanced CSS and basic SVG to create a graphic interface, but it, of course, doesn't work in all browsers.

`etymology.html` creates a text-based interface, and it works in browsers which don't support advanced web-technologies, such as Internet Explorer 6 and NetSurf.

`etymology_dataset.json` is a JSON file containing real-world data about the names of numbers in various languages, taken from [Wikipedia](https://en.wikipedia.org/wiki/List_of_numbers_in_various_languages).

`etymology_game_validator.js` is a JavaScript program, runnable, for example, in NodeJS or ChakraCore or QuickJS, which validates the algorithm used in `etymology.html` and `etymologist.html` and outputs the results as HTML, and `validation_results.html` is its example output.

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
