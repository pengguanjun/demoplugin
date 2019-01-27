# 为插件编写操作手册

操作手册并不是必须部分，但希望自己编写的插件能更好的服务用户，它是是非常重要的。这里我们演示如何给插件编写操作手册。



在插件项目的顶级目录下，创建doc文件夹，在文件夹里即可用markdown为你的插件编写操作文档了，需要注意的是文件名需要与插件的title一致，这样ImagePy的文档管理器即可将文档与插件进行关联。工具类型的插件与菜单类型的插件都可以编写文档。



当插件编写完成后，我们有如下方式对文档进行查阅：

1. 我们可以通过参数对话框的Help按钮

2. 工具栏图标上右键单击

3. 使用 **Plugins > Manager** 下的各种 **Tree View**

   

doc下所有的markdown文件都会被解析并通过文件名关联给对应插件，所以这里并不强制要求文件组织方式，但我们强烈建议维护一个与插件目录一致的文档目录，这样方便管理和维护，如果有必要我们可以加入多的目录文件，添加对应的跳转，这样整个doc目录也可以在github上进行阅读。