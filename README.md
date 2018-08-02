# webpack-demo

此部分对应管理资源部分（加载字体）

我们使用npm安装了file-loader依赖，为解析图片文件做准备

我们修改了webpack.config.js文件，引入file-loader

我们新增了一个名为icon.png的图片，同时，在index.js和style.css中使用此图片

最后，运行npm run build 命令，查看效果

> 打开index.html，我们可以看到Hello webpack，文字的颜色变成了红色，且有背景图片出现

> 请注意这里图片并未被压缩，大小没变，也就是说，webpack默认是不会压缩图片大小的

## 

我们先来看下一个TAG(V2.3)

在命令行 / 终端输入以下命令

```bash
git checkout v2.3
```





