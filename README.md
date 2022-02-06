# frontend-app-vuejs

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## Build & Run using docker

### Build
```
docker build -t frontend-app-vuejs:local .
```

### Run
```
docker run -it -p 8080:80 --rm --name frontend-app-vuejs-1 frontend-app-vuejs:local
```