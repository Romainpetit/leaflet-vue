# Leaflet-vue
## An example showcase of a Vue2Leaflet map integration

![The browser output](preview.png)

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

## Important Leaflet map setup steps

### [`In Main.js`](https://github.com/Romainpetit/leaflet-vue/blob/master/src/main.js)
- Load the Leaflet CSS file
- Add the lines related the icons file path, otherwise the markers will not show.


### [`In Map.vue`](https://github.com/Romainpetit/leaflet-vue/blob/master/src/components/Map.vue)
- Load the required components from the `vue2-leaflet` library in the script
- Call the components with `LMap` as parent in the template
