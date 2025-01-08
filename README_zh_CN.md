[English](https://github.com/siyuan-note/theme-sample/blob/main/README.md)

这是一个手动模仿飞书文档风格而制作出来的深色主题。

飞书风格是一个办公味比较浓重的风格，相较于原版 `midnight`来说没有那么活泼。更注重沉稳、清晰。当然，相较于`Notion`和`VS Code`来说，咱们飞书的风格还是很年轻的。

以下是互联网搜罗的一些文书风格的夸夸：
* 飞书以其简洁大气的设计风格，清新的色彩搭配以及流畅的界面布局，给人带来视觉上的享受。从图标到整体框架，每一处细节都彰显着精致与用心。

* 企业选择飞书，往往“始于颜值，终于才华”。文和友CEO冯彬非常坦诚地表示，他们选择飞书的第一个理由很简单：好看，颜值是第一生产力。

细心的朋友应该看出来了，LOGO都是我手动模仿的~

生成 package.zip
* 在 GitHub 上创建一个新的发布，使用主题版本号作为 “Tag
  version”，示例 https://github.com/siyuan-note/theme-sample/releases
* 上传 package.zip 作为二进制附件
* 提交发布

如果是第一次发布版本，还需要创建一个 PR 到 [Community Bazaar](https://github.com/siyuan-note/bazaar) 社区集市仓库，修改该库的
themes.json。该文件是所有社区主题库的索引，格式为：

```json
{
  "repos": [
    "username/reponame"
  ]
}
```

PR 被合并以后集市会通过 GitHub Actions 自动更新索引并部署。后续发布新版本主题时只需要按照上述步骤创建新的发布即可，不需要再
PR 社区集市仓库。

正常情况下，社区集市仓库每隔 1 小时会自动更新索引并部署，可在 https://github.com/siyuan-note/bazaar/actions 查看部署状态。
