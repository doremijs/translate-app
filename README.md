# 在线国际化翻译小助手

该项目可以帮助我们对`react-intl`生成的国际化配置做辅助在线翻译的功能。

## 使用方法

1. 编译`react-intl`项目以便生成包含国际化`json`数据的`lang`目录，要求生成一份最新翻译抽取出的`defaults.json`文件，其余的为各语言的 json 文件
2. 压缩`lang`目录，生成`lang.zip`
3. 打开[https://doremijs.github.io/translate-app/](https://doremijs.github.io/translate-app/)，点击下方`选择zip文件上传`按钮上传打包的 zip 文件
4. 在页面填写未翻译的空白项，完成后点击`导出`按钮下载 zip 包，解压缩后替换代码中的`lang`目录中的文件
