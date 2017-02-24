# react-pagination

分页组件
[在线demo](http://datianyun.github.io/pagination "Title")
### Installation
``` sh
npm install reactui-pagination
```

### API
### props

|name|type|default| description|
|-----|---|--------|----|
|onclick | func |- | 点击分页事件|
|config | object| -| 配置 |

config中包括
currentPage ： 当前页
total：总页数
perNum： 每页数目
### Demo

``` sh
npm run start
```

http://localhost:8888/example/

### Usage
``` javascript
const config = {
    currentPage : 1,
    total : 100,
    perNum : 6
}
<Pagination onclick={this.pageClick.bind(this)} config={config}></Pagination>

```
