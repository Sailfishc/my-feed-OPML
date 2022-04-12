**<p align="center">[My Feedly OPML](https://github.com/Sailfishc/my-feed-OPML)</p>**
====

## 前言

**分享我订阅的一些 Blog 和 Newsletter，每天自动同步我 Feedly 上的订阅源，✅ 代表能正常订阅，❌ 代表暂无法订阅（对于无法订阅的 feed，支持 Telegram Bot、Email、Server酱等推送工具提醒更新），**[opml 下载地址](https://github.com/Sailfishc/my-feed-OPML/releases/download/latest/feed.opml)

**最新更新时间（北京时间）：2022-04-12 08:33:05**

## 如何使用

- fork 本仓库

- 在 `Settings --> Secrets --> Actions` 下新增如下的几个 secrets：
   - **FEEDLY_TOKEN**：**必须**，你的 Feedly token，访问 [https://feedly.com/v3/auth/dev](https://feedly.com/v3/auth/dev)，创建一个开发者 token
   - **G_TOKEN**：**必须**，你的 [Github Token](https://github.com/settings/tokens/new)，scope 不知道选啥，就全部勾上，然后拷贝生成的 token
   - **TG_CHAT_ID**：可选，你的 Telegram user id，关注机器人 [@getuseridbot](https://t.me/getuseridbot) 即可获取
   - **TG_TOKEN**：可选，你的用于接收通知的 telegram bot 的 token，如何创建 Telegram Bot，见搜索引擎
   - **EMAIL**：可选，你的用于接收通知的邮箱
   - **EMAIL_PASS**：可选，你的邮箱授权密码
   - **EMAIL_HOST**：可选，邮箱协议
   - **SC_KEY**：可选，Server酱的 secret key

- 修改 `feedly_opml_import.yml`，修改如下的配置项为你自己的 Github userName 和 Email：
   ```yml
   env:
    GITHUB_NAME: superleeyom
    GITHUB_EMAIL: 635709492@qq.com
   ```
  
- 然后 `Actions --> Workflows --> FeedlyOpmlImportApplication --> Run workflow`，手动触发任务


Programming
-----------
- [✅ Javarevisited](http://javarevisited.blogspot.com/)：[feed](http://javarevisited.blogspot.com/feeds/posts/default)
- [✅ Stack Overflow Blog](https://stackoverflow.blog)：[feed](http://blog.stackoverflow.com/feed/)
- [✅ Scott Hanselman's Blog](https://www.hanselman.com/blog/)：[feed](http://feeds.feedburner.com/ScottHanselman)
- [✅ High Scalability](http://highscalability.com/blog/)：[feed](http://feeds.feedburner.com/HighScalability)
- [✅ Engineering at Meta](https://engineering.fb.com)：[feed](https://code.facebook.com/posts/rss)
- [✅ You’ve Been Haacked](http://haacked.com/)：[feed](http://feeds.haacked.com/haacked/)
- [❌ Google Developers ](http://developers.googleblog.com/)：[feed](http://code.google.com/feeds/updates.xml)
- [✅ Netflix TechBlog](https://netflixtechblog.com?source=rss----2615bd06b42e---4)：[feed](http://techblog.netflix.com/feeds/posts/default)
- [✅ Coding Horror](https://blog.codinghorror.com/)：[feed](http://feeds.feedburner.com/codinghorror/)
- [✅ Code as Craft](https://codeascraft.com)：[feed](http://codeascraft.etsy.com/feed/)
- [✅ LinkedIn Engineering](https://engineering.linkedin.com/blog.rss.html)：[feed](https://engineering.linkedin.com/blog.rss)
- [✅ The Clean Code Blog](http://blog.cleancoder.com/)：[feed](http://blog.cleancoder.com/atom.xml)
- [✅ The IntelliJ IDEA Blog : The Capable & Ergonomic IDE for JVM languages by JetBrains | The JetBrains Blog](https://blog.jetbrains.com)：[feed](http://blogs.jetbrains.com/idea/feed/)
- [❌ CodeBetter.Com Posts](http://codebetter.com)：[feed](http://codebetter.com/blogs/MainFeed.aspx)
- [✅ AWS Database Blog](https://aws.amazon.com/blogs/database/)：[feed](https://aws.amazon.com/blogs/database/feed/)
- [✅ Engineering – The GitHub Blog](https://github.blog)：[feed](http://githubengineering.com/atom.xml)
- [✅ The Go Blog](http://blog.golang.org/)：[feed](http://blog.golang.org/feeds/posts/default)

Tech
----
- [✅ Praxis](https://medium.com/praxis-blog?source=rss----43a173dea401---4)：[feed](https://medium.com/feed/forte-labs)
- [✅ 王垠的博客 - 当然我在扯淡](https://www.yinwang.org)：[feed](https://rsshub.app/blogs/wangyin)
- [✅ Martin Fowler](https://martinfowler.com)：[feed](http://martinfowler.com/bliki/bliki.atom)
- [✅ null program](https://nullprogram.com)：[feed](http://nullprogram.com/feed/)
- [✅ Eli Bendersky's website](https://eli.thegreenplace.net/)：[feed](http://eli.thegreenplace.net/feed/)
- [✅ Marek's idea of the day](https://idea.popcount.org)：[feed](https://idea.popcount.org/rss.xml)
- [✅ Google Developers](https://medium.com/google-developers?source=rss----2e5ce7f173a5---4)：[feed](https://medium.com/feed/google-developers)
- [✅ AWS Architecture Blog](https://aws.amazon.com/blogs/architecture/)：[feed](http://www.awsarchitectureblog.com/atom.xml)
- [✅ Accidentally Quadratic](https://accidentallyquadratic.tumblr.com/)：[feed](https://accidentallyquadratic.tumblr.com/rss)
- [✅ Uber Engineering Blog](https://eng.uber.com)：[feed](https://eng.uber.com/feed/)
- [✅ fuzzy notepad](https://eev.ee/)：[feed](http://me.veekun.com/atom.xml)
- [✅ 卡瓦邦噶！](https://www.kawabangga.com)：[feed](http://www.kawabangga.com/feed)
- [❌ Kotlin Expertise Blog](https://kotlinexpertise.com)：[feed](https://blog.simon-wirtz.de/feed/)
- [✅ AWS News Blog](https://aws.amazon.com/blogs/aws/)：[feed](http://aws.typepad.com/aws/atom.xml)
- [✅ Coding Horror](https://blog.codinghorror.com/)：[feed](https://blog.codinghorror.com/rss/)
- [✅ Superorganizers](https://superorganizers.every.to)：[feed](https://superorganizers.substack.com/feed/)
- [✅ Philipp Hauer's Blog](https://phauer.com)：[feed](http://blog.philipphauer.de/feed/)
- [✅ Dropbox Tech Blog](https://dropboxtechblog.wordpress.com)：[feed](https://tech.dropbox.com/feed/)
- [✅ Thoughtworks Technology Podcast](https://www.thoughtworks.com/podcasts)：[feed](http://feeds.soundcloud.com/users/soundcloud:users:94605026/sounds.rss)
- [✅ Reimu's blog](https://blog.k8s.li/)：[feed](https://blog.502.li/feed)
- [✅ Comments for Joel on Software](https://www.joelonsoftware.com)：[feed](https://www.joelonsoftware.com/comments/feed/)
- [✅ Martin Fowler](https://martinfowler.com)：[feed](https://martinfowler.com/feed.atom)
- [✅ programming is terrible](https://programmingisterrible.com/)：[feed](https://programmingisterrible.com/rss)
- [✅ Evan Jones - Software Engineer | Computer Scientist](https://www.evanjones.ca/)：[feed](http://www.evanjones.ca/index.rss)
- [✅ Google Open Source Blog](http://opensource.googleblog.com/)：[feed](http://google-opensource.blogspot.com/feeds/posts/default)
- [✅ The Cloudflare Blog](https://blog.cloudflare.com/)：[feed](http://blog.cloudflare.com/rss.xml)
- [✅ Stories by 1v1 lol unblocked games play 1v1 lol unblocked on Medium](https://medium.com/@steve.yegge?source=rss-45e3a3f3166------2)：[feed](https://medium.com/feed/@steve.yegge)
- [✅ Enterprise Craftsmanship](https://enterprisecraftsmanship.com/)：[feed](https://enterprisecraftsmanship.com/index.xml)
- [✅ Updates](https://developers.google.com/web/updates/?utm_source=feed&utm_medium=feed&utm_campaign=updates_feed)：[feed](https://developers.google.com/web/updates/rss.xml)
- [✅ Blogold - Roy Osherove](https://osherove.com/blog/)：[feed](http://feeds.feedburner.com/Iserializable)

Design
------
github
------
- [✅ biezhi's GitHub repositories](https://github.com/biezhi)：[feed](https://sail-rss-hub.herokuapp.com/github/repos/biezhi)

Coder
-----
Youtube
-------
- [✅ Optimum Tech](https://www.youtube.com/channel/UCRYOj4DmyxhBVrdvbsUwmAA)：[feed](https://www.youtube.com/feeds/videos.xml?channel_id=UCRYOj4DmyxhBVrdvbsUwmAA)
- [✅ Techno Dad Life (uploads) on YouTube](https://www.youtube.com/playlist?list=UUX2Vhc0LIzSS9aMzhGFZ7PA)：[feed](https://www.youtube.com/playlist?list=UUX2Vhc0LIzSS9aMzhGFZ7PA)
- [✅ Jango Y (uploads) on YouTube](https://www.youtube.com/playlist?list=UUUrJvRXzVBOYtHBs9fDnJEw)：[feed](https://www.youtube.com/playlist?list=UUUrJvRXzVBOYtHBs9fDnJEw)
- [✅ EngFluent](https://www.youtube.com/channel/UCbW3Pcp-8Gz9QMKALqlY5nQ)：[feed](https://www.youtube.com/feeds/videos.xml?channel_id=UCbW3Pcp-8Gz9QMKALqlY5nQ)
- [✅ DesignCode (Webflow Free Course) on YouTube](https://www.youtube.com/playlist?list=PLDaHCLWmCcQKWhjHSJClUoldk4465gf6R)：[feed](https://www.youtube.com/playlist?list=PLDaHCLWmCcQKWhjHSJClUoldk4465gf6R)
- [✅ Principles by Ray Dalio (Kissinger and Dalio on Chinese-American Relations) on YouTube](https://www.youtube.com/playlist?list=PLykIL_1_MFWlMnsHknYc4HUeRvb3ak7MZ)：[feed](https://www.youtube.com/playlist?list=PLykIL_1_MFWlMnsHknYc4HUeRvb3ak7MZ)

Twitter
-------
技术
--
- [✅ CodingLabs](http://blog.codinglabs.org)：[feed](http://blog.codinglabs.org/rss.xml)
- [✅ Martin Kleppmann's blog](http://martin.kleppmann.com/)：[feed](https://feeds.feedburner.com/martinkl)
- [✅ Thoughtworks洞见](https://insights.thoughtworks.cn)：[feed](http://insights.thoughtworks.cn/feed/)
- [❌ http://www.yinwang.org](http://www.yinwang.org/)：[feed](http://www.yinwang.org/atom.xml)
- [✅ Rebornix, homepage and blog belongs to Peng Lv.](http://www.rebornix.com)：[feed](https://rebornix.com/atom)
- [✅ "地瓜哥"博客网](https://www.diguage.com/)：[feed](https://www.diguage.com/index.xml)
- [✅ 徐靖峰|个人博客](https://lexburner.github.io/)：[feed](https://www.cnkirito.moe/atom.xml)
- [✅ Hawstein's Blog](http://hawstein.com/)：[feed](http://hawstein.com/atom.xml)
- [✅ Antirez weblog](http://antirez.com)：[feed](http://antirez.com/rss)
- [✅ iTimothy](https://xiaozhou.net/)：[feed](http://www.xiaozhou.net/atom.xml)
- [✅ Skywind Inside](http://www.skywind.me/blog)：[feed](http://www.skywind.me/blog/feed)
- [✅ 美团技术团队](https://tech.meituan.com/feed/)：[feed](https://tech.meituan.com/feed/)
- [✅ 小胡子哥的个人网站](http://www.barretlee.com/)：[feed](http://barretlee.com/rss2.xml)
- [✅ 「已注销」的知乎动态](https://www.zhihu.com/people/in-nek/activities)：[feed]( https://rsshub.app/zhihu/people/activities/in-nek)
- [✅ Jack Liu博客-RSS订阅](http://www.jack-liu.com/)：[feed](http://www.jack-liu.com/rss.php)
- [✅ 阮一峰的网络日志](http://www.ruanyifeng.com/blog/)：[feed](http://www.ruanyifeng.com/blog/atom.xml)
- [✅ Joe’s Blog](https://hijiangtao.github.io/)：[feed](https://hijiangtao.github.io/feed.xml)
- [❌ 代码家](https://daimajia.com)：[feed](http://blog.daimajia.com/feed/)
- [❌ 谷歌开发者中文博客](https://googledeveloperschina.blogspot.com/)：[feed](http://feeds.googleblog.cn/GoogleDevelopersChineseLanguageBlog)
- [✅ Coding Husky](https://ericfu.me/)：[feed](https://ericfu.me/atom.xml)
- [✅ 云风的 BLOG](https://blog.codingnow.com/)：[feed](http://blog.codingnow.com/atom.xml)
- [✅ 酷 壳 – CoolShell](https://coolshell.cn)：[feed](http://coolshell.cn/feed)
- [✅ 面向信仰编程](https://draveness.me/)：[feed](https://draveness.me/feed.xml)
- [✅ Jiajun的编程随想](https://jiajunhuang.com)：[feed](https://jiajunhuang.com/rss)
- [❌ 橙小张的博客](https://blog.sailfishc.cn/)：[feed](https://blog.sailfishc.cn/index.xml)
- [❌ 唐巧的博客](https://blog.devtang.com/)：[feed](http://www.devtang.com/atom.xml)

English
-------
- [✅ EngFluent](https://engfluent.com)：[feed](https://engfluent.com/feed/)

LeetCode
--------
- [✅ Hua Hua](https://www.youtube.com/channel/UC5xDNEcvb1vgw3lE21Ack2Q)：[feed](https://www.youtube.com/feeds/videos.xml?channel_id=UC5xDNEcvb1vgw3lE21Ack2Q)

资讯头条
----
- [✅ 代码时间](http://codetimecn.com)：[feed](http://codetimecn.com/podcast.rss)

