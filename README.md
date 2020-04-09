# alberick-vue

[alberick.nl](https://alberick.nl)

This is a two-part project. This is a client side. It builds into a VueJS SPA Wordpress theme but can be hosted standalone if you do not run `afterbuild` command.

## Vue cli

This project is created using Vue Cli (https://cli.vuejs.org)

### Install Vue cli
```
npm install -g @vue/cli
# OR
yarn global add @vue/cli
```

## Project setup
```
npm install
```

Use `vue ui` to run the project and perform other tasks. Alternatively, use npm for that

### Compiles and hot-reloads for development
```
npm run serve
```


### Compiles and minifies for production

#### For hosting standalone
```
npm run build
```
Leaves some PHP code inside `<noscript>` of index.html. This is needed for basic prerender functionality. Can be safely removed when hosting standalone.

#### As a Wordpress theme
Renames index.html to index.php
```
npm run build && npm run afterbuild
```

### Lints and fixes files
```
npm run lint
```

### Force resolutions
```
npm run resolve
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## License
This work is copyrighted and cannot be reproduced without a written permission. © 2020 @anthonyboutinov. All rights reserved. Alberick logo, photos etc. © 2020 Alberick Medisch Centrum. All rights reserved. Artwork design by pch.vector / Freepik.
