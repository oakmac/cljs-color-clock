# Color Clock in ClojureScript

Writing the color clock assignment in ClojureScript.

## Development Setup

Install [Leiningen] and [Node.js]

```sh
# install node_modules (one-time)
npm install

# you may wish the run the following commands in separate console tabs / windows

# build CLJS files
lein clean && lein cljsbuild auto

# compile LESS into CSS
grunt watch

# run a local web server out of public/ on port 9955
node server.js 9955

# produce a build in the 00-publish/ folder
grunt build
```

## License

[ISC License]

[Leiningen]:http://leiningen.org
[Node.js]:http://nodejs.org
[ISC License]:LICENSE.md
