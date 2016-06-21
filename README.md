# Vuejs-rating
>A Vue.js rating plugin written by Benjamin Reid and updated by me.

### Installation
1. Copy the file
2. Add the component to your component
  ```components: {
              'star-rating': require('./../../plugins/star-rating')
              }```
3. Add the component to your view
  ```<star-rating :value.sync="writeModel.rating" max="5"></star-rating>```

Tested on Vue.js v1.0.25.

Demo: https://jsfiddle.net/bf9arnyz/1/
