# ASoul 评论区梗解释

![TOC GENERATOR](https://github.com/sakifore/ASoul_meme_explanation/actions/workflows/gen_toc.yml/badge.svg)

## 当前工作

[ASoul-梗百科](./asoul.md)

## 如何贡献

如果你也对这个梗百科有兴趣，可以依照如下步骤进行贡献：

1. `fork` 仓库

点击右上角的 `fork` 按钮将该仓库 fork 到你的账户下。

2. 拉取仓库到本地并编辑

拉取仓库:

```bash
git clone https://github.com/{{YOURNAME}}/ASoul_meme_explanation
```

新建分支：

```bash
git checkout -b {{NEW_CHANGE}}

# 例子
git checkout -b some-meme
```

然后对 `asoul.md` 文件进行编辑， 编辑时请尽量依照下章梗百科格式的要求。

同时请注意几点：

- 请不要编辑 `README.md`。
- 请不要编辑 `asoul.md` 里目录索引的部分，上传后会有脚本自动处理。
- 请不要编辑 `LICENSE.txt`

3. 提交

```bash
git add . && git commit -m "你做了什么修改"
git push origin master
```

4. 提交 PR

点击 Pull Request, 将分支提交到这个仓库。

## 梗百科格式

关于该仓库梗百科编辑有如下要求。

1. 请使用 Markdown 格式编辑。

如对 Markdown 语法不熟悉，可以查看这篇文章： [Markdown语法教程](https://markdown.com.cn/intro.html#markdown-%E6%98%AF%E4%BB%80%E4%B9%88%EF%BC%9F)

2. 请使用如下格式进行百科内容编辑

```markdown
## 梗归类（比如电竞类）

### 梗名字 （比如“含金量”）

**变体**：梗的一些变体 （比如 “知道顶碗人的含金量吗”）

**来源**：梗的来源 （可以是直接的视频地址，或者文字解释渊源。）

**语义**：应该如何使用这个梗 （比如介绍 “含金量” 应该在什么情况下使用）

**应用**：梗的使用范例。
```

3. 请使用正确的中英文文案编辑格式

请查看 [中文文案排版指北](https://github.com/mzlogin/chinese-copywriting-guidelines/blob/Simplified/README.md)
并依照文章规范进行文案编辑。

4. （推荐，可选）可以使用如下的 Commit Message 模板进行 commit

```text
<type>(optional text): <descriptions>
```

例子：

- 修改了一些语法错误：

```text
git commit -m "订正： 修复了含金量条目的语法错误"
```

- 增加了新的条目：

```text
git commit -m "更新： 新增 “欧系给” 条目"
```

可以参考下列网站来获得更详细描述：

- [Udacity Git Commit Message Style Guide](udacity.github.io/git-styleguide/)
- [Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/)

## MIT LICENSE

该仓库遵循 [MIT LICENSE](./LICENSE.txt)

