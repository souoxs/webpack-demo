# webpack-demo

此部分对应管理资源部分（加载字体）

我们修改了webpack.config.js文件，引入file-loader，用来解析字体

我们新增了一个名为myFont.otf的字体，同时，在style.css中使用此字体

最后，运行npm run build 命令，查看效果

> 打开index.html，我们可以看到Hello webpack，文字的颜色变成了红色，且有背景图片出现，文字字体也发生了变化

> 请注意这里字体并未被压缩，大小没变，也就是说，webpack默认是不会压缩字体大小的

## 

我们先来看下一个TAG(V2.4)

在命令行 / 终端输入以下命令

```bash
git checkout v2.4
```





