## SublimeTransit

一个在 Sublime 编辑器上翻译单词的插件。使用[有道智云](http://ai.youdao.com/docs/doc-trans-api.s#p02)提供的翻译 api 实现。

tip: 有道智云的翻译服务是收费服务，具体收费可参加其[文档](http://ai.youdao.com/docs/doc-trans-price.s#p03)

建议自己注册一个账号，获取 appKey 和 secretKey，将代码里的对应的 appKey 和 secretKey 换成自己的。（按一个单词 10 个字符来算，新人可免费翻译近 21 万个单词，一天翻译 100 个，可以免费用近 6 年了~）

## 安装
- 方式一：使用 Sublime 的 「Package Control」包管理器进行安装，默认你已安装了包管理器，打开它，搜索「Translate-CN」，点击安装后，即可使用。
- 方式二：直接下载压缩包，解压到 Sublime 的 Packages 中，即可使用。

## 使用方法

- 快捷键

```python
# MacOs:
alt + t 翻译选中的文本
alt + i 翻译输入的文本

# Windows & Linux
alt + t 翻译选中的文本
alt + i 翻译输入的文本
```

- 右击，显示快捷菜单，选中 Translate
  - current text  翻译选中的文本
  - input text    翻译输入的文本

## 配置

你可以在 Preferences --> Package Settings -->  Translate --> Settings - Default 下进行插件配置
```js
{
    "translate_whole_word": false,//全词翻译，当你选择了单词的一个部分，也会翻译整个单词
}
```
