#iMkdirs

多层级文件夹生成

## 安装
#### 全局使用
```shell
npm install -g imkdrs
```

#### 文件引用 
```shell
npm install imkdrs
```

## 示例
#### 全局使用
```shell
# 生成 abc def 123 三个文件夹
mk abc def 123

# 在当前目录生成一个多级目录： abc/def/123
mk abc abc/def/123
```

#### 文件夹中使用
```shell
var mk = require('imkdirs');

# 在当前目录生成一个多级目录： abc/def/123
mk('abc/def/123')
```