# vuejs-bootstrap-4

> Vue.js bootstrap-4 boilerplate

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

## Using Bootstrap
Import Bootstrap JS and css at your app root file:
```js
import 'bootstrap';
import '../node_modules/bootstrap/dist/css/bootstrap.min.css';
```
  
Then you can use Bootstrap classes as well as JS. For example:

```js
$('.carousel').carousel();
```

## Using Sass

You can write Sass style directly at you Vue components like this:
```
<style lang="sass">
  h2 {
    border: 2px solid aquamarine;
  }
</style>
```
or  
import scss styles from your styles folder

```
<style lang="sass">
  @import "~styles/main"
</style>
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
