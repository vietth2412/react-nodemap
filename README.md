# react-nodemap

> Made with create-react-library

[![NPM](https://img.shields.io/npm/v/react-nodemap.svg)](https://www.npmjs.com/package/react-nodemap) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install react-nodemap
```
or
```bash
yarn add react-nodemap
```


## Usage

```jsx
import React, { Component } from 'react'

import MyComponent from 'react-nodemap'
import 'react-nodemap/dist/index.css'

class Example extends Component {
  this.data = [
  {
    "name":"如何学习D3",
    "children":
    [
      {
        "name":"预备知识",
        "children":
        [
          {"name":"HTML & CSS", "children": []},
          {"name":"JavaScript", "children": []},
          {"name":"DOM", "children": []},
          {"name":"SVG", "children": []},
          {"name":"test", "children": []}]
      },
      {
        "name":"安装",
        "children": []
      },
      {
        "name":"入门",
        "children":
        [
          {"name":"选择集", "children": []},
          {"name":"test", "children": []},
          {"name":"绑定数据", "children": []},
          {"name":"添加删除元素", "children": []},
          {
            "name":"简单图形",
            "children":
            [
              {"name":"柱形图", "children": []},
              {"name":"折线图", "children": []},
              {"name":"散点图", "children": []}]
          },
          {"name":"比例尺", "children": []},
          {"name":"生成器", "children": []},
          {"name":"过渡", "children": []}]
      },
      {
        "name":"进阶", "children": []
      }]
  }
]
  render() {
    return <MyComponent value={this.data}/>
  }
}
```

## License

MIT © [ysqsimon](https://github.com/ysqsimon)