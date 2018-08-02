# webpack-demo

此部分对应起步部分（创建一个bundle文件）

我们新建了一个dist目录，同时把index.html文件移入

使用npm安装lodash依赖（npm i --save lodash），同时，修改lodash引入方式

index.js使用import方式引入lodash

index.html 去掉script标签引入lodash，同时修改index.js => main.js(打包后)

最后，使用npx webpack生成main.js

> npx 会自动查找当前依赖包中的可执行文件，如果找不到，就会去 PATH 里找。如果依然找不到，就会帮你安装！

> 打开index.html，我们可以看到Hello webpack

## 

我们先来看第3个TAG(V1.2)

在命令行 / 终端输入以下命令

```bash
git checkout v1.2
```





