# 暂停更新
## 你好

这里是四川大学生存指南 <https://y0omu.github.io/SCUSurvivalGuide>

- 通过主题和目录浏览文章。
    - 电脑端：在上方标签栏选择主题，在左侧目录选择文章。
    - 移动端：点击左上角图标选择主题和文章。
- 搜索关键词查找文章。

## 如何添加文章

### 如果您没有使用Github的经验
联系我

### 如果您有使用Github的经验
在对应的目录下创建新的 Markdown 文件。例如，如果你想为“生存篇”添加一篇新文章，可以在 SURVIVALGUIDE 目录下创建一个新的 Markdown 文件：
```bash
touch SURVIVALGUIDE/new_article.md
```
然后打开 mkdocs.yml 文件，在 nav 部分添加新文章的路径。例如，添加一篇名为“新文章”的文章：
```yaml
nav:
  - 生存篇:
      - SURVIVALGUIDE/index.md
      - SURVIVALGUIDE/welcome.md
      - SURVIVALGUIDE/new_article.md  # 添加这一行
```
然后提交`Pull Request`

### 创作阶段
目前还在创作阶段，希望大家踊跃参与
目标是争取在九月份新生入学前初步构建好整个的项目。

不知道写什么的可以参考友校[上海交通大学生存手册](https://survivesjtu.gitbook.io/survivesjtumanual)
