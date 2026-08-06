摩鑫官方娱乐【Q-——333307——】摩鑫官方娱乐【 辋芷《888yx●vip》 】
摩鑫官方娱乐【Q-——333307——】摩鑫官方娱乐【 辋芷《888yx●vip》 】

 从0到1搭建个人博客：GitHub Pages + Hexo 完整教程

> 还在羡慕别人炫酷的技术博客？其实你也能轻松拥有。本文手把手教你用 GitHub Pages + Hexo，免费搭建一个属于自己的博客站点。

 为什么选择 Hexo + GitHub Pages？

很多开发者想写博客，但卡在第一步：服务器贵、部署麻烦。GitHub Pages 提供免费静态托管，搭配 Hexo 框架，你只需要专注写 Markdown 文章，一条命令即可完成部署。本文将带你完成从环境配置到域名绑定的全流程。

 第一步：环境准备

在开始之前，请确保你的电脑已安装：
- Node.js (推荐 LTS 版本)
- Git（用于版本控制和代码上传）

打开终端，输入以下命令验证安装结果：
```bash
node -v && git --version
```
如果出现版本号，说明环境就绪。如果没有安装，可以前往官网下载，或者参考文末的常见问题。

 第二步：快速安装 Hexo

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
hexo s
```

浏览器访问 `http://localhost:4000`，看到默认页面即表示本地运行成功。此时你已完成了 Hexo 的初始化安装，接下来我们把它部署到线上。

 第三步：部署到 GitHub Pages（重点）

这一步骤是关键词覆盖最核心的部分：创建仓库并推送代码。

1. 在 GitHub 上新建一个仓库，仓库名格式必须为：`你的用户名.github.io`
2. 修改站点根目录下的 `_config.yml` 文件，找到 `deploy` 字段，填入你的仓库地址。
3. 安装部署插件并推送：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo g && hexo d
```

浏览器输入 `https://你的用户名.github.io`，看到博客上线的那一刻，你会觉得一切都值得。

 第四步：优化与美化

搭建完成只是开始，为了让你持续创作，这里提供几条高价值建议：
- 更换主题：推荐 `NexT` 或 `Fluid`，配置简单且支持响应式布局。
- 绑定自定义域名：在仓库设置中启用，并将 CNAME 记录指向 GitHub。
- 接入评论系统：比如 Giscus、Valine，增强与读者的互动性。

 你想知道的问题

Q: 文章如何发布？
在 `source/_posts` 目录下新建 `.md` 文件，写完后执行 `hexo g && hexo d` 即可。

Q: 部署总是失败怎么办？
检查仓库名是否匹配，并确认 `_config.yml` 中 deploy 的 repo 地址是否为 HTTPS 格式。

 行动起来

搭建博客最大的阻碍从来不是技术，而是开始的第一步。如果你在搭建过程中遇到任何问题，欢迎在评论区 留言交流，或者点赞收藏本文，方便以后查阅。

你的第一个 Git 页面，可能从这里开始。

相关推荐：

https://github.com/gibsonbrittany8713/clmhvk/blob/main/ch%E1%BB%8Di%20g%C3%A0%20%F0%9F%90%94%20%EF%BC%9A%E6%91%A9%E9%91%AB%E7%BD%91%E5%9D%80app_%E6%BE%88%E9%A2%97%E7%9F%AB%E8%A1%94%E5%BE%BDvonhn.md

<img src="https://i.postimg.cc/6qRcdLZg/moxin-00004.png" />

相关推荐：

https://github.com/gibsonbrittany8713/clmhvk/commit/f1ce4885136f8b876ec0f96dd28946b10bb5db5f

<img src="https://i.postimg.cc/c18FyZz9/moxin-00011.png" />
相关推荐：

https://github.com/linanthony2740/tbdexg/blob/main/Th%E1%BB%83%20thao%20%E2%9A%BD%EF%B8%8F%EF%BC%9A%E6%91%A9%E9%91%AB%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0_%E7%AA%83%E8%9B%8A%E5%B7%B4%E7%B4%A0%E6%99%83flfmg.md

<img src="https://i.postimg.cc/VsbKQ1h2/moxin-00013.png" />
相关推荐：

https://github.com/linanthony2740/tbdexg/commit/6573f1dae26017bb2b7c1aa8262b21e48f00e5b7

<img src="https://i.postimg.cc/T2WtMGSG/moxin-00014.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
