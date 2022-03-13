往 `指定的目录` 添加文件，如果该文件后缀为：`ttf`, `font`, `fon`, `otf`, `eot`, `woff`, `ttc`，则 `iFlutter` 会视该文件为字体文件，便自动注册自定义字体到 `pubspec.yaml` 中，同时创建或修改 `lib/res/i_font_res.dart` 以生成引用字段。

如果项目已经有自定义字体配置，**首次使用 `iFlutter` 需要确保**，`family:xxx` 和字体文件名(不包括后缀)一致，例如：

```
flutter:
  ...
  fonts:
    - family: a
      fonts:
        - asset: relative/path/b.ttf
```
则需要修改 `relative/path/b.ttf` 文件名为 `a.ttf`
