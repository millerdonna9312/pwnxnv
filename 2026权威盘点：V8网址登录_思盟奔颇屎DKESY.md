V8网址登录【Q-——333307——】V8网址登录【 辋芷《888yx●vip》 】
V8网址登录【Q-——333307——】V8网址登录【 辋芷《888yx●vip》 】

 从零开始搭建个人博客：GitHub Pages + Hexo 完整教程（2025亲测有效）

你是否想过拥有一个完全属于自己的技术博客？不需要买服务器，不需要备案，甚至零成本就能上线？今天这篇文章，手把手教你用 GitHub Pages + Hexo 搭建一个速度快、可定制性高的静态博客。无论你是编程新手还是老手，这套方案都能帮你轻松搞定。

 为什么选择 Hexo + GitHub Pages？

- 免费且稳定：托管在 GitHub 上，全球访问速度极快。
- SEO 友好：静态页面，天然利于百度、谷歌收录。
- 高度可定制：支持主题切换，配合 `hexo-generator-search` 还能实现站内搜索。
- 写作体验好：支持 Markdown 语法，专注内容创作。

 第一步：环境准备（5分钟）

1. 安装 Node.js（建议使用 16.x 以上版本），官网下载安装包即可。
2. 安装 Git，用于代码版本管理。
3. 注册 GitHub 账号，并创建仓库，命名为 `你的用户名.github.io`。

 第二步：安装并初始化 Hexo

打开终端，全局安装 Hexo 命令行工具：

```bash
npm install -g hexo-cli
```

接着初始化博客文件夹：

```bash
hexo init my-blog
cd my-blog
npm install
```

启动本地预览服务：

```bash
hexo s
```

浏览器访问 `http://localhost:4000`，看到默认博客即代表成功。

 第三步：部署到 GitHub（关键步骤）

安装部署插件：

```bash
npm install hexo-deployer-git --save
```

修改根目录下的 `_config.yml` 文件，在 `deploy` 段落填入你的仓库地址：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

执行一键部署命令：

```bash
hexo clean && hexo g && hexo d
```

访问 `https://你的用户名.github.io`，你的博客已经正式上线了！

 第四步：SEO 优化配置（重点）

为了让百度更快地收录你的文章，需要做好以下三点：

1. 开启站点地图：安装插件 `hexo-generator-sitemap`，并在 `_config.yml` 中启用。
2. 提交链接到百度站长平台：将生成的 `sitemap.xml` 链接提交到百度搜索资源平台。
3. 配置 robots.txt：在 `source` 目录下创建 `robots.txt`，允许百度蜘蛛抓取。

 总结与互动

至此，你的个人博客已经可以正式对外发布文章了。是不是很简单？如果你在搭建过程中遇到任何报错，欢迎在评论区留言，或者将此文章点赞+收藏，方便后续查阅。

对了，上线后第一件事当然是写一篇“Hello World”啦！你的博客准备写点什么？在评论区立个 Flag，我们一起见证你的第一篇文章诞生！🚀

相关推荐：

https://github.com/stoneconnor94/facjpk/blob/main/2026%E5%AE%98%E6%96%B9%E7%94%84%E9%80%89%EF%BC%9AV8%E5%9C%B0%E5%9D%80%E4%B8%8B%E8%BD%BD_%E6%8B%90%E7%94%A8%E5%82%A9%E5%91%98%E8%B4%A4EFLZE.md

<img src="https://i.postimg.cc/J7sVTRgT/V8-00010.png" />

相关推荐：

https://github.com/stoneconnor94/facjpk/commit/c806a39503c4636ad6ed995672f528752c9ca85b

<img src="https://i.postimg.cc/J7sVTRgT/V8-00010.png" />
相关推荐：

https://github.com/yangpatricia1/ybxyao/blob/main/2026%E5%AE%98%E6%96%B9%E5%B9%B2%E8%B4%A7%EF%BC%9AV8%E5%9C%B0%E5%9D%80%E5%9C%B0%E5%9D%80_%E4%B9%98%E9%80%8A%E7%AF%AE%E4%BB%9D%E8%94%9AXJWDV.md

<img src="https://i.postimg.cc/SKg3rPf5/V8-00018.png" />
相关推荐：

https://github.com/yangpatricia1/ybxyao/commit/3264d13aa213b926f870789f268d3d891068903a

<img src="https://i.postimg.cc/hGspn7JM/V8-00003.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
