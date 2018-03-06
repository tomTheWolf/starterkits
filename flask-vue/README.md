# A Vue.js front-end served by a Flask back-end, minimal boilerplate and sane directory structure

## Build client code

``` bash
# install dependencies
npm install

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run all tests
npm test
```

## Build docker image
docker build -t flask-vue .

## Run docker image
docker run -p 5000:5000 -t flask-vue

