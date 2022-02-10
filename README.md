## 无限流TRPG星光规则书 在线版

规则书作者为 老鹿 ，该仓库主要用于生成在线规则书文档使用。
此外仓库也可以通过多人协助的形式，进行Pull Request 的形式进行文档编辑修改。
而且有什么建议或者BUG 都可以在 Issues 进行提出。

此外也可以通过静态HTML 生成多端APP 方便快捷使用。

### 依赖技术
1. docsify
2. markdown

### 实现说明

大家可以通过编写 markdown 文档（形如 .md 为后缀的文档） ，然后通过docsify 生成 HTML 浏览页面。
docsify 也提供了一些全局搜索的功能。
gitee 可以在线部署静态页面
本仓库会先实现具体的框架，以供大家参考使用。

### 目录说明
1. `/docs` 为 markdown 文档存放区 主要用于 docsify 使用。此外该目录下的文件，主要为 docsify 的配置文件 和 主页文档。
2. `/docs/image` 为图片文件存放区。如果以后有大量的图片，可以再细分图片文件夹
3. `/docs/items` 为子项文档，像规则书的规则、资源等内容，都放在里面。例如是基础规则，应当在该子项里面再建文件家，例如: `/docs/items/rules/`

### 文件说明
1. `/docs/.nojekyll` 为仓库声明文档，告诉gitee pages 这不是一个 jekyll 仓库。
2. `/docs/README.md` 为文档首页介绍。
3. `/docs/_sidebar.md` 为侧栏目录内容。
4. `index.html` 为 docsify 的配置文件。