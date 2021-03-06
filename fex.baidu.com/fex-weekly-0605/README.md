# 百度技术周刊 第0605期

    周刊地址：[http://fex.baidu.com/blog/2017/06/fex-weekly-05/](http://fex.baidu.com/blog/2017/06/fex-weekly-05/)

## 深阅读

### [Node v8.0.0](https://nodejs.org/en/blog/release/v8.0.0/)

 这次升级附带 [npm v5.0.0](http://blog.npmjs.org/post/161081169345/v500), V8 引擎 v5.8, [Node.js API (N-API)](https://medium.com/@nodejs/n-api-next-generation-node-js-apis-for-native-modules-169af5235b06), Async Hooks… 等，都进行了升级。

* [Node8中重要的升级和特性](https://blog.risingstack.com/important-features-fixes-node-js-version-8/)
* [Node8必知必会](http://codingsans.com/blog/node-8)
* [Node8调试和本地模块生态系统的提升](https://medium.com/@nodejs/node-js-8-big-improvements-for-the-debugging-and-native-module-ecosystem-58454861f2fc).

### [WebAssembly: Mozilla Won](http://robert.ocallahan.org/2017/06/webassembly-mozilla-won.html)

    Mozilla staff are being very diplomatic and restrained by allowing WebAssembly to be portrayed as a compromise between the approaches of asm.js and PNaCl. They have good reasons for being so, but I can be a bit less restrained. asm.js and PNaCl represented quite different visions for how C/C++ code should be supported on the Web, and I think WebAssembly is a big victory for asm.js and Mozilla’s vision. 另附：[Chromium - Goodbye PNaCl, Hello WebAssembly](https://blog.chromium.org/2017/05/goodbye-pnacl-hello-webassembly.html)、[What WebAssembly means for React](https://www.youtube.com/watch?v=3GHJ4cbxsVQ)


### [Yarn determinism](https://yarnpkg.com/blog/2017/05/31/determinism/)

    One of the claims that Yarn makes is that it makes your package management “deterministic”. But what exactly does this mean? This blog post highlights how both Yarn and npm 5 are deterministic, but differ in the exact guarantees they provide and the tradeoffs they have chosen. Determinism in the context of JavaScript package management is defined as always getting the exact same node_modules folder given a package.json and companion lock file.

### [Key Abstractions for IoT-Oriented Software Engineering](https://www.infoq.com/articles/iot-key-abstractions)

    The current design of IoT systems sports a number of common features such as the “things” they want to connect, the software infrastructure that connects them, and the services and applications that allow to regulate and configure the system.The first abstraction that is useful in the defintion of an IoT system is that of system stakeholders, including local and global managers, and users.

### [Into the Great Unknown — Migrating from Mocha to Jest](https://ebaytech.berlin/into-the-great-unknown-migrating-from-mocha-to-jest-3baced083c7e)

    How to migrate an existing code base to Jest? Let’s put on our sun helmets, zip up our sturdy boots and prepare to venture into the great unknown!

### [HTTP/2推送技术之难，真的远超我们想象](https://mp.weixin.qq.com/s?__biz=MzA5Nzc4OTA1Mw==&mid=2659599304&idx=1&sn=12d2da3dc46c50e829f6f959237c41ff)

    HTTP/2 推送远比我最初想象中更复杂，也更底层，但最让我措手不及的地方在于，这种技术在不同浏览器上的表现竟然有这么大的差别，本来我还觉得这技术已经足够成熟，可以在生产环境中使用了。本文并不是那种认为“HTTP/2 推送一无是处”的吐槽文。我觉得 HTTP/2 推送真的很强大，以后还会更加完善，但并不算能解决所有问题的万灵药。

### [回顾我的600篇技术笔记](https://mp.weixin.qq.com/s?__biz=MzU5OTAxOTE4MA==&mid=2247483673&idx=1&sn=2668eee091d3ebe040f199d417c08a30)

    一位码农的心得体会，挺实在的，赞：“节制无穷尽的求知欲，从实践出发求知；不要闭门造车，好东西要分享”。

### [我对知乎前端相关问题的十问十答](http://www.zhangxinxu.com/wordpress/2017/06/ten-question-about-frontend-zhihu/)

    CSS 专家张鑫旭对前端的理解。

### [Instagram 在 PyCon 2017 的演讲摘要](http://www.zlovezl.cn/articles/instagram-pycon-2017/)

    Instagram 的总注册用户达到 30 亿，月活用户超过 7 亿。而令人吃惊的是，这么高的访问量背后，竟完全是由以速度慢著称的 Python + Django 支撑。在 [Python 2017](https://us.pycon.org/2017/) 上，Instagram 的工程师们带来了一个有关 Python 在 Instagram 的主题演讲，同时还分享了 Instagram 如何将整个项目运行环境升级到 Python 3 的故事。

### [DNS Infrastructure at GitHub](https://githubengineering.com/dns-infrastructure-at-github/)

    At GitHub we recently revamped how we do DNS from the ground up. This included both how we interact with external DNS providers and how we serve records internally to our hosts. To do this, we had to design and build a new DNS infrastructure that could scale with GitHub’s growth and across many data centers.

### [Flannel: An Application-Level Edge Cache to Make Slack Scale](https://slack.engineering/flannel-an-application-level-edge-cache-to-make-slack-scale-b8a6400e2f6b)

    Slack was architected around the goal of keeping teams of hundreds of people connected, and as teams have gotten larger, our initial techniques for loading and maintaining data have not scaled. To address that, we created a system that lazily loads data on demand and answers queries as you go.

### [Animating Single Div Art](https://css-tricks.com/animating-single-div-art/)

    When you dig deep with your tools, it is amazing what you can create out of the most basic of HTML. I have been constantly impressed with “Single Div Art” by Lynn Fisher and others where you take a single generic <div> to create a beautiful cactus, Alamo, or panda.

### [11 things I learned reading the flexbox spec](https://hackernoon.com/11-things-i-learned-reading-the-flexbox-spec-5f0c799c776b)

    A run through some of the ‘good bits’ of the CSS Flexible Box Layout specification.

### [A Love Letter to CSS](http://developer.telerik.com/topics/web-development/love-letter-css/)

    Today I’m going to try to convince you that not only is CSS one of the best technologies you use on a day-to-day basis, not only is CSS incredibly well designed, but that you should be thankful—thankful!—each and every time you open a .css file. My argument is relatively simple: creating a comprehensive styling mechanism for building complex user interfaces is startlingly hard, and every alternative to CSS is much worse. Like, it’s not even close.

## 新鲜货

### [Announcing an open data set on the open source community](https://github.com/blog/2372-announcing-an-open-data-set-on-the-open-source-community)

    We just released [an open data set](http://opensourcesurvey.org/2017/) for the open source community, researchers, and curious data wonks to study. The data includes responses from 5,500 open source participants randomly sampled from over 3,800 projects on GitHub.com and over 500 sourced from communities that work on other platforms. Altogether, the data represents some of the most comprehensive and high-quality data on the open source community to date.

### [Best JavaScript Frameworks, Libraries and Tools to use in 2017](https://www.sitepoint.com/top-javascript-frameworks-libraries-tools-use/)

    This article endeavors to explain the basics and rudimentary differences between the most popular client-side JavaScript frameworks, libraries, and tools. Whether they are “best” for you is another question. Choose something and stick with it for a while. Just be aware your favorite option will be superseded by something “better” no matter what you select!

### [npm Pride 2017 Shirts](http://blog.npmjs.org/post/161303607370/npm-pride-2017)

    不知国内能不能买。

### [2017互联网女皇报告中文完整版](http://tech.qq.com/a/20170601/009038.htm#p=1)

    有“互联网女皇”之称的玛丽·米克尔在美国Code大会上发布了2017年的互联网趋势报告，可关注下行业发展趋势。

### [TypeScript support in Electron](https://electron.atom.io/blog/2017/06/01/typescript)

    The electron npm package now includes a TypeScript definition file that provides detailed annotations of the entire Electron API. These annotation can improve your Electron development experience even if you’re writing vanilla JavaScript. Just npm install electron to get up-to-date Electron typings in your project.

### [Visualize data instantly with machine learning in Google Sheets](https://www.blog.google/products/g-suite/visualize-data-instantly-machine-learning-google-sheets/)

    Explore in Sheets, powered by machine learning, helps teams gain insights from data, instantly. Simply ask questions—in words, not formulas—to quickly analyze your data.

### [What’s New In DevTools (Chrome 60)](https://developers.google.com/web/updates/2017/05/devtools-release-notes)

    Here’s what’s new in DevTools in Chrome 60. You can check what version of Chrome you’re running at chrome://version.

### [vis.js](http://visjs.org/)

    A dynamic, browser based visualization library. The library is designed to be easy to use, to handle large amounts of dynamic data, and to enable manipulation of and interaction with the data. The library consists of the components DataSet, Timeline, Network, Graph2d and Graph3d.

### [Storybook 3.0](https://medium.com/storybookjs/announcing-storybook-3-0-329748b8f4cd)

    [Storybook](https://storybook.js.org/) is a development environment for UI components. It allows you to browse a component library, view the different states of each component, and interactively develop and test components. 3.0 brings long-anticipated webpack2 support, create-react-native-app support, flexible snapshot testing, and a host of bugfixes and enhancements.

### [Meteor 1.5](https://blog.meteor.com/announcing-meteor-1-5-b82be66571bb)    
    Dynamic import(…), exact code splitting, immutable module caching, and bundle analysis tools

### [Muuri](https://haltu.github.io/muuri/)

    Responsive, sortable, filterable and draggable grid layouts

### [Awesome CSS in JS](https://github.com/tuchk4/awesome-css-in-js)

    A collection of awesome things regarding to CSS in JS approach

### [Popper.js](https://popper.js.org/)

    A kickass library to manage your poppers. A popper is an element on the screen which “pops out” from the natural flow of your application.

### [Picodom](https://github.com/picodom/picodom)

    Picodom is a 1kb Virtual DOM builder and patch algorithm.

## [Browse faster and safer with Brave](https://brave.com/)

    The new Brave browser automatically blocks ads and trackers, making it faster and safer than your current browser.

### [W3C Performance Specifications](http://www.standardista.com/w3c-performance-specifications/)

    Here are some of the W3C’s web performance specifications.

### [Web Design Museum](https://www.webdesignmuseum.org/)

    The museum exhibits over 800 carefully selected and sorted web sites that show web design trends between the years 1996 and 2005.

### [Data GIF Maker - 一款数据 GIF 制作工具](http://www.geekpark.net/topics/219627)

    News Lab 推出了一款数据 GIF 制作工具——Data GIF Maker。该工具可以使某些动态性的数据更加直观地进行对比，例如，你可以使用这款工具在不同的时间节点上，查看两支球队的夺冠支持率，但是它仅能用于两种不同主题对比的数据统计。

### [Game Programming Patterns](http://gameprogrammingpatterns.com/)

    I’m here to help! Game Programming Patterns is a collection of patterns I found in games that make code cleaner, easier to understand, and faster. This is the book I wish I had when I started making games, and now I want you to have it.

## 产品及其它

### [腾讯社交办公产品 TIM](http://36kr.com/p/5078074.html)

    TIM没有一般企业内部交流软件的标配——企业组织架构。它似乎只是在QQ的基础上，做了一些定制化的功能，并没有革命性的改变。这似乎是腾讯进军办公场景的一条尝试路径。另附：[腾讯社交办公产品 TIM：不做另一个企业微信](http://www.geekpark.net/topics/219664)。

### [傅盛创业方法论之CEO系列全集](https://mp.weixin.qq.com/s?__biz=MjM5NjgzMzkwMQ==&mid=2653646337&idx=1&sn=548060db00705b85e236f18545d0ea8b)

    创业要解决的，就是开放性的环境下，找到方向。CEO的核心是树立一个简单可行的目标，树立一个越简单越聚焦的目标越好。尽管这个目标，可能在过程中，不断变化。创业过程中，开放式变成封闭式问题的转换能力，是我们真正最需要的能力的核心。当目标足够简单，就会足够狭窄，足够狭窄会带来什么？就是你如此投入以后，别人没有机会赶超，因为已经没办法再超越了。管理的本质就是树立一个核心的业务，让这个业务带着所有的员工和组织构架往前走，而不是去构建一个四平八稳的组织，让所有的业务井井有条。

### [从顺丰大战阿里，看巨头的“舒服恶”和“舒服死”](https://mp.weixin.qq.com/s?__biz=MjM5NzYxMzk4MQ==&mid=2649331114&idx=1&sn=a07400fe7db5e2f396916e039b2d6428)

    能力越大，责任越大，要求越高。曾经，腾讯在那个“艰难的决定”之后，痛改前非，拥抱开放，重建生态，获得了行业的尊重。阿里呢？

### [技术人转型怎样转变思路与处事之道](https://mp.weixin.qq.com/s?__biz=MjM5MDE0Mjc4MA==&mid=2650996346&idx=1&sn=e0998b024f852f966d3d59be7969f2dd)

    本文作者将从自己的工作经历出发，从工程师择业的角度，与观众产生共鸣，从大公司到创业公司，需要转变的思路与做事情的方法，有原则性的东西，也有真实案例与身边的故事，还会穿插一些工程师的软技能。

### [互联网世界的「阿甘正传」 - Meduim 创始人 Ev Williams](https://mp.weixin.qq.com/s/UMujS8y-d2MfwKH_ZB8jAw)

    网络，是指页面由HTML或者CSS编写。而自由，是指所有人都可以访问，没有特权页面，没有付费要求，没有用户账号。最重要的是，这个开放网络是自由的——就像语言和意识一样自由。自由并不是一项权利，更像是一种技术上不可分割的事实。这种自由的终极意义：是创造一个最好、最酷的，以往媒体从来没能创造的，由全人类共同编写的图书所组成的图书馆。这个网络将包含着小说、报纸、科学期刊，和其它全部的东西。每个人都能为它写作，每个人都能来阅读它。它是待办事项清单、日记本、文学作品，也是力量强大到甚至能够阻止战争的沟通工具。