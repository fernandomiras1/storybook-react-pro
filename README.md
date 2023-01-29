# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Paquetes Instalados FMiras

Te permite borrar folder desde NPM Script, por ejemplo podemos usar el comando rm -rf

### `yarn add -D rimraf`

Te permite copiar folder desde NPM Script

### `yarn add -D copyfiles`

Copiamos todos los archivos de CSS a nuestro dist

### `"copy-files": "copyfiles -u 1 src/**/*.css dist/"`

peerDependencies ( le decimos que lib tiene que tener para que nuestro paquete funcione )

Automatizar los commit para que hagan release automaticos.

Si en el commit escribimos
--fix: Enteonces es un bug y me incrementa a un pacht ( ultimo nro )
--fear: Enteonces es un feature y me incrementa a un Minor ( el nro del medio )
--perf : Enteonces es un cambio muy importante en al app y me incrementa a un major ( el 1er nro )

Para mas info leer aqui: https://www.npmjs.com/package/semantic-release

### `yarn add -D semantic-release`

Usar estos plugins para trabajar con Semantic Versioning

`package.json`

```
"plugins": [
    "@semantic-release/commit-analyzer",
    "@semantic-release/release-notes-generator",
    "@semantic-release/changelog",
    "@semantic-release/github",
    "@semantic-release/npm",
    "@semantic-release/git"
],
```

TOken de github:: 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
