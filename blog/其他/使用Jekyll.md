# 1. 配置文件

在站点根目录中的_config.yml或_config.toml文件中指定
```
theme: jekyll-theme-cayman
baseurl: /blog5
permalink: /:year/:month/:day/:title
auto: true
markdown: rdiscount
```
GitHub Pages网站的某些配置设置无法更改。
```
lsi: false
safe: true
source: [your repo's top level directory]
incremental: false
highlighter: rouge
gist:
  noscript: false
kramdown:
  math_engine: mathjax
  syntax_highlighter: rouge
```
默认情况下，Jekyll不会生成以下文件或文件夹：
```
位于名为/node_modules或的文件夹中/vendor
开始_，.或#
以 ~
被exclude配置文件中的设置排除
```
如果您希望Jekyll处理这些文件中的任何一个，则可以使用includes配置文件中的设置。

