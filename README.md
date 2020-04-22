## Git versioning

**Commit message format**

**type**[scope]: _subject_

Allowed - **type**

- **fix** - fix broken code
- **ref** - improve code
- **mod** - add, remove file
- **docs** - comment code, documentation
- **unit** - a working feature or functionality
- **wip** - work in progress, not representative of the final implementation

Allowed - [scope] <br>
Define the extent of influence by the commit change.

- **con** - content
- **des** - design
- **vue** - vue logic
- **vuex** - vuex logic
- **pro** - project development environment

Format - _subject_

- use imperative, present tense: “change” not “changed” nor “changes”
- don't capitalize first letter
- no dot (.) at the end


# watch-us-build-trello

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

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
