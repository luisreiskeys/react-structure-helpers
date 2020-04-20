# react-structure-helpers CLI

This package was inspired on this repo:

https://github.com/Rocketseat/youtube-cli-node-gluegun

A CLI for react-structure-helpers. 

## Instalation

```
yarn global add react-structure-helpers
```
or

```
npm install -g react-structure-helpers
```
## Usage

## generate:pages

generate one or more pages inside src/pages for ReactJS and React Native projects

```
rctsh generate:pages page1 page2 page3 ...
```

### options

--route . Use this option for create a route.js file with imports for the pages created. If the routes.js file already exists the imports will be added on the end of file.

To do ***
To add the imports on rigth location if the routes.js file exists



```
rctsh generate:pages page1 page2 page3 --route
```

### generate:components

generate one or more components inside src/components for ReactJS and React Native projects

```
rctsh generate:components page1 page2 page3 ...
```

<img alt="rctsh" title="rctsh" src="assets/react-structure-helpers.gif" width="100%" />

# License

MIT - see LICENSE

