This website is templated in [Pug](https://pugjs.org/api/getting-started.html).

To compile to HTML, install [Pug's CLI](https://github.com/pugjs/pug-cli), and run `pug -w src/pages -o ./dist -P `

To push ./dist subtree for deployment: 
`git subtree push --prefix dist origin gh-pages`