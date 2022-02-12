# docsify-cn-beian

> docsify备案插件

## Usage

1. add script
``` html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/yhuan416/docsify-cn-beian/src/docsify-cn-beian.css">
<script src="https://cdn.jsdelivr.net/gh/yhuan416/docsify-cn-beian/src/docsify-cn-beian.js"></script>
```

2. add config
``` js
window.$docsify = {
    beian: {
        debug: false,       // bool                     default : false
        align: "left",      // string [text-align]      default: "left"
        ICP: "",            // string                   default : ""
        NISMSP: {
            text: "",       // string                   default : ""
            url: "",        // string                   default : ""
            code: ""        // string                   default : ""
        },
    },
}
```

| 参数 | 参数描述 | 参数类型 | 默认值 |
|-|-|-|-|
|debug|调试打印开关|bool|false|
|align|对齐方式|string [text-align]| "left" |
|ICP|ICP备案号[粤ICP备xxxx号]|string|""|
|NISMSP.text|公安部备案号[粤公网安备 xxxx号]|string|""|
|NISMSP.url|公安部备案链接|string|""|
|NISMSP.code|公安部备案号的数字部分|string|""|
