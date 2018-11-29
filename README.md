# Create-initFiles-Script

- 脚本作用： 创建初始的html、css和js文件

- 实现方式： demo.sh xxx 可在当前目录下生成目录 xxx，demo.sh yyy 可生成目录 yyy

- 生成的目录结构如下：
```
├── css
│   └── style.css
├── index.html
└── js
    └── main.js
```
- index.html 的内容为
```
<!DOCTYPE>
 <title>Hello</title>
 <h1>Hi</h1>
```
- css/style.css 的内容为
```
h1{color: red;}
```
- js/main.js 的内容为
```
var string = "Hello World"
alert(string)
```


