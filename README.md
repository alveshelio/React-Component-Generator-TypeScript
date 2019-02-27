# React Component Generator TypeScript

React Component Generator TypeScript is a cli for generating react component for typescript based architecture.

## Install
* Global installation
  ```bash
  # Using yarn package manager
  $ yarn global add react-component-generator-typescript

  # Using npm package manager
  $ npm i -g react-component-generator-typescript
  ```
* Local installation
  ```bash
  # Using yarn package manager
  $ yarn add -D react-component-generator-typescript

  # Using npm package manager
  $ npm i -D react-component-generator-typescript
  ```

## Usage
`<componentName>` is the name of component that can be with or without directory

eg:
- `src/webparts/webpartName/components/ComponentName`

  this will generate component named *`ComponentName`* in the directory *`./src/webparts/webpartName/components/ComponentName`*

- `ComponentName`

  this will generate component named *`ComponentName`* in the directory *`./ComponentName`*
### Generate React Stateless Component

```bash
$ tsg statelessComponent componentName
# or
$ tsg s componentName
```

### Generate React Class Component

```bash
$ tsg classComponent componentName
# or
$ tsg c componentName
```

  ### Generate React Redux Container Component

```bash
$ tsg containerComponent componentName
# or
$ tsg r componentName
```
## License

React Component Generator TypeScript is MIT licensed.
