# VUE CESIUM

<p align="center">
  <img src="https://zouyaoji.top/vue-cesium/favicon.png" width="200px">
</p>
<p align="center">Cesium components for Vue 2.x that can help you load Cesium built package or other third-party packages which are built on Cesium.</p>

[![npm](https://img.shields.io/npm/v/vue-cesium.svg)]()
[![Travis](https://img.shields.io/travis/zouyaoji/vue-cesium.svg)]()
[![Package Quality](http://npm.packagequality.com/shield/vue-cesium.png)](http://packagequality.com/#?package=vue-cesium)
[![npm](https://img.shields.io/npm/dm/vue-cesium.svg)]()
[![license](https://img.shields.io/github/license/zouyaoji/vue-cesium.svg)]()

## Languages

- [中文](https://github.com/zouyaoji/vue-cesium/blob/master/README.zh.md)
- [English](https://github.com/zouyaoji/vue-cesium/blob/master/README.md)

## Documentation

- [Online Documentation](https://zouyaoji.top/vue-cesium)
- [For more examples](https://github.com/zouyaoji/vue-cesium-demo)

## Get Start

Amateur learning Vue component development, continuous development.

### Installation

```bash
npm i --save vue-cesium
```

### Initialization

```javascript
import Vue from 'vue'
import VueCesium from 'vue-cesium'
// Vue-Cesium will load Cesium.js from `https://unpkg.com/cesium/Build/Cesium/Cesium.js`
Vue.use(VueCesium)
```

```javascript
import Vue from 'vue'
import VueCesium from 'vue-cesium'

Vue.use(VueCesium, {
  // cesiumPath is path of Cesium.js', for example:
  // local Cesium Build package:
  // cesiumPath: /static/Cesium/Cesium.js
  // Personal online Cesium Build package：
  // cesiumPath: 'https://zouyaoji.top/vue-cesium/statics/Cesium/Cesium.js'
  // Personal online SuperMap Cesium Build package：
  // cesiumPath: 'https://zouyaoji.top/vue-cesium/statics/SuperMapCesium/Cesium.js'
  // Official Online Cesium Build package：
  cesiumPath: 'https://unpkg.com/cesium/Build/Cesium/Cesium.js'
})
```

### Usage

```vue
<template>
  <div class="viewer">
    <cesium-viewer> </cesium-viewer>
  </div>
</template>

<style>
.viewer {
  width: 100%;
  height: 400px;
}
</style>
```

## TODOS

- Use rollup odule bundler
- Doucment & Demo
- Add more components
- ...

## Contributing

[Contributing Guide](https://github.com/zouyaoji/vue-cesium/blob/master/CONTRIBUTING.md)

## License

[MIT License](https://opensource.org/licenses/MIT)

Copyright (c) 2018-present, zouyaoji <370681295@qq.com>

## Reference

A good project: [vue-baidu-map](https://github.com/Dafrok/vue-baidu-map)
