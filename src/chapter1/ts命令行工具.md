通过上一节的介绍我们可以看出ts是不能直接运行的，需要经过编译生成js文件，才可以运行

对此，官方给我们提供了一个typescript的命令行工具可供我们来实现编译

接下来就使用yarn或者npm来安装typescript这个命令行工具
```shell
# 全局安装typescript
yarn global add typescript
```

安装完成之后，系统会多出一个tsc命令
```shell
# 如下 tsc 后面跟上需要编译的ts文件，默认就会在当前目录下生成一个和ts文件同名的js文件
tsc *.ts
```