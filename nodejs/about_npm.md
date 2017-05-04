## 包与NPM

包和NPM是将相互独立的模块联系在一起的一种机制。

### 包

包可以看作是一个存档文件，即一个目录直接打包为.zip或者tar.gz格式的文件，安装后解压还原为目录。符合CommonJs规范的包应该包含如下文件：
- package.json 包描述文件

  CommonJS为package.json定义了些许必须字段，如name、description、version等。

- bin 存放可执行二进制文件的目录
- lib 存放JavaScript代码的目录
- doc 存放文档的目录
- test 存放单元测试用例的目录

在包描述文件规范中，NPM实际需要的字段有name,version,description,keywords,repositories,author,bin,main,scripts,engines,dependencies,devDependencies。其中author,bin,main,devDependencies这4个是比包规范中多出来的。

### NPM

常用命令
- npm -v
- npm 查看帮助引导说明
- npm help


NPM镜像安装【TODO】


NPM包发布
