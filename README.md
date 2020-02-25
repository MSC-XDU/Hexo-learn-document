# Hexo-blog-learning-doc

本教程以使用`Hexo`完成博客搭建这个简单任务为主线，涉及git与GitHub的使用、域名解析记录、CDN（以Cloudflare为例）、Node.js、markdown语法、dockerfile编写、CI/CD工具(以GitHub actions为例)等内容。期待在完成博客搭建这个小任务的过程中涉猎一些常用工具和学习一些基本技能。

## 完成本教程你将获得什么？

一个带有评论功能的、能够完成基本在线编辑功能的、有自定义域名的、配置CDN加速的、具有`rss`生成功能的基于`Hexo`的属于你自己的、几乎免费（也可以完全免费）的个人博客。

**完成较好的同学可以获得微软周边小礼品**

注：自定义域名那个在国内需要备案，CDN使用国内产品的话同样需要备案。

## 面向对象

内容设计较为基础简单，面向群体主要有：

1. 想自己搭建博客的(废话)
2. 想简单了解一下web的
3. 想学习GitHub和git的
4. 想简单了解教程开头那些涉及到的内容都是啥东西的
5. 想来玩的

## 主要任务目录

1. 学习了解`GitHub`并开始本教程
2. 完成Step2开始前的准备部分，如果遇到问题在本仓库`issue`中提出
3. 安装并完成`hexo`的最基本配置
4. 使用`GitHub pages`发布你的内容
5. 使用`GitHub actions`自动化博客的构建过程
6. 为你的博客添加自定义域名、配置CDN加速
7. 挑选博客主题、了解hexo的工作机制、简单修改主题、添加rss生成
8. 如果愿意的话将你的博客和rss添加到[MSCer RSS列表](https://github.com/MSC-XDU/MSCer_blog_rss)

## Pre-Step

如果你听了本学期第一次技术沙龙的建议申请了学生邮箱的话，强烈建议在开始前去申请[GitHub education pack](https://education.github.com/benefits)

本文涉及的所有服务均可在pack中找到免费额度，而且**不需要**信用卡

申请需要你的学生邮箱以及学生证照片，另外上传照片时**一定不要**用梯子，会导致ip地址偏离学校太多审核失败

另外，你的学生邮箱能为你提供非常多的学生优惠，不过这不是本文的内容，可以参考知乎的[这篇文章](https://zhuanlan.zhihu.com/p/22804091)

## Step1-1 了解`git`

### 基本内容(为顺利完成本教程必须掌握的内容)：

首先请安装`git` 官方下载过慢的话可以[从这里下载](https://myblog-1254913510.file.myqcloud.com/Git-2.25.1-64-bit.exe)

粗略阅读[本篇](https://www.bootcss.com/p/git-guide/)文章,没看懂的部分跳过即可，只要弄明白以下几个命令如何使用即可:
1. `git clone`
2. `git add`
3. `git commit`
4. `git push`
5. `git status`


### 基础扩展(日常使用经常用到的内容)：
1. 阅读[这篇微信推文](https://mp.weixin.qq.com/s/l5f1299fxOuMF9ZZ4wA17A)
2. 弄明白下面几个命令:
   1. `git checkout`
   2. `git log`
   3. `git reflog`
   4. `git merge`
   5. `git pull`
3. 解答`issue #1`中的问题(直接回复即可)


### 进阶阅读材料：
1. 关于`git`原理 公众号文章[通过 .git 目录深入理解 Git](https://mp.weixin.qq.com/s/NZ3TMMEjawIeAVCXGXkKkg)



## Step1-2 了解`github`并完成签到任务

我觉得如果你完成了`Step1-1-基本内容`那部分，那么接下来最好的方式就是尝试（随便乱点一通看看发生什么 逃）

1. 请在自己的账号下面(如果没有请注册一个，这是下面必须的)创建一个仓库，不用纠结名字，然后尝试：
   1. 用上面的git知识向你的仓库添加一些东西
   2. 给自己的仓库提交一个issue
   3. 尝试删除自己的仓库
   4. 其它你想做的任何事情
2. 我也给你准备了一个[仓库](https://github.com/MSC-XDU/Just-try-to-use-github)你可以尝试:
   1. `fork`它并修改一些东西然后提交一个`Pull Request`
   2. 给这个交一个issue
   3. 其它你想做的任何事情

然后请完成**签到任务**：
`fork`本仓库，把你`fork`的把版本clone到本地，在`Registration-list.md`文件里面添加你的名字或昵称，`commit`并`push`，最后给本仓库提交一个`Pull request`

建议填写QQ昵称我会根据本教程的完成情况，在返校后**发放一些微软周边小礼品**





