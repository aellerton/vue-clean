# vue-clean

An attempt to make a vue+typescript+vuetify base project that handles
linting and fixing formatting cleanly, quickly, correctly and simply.

So far it is "not bad" but not perfect.

Manually formatting individual files in WebStorm with Prettier (Ctrl+Shift+Alt+P)
works nicely. The default formatting (Ctrl+Shift+L) it's close, but indents vue
typescript one level in.

Edit `.prettierrc` to modify whether semicolons are present, trailing commas, etc.

It's not perfect though:

1. Running "yarn lint" on a file with obvious issues doesn't pick up anything

2. I can't figure out how to get it to prettify an entire tree.

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Run your unit tests
```
yarn run test:unit
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
