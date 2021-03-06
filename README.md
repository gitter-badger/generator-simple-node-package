# generator-simple-node-package
> start a simple node module project, including CLI

Heavily inspired by how [Sindre Sorhus](https://github.com/sindresorhus) structures his small Node.js modules.

## Install

```sh
$ npm install --global generator-simple-node-package
```


## Usage

```sh
$ yo simple-node-package
[?] What is the name of your module? hello world
[?] Please provide a short description for the project: say hello to the world!
[?] Will this module include a CLI? Yes
[?] Please provide your personal website: http://hello.world
   create index.js
   create test.js
   create cli.js
   create readme.md
   create license
   create package.json
   create .editorconfig
   create .gitignore
   create .jshintrc
   create .travis.yml


I'm all done. Running npm install for you to install the required dependencies. If this fails, try running the command yourself.
```

## todo
- tests
- create GitHub repo
- init [TravisCI](https://travis-ci.org/) for project
- init [Gemnasium](https://gemnasium.com/dashboard) for project

## License

MIT © [Matias Singers](http://mts.io)
