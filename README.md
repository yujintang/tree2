## 模仿linux tree
**可以做到文件过滤，使其使用更方便**

#### 安装
```
$npm install tree2 -g
```

#### 使用
```
$tree2 
```
#### show 某个文件夹下内容
```
$tree2 /xx/xx/x
```
#### 查看常规Node.js 文件目录树
**不展开node_modules, 同时进行配色**
```
$tree2 -a
```
#### 对文件树进行保存
**将该文件树保存到该命令下的tree2.md**
```
$tree2 -s
```
#### 详细例子
**如将/usr/local 下文件进行tree， 并且配色， 不展开 node_modules, go 两个文件夹下的内容, 最后保存**
```
$tree2 -c -i go,node_modules -s /usr/local
```

#### 具体用法
```
$tree2 -h 
```

**有任何问题，可联系：shanquan54@gmail.com**