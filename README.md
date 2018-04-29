### 开启json服务器用于获取数据

```
cd json-server
npm install
npm start

```

> 数据文件：db.json
> 数据地址：http://localhost:3000/data


package.json

```
{
  "name": "jsonserver",
  "version": "1.0.0",
  "description": "test restful api",
  "main": "index.js",
  "scripts": {
    "json:server": "json-server --watch db.json",
  },
  "author": "",
  "license": "ISC",
  "dependencies": {
    "json-server": "^0.12.0"
  }
}
```