当项目使用`flutter_localizations`支持国际化后，不同语种的字符资源需要手动添加到不同的`*.arb`文件中，过程枯燥而毫无技术含量。针对这一问题，`iFlutter`支持快速添加、移除国际化资源，效果如下：

- 添加资源 (快捷键: Option/Alt + A)

![添加资源](https://iflutter.toolu.cn/configs/intl_add.gif)

- 移除资源 (快捷键: Option/Alt + R)

![移除资源](https://iflutter.toolu.cn/configs/intl_remove.gif)


如果当前IDEA安装了`flutter_intl`插件，为了提供统一的开发习惯，`iFlutter`会在`flutter_intl`功能入口处，注入资源管理入口，效果如下：

![功能注入](https://iflutter.toolu.cn/configs/intl_inject.png)
