markdown文件位于source文件夹下

github pages网址

https://czc13611858691.github.io/SphinxPageTest/index.html

如何写文档

参考source下的文件结构

写完之后执行如下命令

```bash
make build
```

如何调试

```bash
sphinx-autobuild source build/html
```

推送的话，把build html文件夹内的内容推送到当前仓库中的gh-pages分支上就可以了