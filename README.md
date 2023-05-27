# lowcode-engine-docs

这里是关于学习 lowcode-engine 的笔记，如果需要更多信息可以访问 [官网](https://lowcode-engine.cn/index)

Notes on learning the lowcode-engine. For more information, please visit the official [website](https://lowcode-engine.cn/index)

- [x] [物料](./%E5%9F%BA%E7%A1%80%E7%BB%84%E4%BB%B6%E8%BD%AC%E7%89%A9%E6%96%99%E4%BF%A1%E6%81%AF%E6%95%B4%E7%90%86%E8%AF%B4%E6%98%8E.md)

## XSwitch
```bash
{
  "proxy": [
    [
      "http://localhost:5557/vue-simulator-renderer.js",
      "http://localhost:5559/vue-simulator-renderer.js"
      // "http://localhost:8000/vue-simulator-renderer.js"
    ],
    [
      "http://localhost:5557/vue-simulator-renderer.css",
      "http://localhost:5559/vue-simulator-renderer.css"
    ],
    [
      "http://localhost:5577/js/vue-simulator-renderer.js",
      "http://localhost:5579/vue-simulator-renderer.js"
    ],
    [
      "http://localhost:5577/js/vue-simulator-renderer.css",
      "http://localhost:5579/vue-simulator-renderer.css"
    ],
    [
      "http://localhost:5557/dist/CustomerDetailComponents.umd.min.js",
      "http://localhost:8000/dist/CustomerDetailComponents.umd.min.js"
    ],
    [
      "http://localhost:5557/dist/CustomerDetailComponents.css",
      "http://localhost:8000/dist/CustomerDetailComponents.css"
    ],
    // [
    //   "http://localhost:8000/vue-simulator-renderer.js",
    //   "http://localhost:5559/vue-simulator-renderer.js"
    // ]
    // [
    //   "https://static.wshoto.com/fe/lowcode/libs/lowcode-engine-ext/1.0.4-beta.1/dist/js/engine-ext.js",
    //   "http://localhost:4008/js/engine-ext.js"
    // ],
    // [
    //   "https://alifd.alicdn.com/npm/@alilc/lowcode-engine-ext@1.0.5/dist/js/engine-ext.js",
    //   "http://localhost:4008/js/engine-ext.js"
    // ]
  ]
}
```
