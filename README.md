# 基于项目的学习
> [FROM](https://github.com/practical-tutorials/project-based-learning),`同步保持更新`

[![Gitter](https://badges.gitter.im/practical-tutorials/community.svg)](https://gitter.im/practical-tutorials/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

这是一个编程教程列表，通过这些教程，初学者可以学习如何从零开始构建一个应用程序。这些教程按照不同的主要编程语言进行划分。教程可能涉及多种技术和语言。

## 参与贡献

只需 fork 这个仓库。请参考 [CONTRIBUTING.md](CONTRIBUTING.md) 了解贡献指南。

## 目录：

- [C#](#c)
- [C/C++](#cc)
- [Clojure](#clojure)
- [Dart](#dart)
- [Elixir](#elixir)
- [Erlang](#erlang)
- [F#](#f)
- [Go](#go)
- [Haskell](#haskell)
- [HTML/CSS](#html-and-css)
- [Java](#java)
- [JavaScript](#javascript)
- [Kotlin](#kotlin)
- [Lua](#lua)
- [OCaml](#ocaml)
- [PHP](#php)
- [Python](#python)
- [R](#r)
- [Ruby](#ruby)
- [Rust](#rust)
- [Scala](#scala)
- [Swift](#swift)
- [其他资源](#additional-resources)

## C/C++:

- [从头构建解释器](http://www.craftinginterpreters.com/)（第14章以后使用 C 编写）
- [内存分配器 101 - 编写一个简单的内存分配器](https://arjunsreedharan.org/post/148675821737/memory-allocators-101-write-a-simple-memory)
- [用 C 编写一个 Shell](https://brennan.io/2015/01/16/write-a-shell-in-c/)
- [编写一个 FUSE 文件系统](https://www.cs.nmsu.edu/~pfeiffer/fuse-tutorial/)
- [构建你自己的文本编辑器](http://viewsourcecode.org/snaptoken/kilo/)
- [构建你自己的 Lisp](http://www.buildyourownlisp.com/)
- [如何用 C 编写一个 NES 游戏](https://nesdoug.com/)
- [从零开始编写操作系统](https://github.com/tuhdo/os01)
- [如何从零开始创建一个操作系统](https://github.com/cfenollosa/os-tutorial)
- [构建一个 CHIP-8 模拟器](https://austinmorlan.com/posts/chip8_emulator/)
- [用 C++ 和 SDL 开始游戏编程](http://lazyfoo.net/tutorials/SDL/)
- [实现一个键值存储](http://codecapsule.com/2012/11/07/ikvs-implementing-a-key-value-store-table-of-contents/)
- 微型 3D 图形项目
  - [Tiny Renderer 或者 OpenGL 是如何工作的：500 行代码的软件渲染](https://github.com/ssloy/tinyrenderer/wiki)
  - [256 行纯 C++ 理解光线追踪](https://github.com/ssloy/tinyraytracer/wiki)
  - [180 行 C++：一个周末的老式 FPS](https://github.com/ssloy/tinykaboom/wiki)
  - [486 行 C++：一个周末的老式射击游戏](https://github.com/ssloy/tinyraycaster/wiki)
- 使用 C++ 写一个最小的 x86-64 JIT 编译器
  - [第 1 部分](https://solarianprogrammer.com/2018/01/10/writing-minimal-x86-64-jit-compiler-cpp/)
  - [第 2 部分](https://solarianprogrammer.com/2018/01/12/writing-minimal-x86-64-jit-compiler-cpp-part-2/)
- [为 C++ 构建一个实时代码重新加载库](http://howistart.org/posts/cpp/1/index.html)
- [用 C 编写一个哈希表](https://github.com/jamesroutley/write-a-hash-table)
- [让我们构建一个简单的数据库](https://cstack.github.io/db_tutorial/)
- [让我们编写一个内核](http://arjunsreedharan.org/post/82710718100/kernel-101-lets-write-a-kernel)
- [用 C 编写一个引导程序](http://3zanders.co.uk/2017/10/13/writing-a-bootloader/)
- [500 行代码实现 Linux 容器](https://blog.lizzie.io/linux-containers-in-500-loc.html)
- [编写你自己的虚拟机](https://justinmeiners.github.io/lc3-vm/)
- [学习 KVM - 实现你自己的 Linux 内核](https://david942j.blogspot.com/2018/10/note-learning-kvm-implement-your-own.html)
- [用 C/C++ 构建你自己的 Redis](https://build-your-own.org/redis/)
- 编写一个 C 编译器
  - [第 1 部分：整数、词法分析和代码生成](https://norasandler.com/2017/11/29/Write-a-Compiler.html)
  - [第 2 部分：一元运算符](https://norasandler.com/2017/12/05/Write-a-Compiler-2.html)
  - [第 3 部分：二元运算符](https://norasandler.com/2017/12/15/Write-a-Compiler-3.html)
  - [第 4 部分：更多的二元运算符](https://norasandler.com/2017/12/28/Write-a-Compiler-4.html)
  - [第 5 部分：局部变量](https://norasandler.com/2018/01/08/Write-a-Compiler-5.html)
  - [第 6 部分：条件语句](https://norasandler.com/2018/02/25/Write-a-Compiler-6.html)
  - [第 7 部分：复合语句](https://norasandler.com/2018/03/14/Write-a-Compiler-7.html)
  - [第 8 部分：循环](https://norasandler.com/2018/04/10/Write-a-Compiler-8.html)
  - [第 9 部分：函数](https://norasandler.com/2018/06/27/Write-a-Compiler-9.html)
  - [第 10 部分：全局变量](https://norasandler.com/2019/02/18/Write-a-Compiler-10.html)
- [使用 LLVM 实现一种语言](https://llvm.org/docs/tutorial/#kaleidoscope-implementing-a-language-with-llvm)
- [Meta Crush Saga：一个使用 C++17 编译时游戏](https://jguegant.github.io//jguegant.github.io/blogs/tech/meta-crush-saga.html)
- [高性能矩阵乘法](https://gist.github.com/nadavrot/5b35d44e8ba3dd718e595e40184d03f0)
- 从头开始的 Space Invaders
  - [第 1 部分](http://nicktasios.nl/posts/space-invaders-from-scratch-part-1.html)
  - [第 2 部分](http://nicktasios.nl/posts/space-invaders-from-scratch-part-2.html)
  - [第 3 部分](http://nicktasios.nl/posts/space-invaders-from-scratch-part-3.html)
  - [第 4 部分](http://nicktasios.nl/posts/space-invaders-from-scratch-part-4.html)
  - [第 5 部分](http://nicktasios.nl/posts/space-invaders-from-scratch-part-5.html)
- [使用 C++ 平台无关地创建 2D Breakout 游戏克隆](http://javilop.com/gamedev/tetris-tutorial-in-c-platform-independent-focused-in-game-logic-for-beginners/)
- 编写一个 Linux 调试器
  - [第 1 部分：设置](https://blog.tartanllama.xyz/writing-a-linux-debugger-setup/)
  - [第 2 部分：断点](https://blog.tartanllama.xyz/writing-a-linux-debugger-breakpoints/)
  - [第 3 部分：寄存器和内存](https://blog.tartanllama.xyz/writing-a-linux-debugger-registers/)
  - [第 4 部分：Elves 和 dwarves](https://blog.tartanllama.xyz/writing-a-linux-debugger-elf-dwarf/)
  - [第 5 部分：源代码和信号](https://blog.tartanllama.xyz/writing-a-linux-debugger-source-signal/)
  - [第 6 部分：源代码级别的单步调试](https://blog.tartanllama.xyz/writing-a-linux-debugger-dwarf-step/)
  - [第 7 部分：源代码级别的断点](https://blog.tartanllama.xyz/writing-a-linux-debugger-source-break/)
  - [第 8 部分：堆栈展开](https://blog.tartanllama.xyz/writing-a-linux-debugger-unwinding/)
  - [第 9 部分：处理变量](https://blog.tartanllama.xyz/writing-a-linux-debugger-variables/)
  - [第 10 部分：高级主题](https://blog.tartanllama.xyz/writing-a-linux-debugger-advanced-topics/)
- 让我们写一个编译器
  - [第 1 部分：介绍、选择一种语言和做一些规划](https://briancallahan.net/blog/20210814.html)
  - [第 2 部分：词法分析器](https://briancallahan.net/blog/20210815.html)
  - [第 3 部分：解析器](https://briancallahan.net/blog/20210816.html)
  - [第 4 部分：测试](https://briancallahan.net/blog/20210817.html)
  - [第 5 部分：代码生成器](https://briancallahan.net/blog/20210818.html)
  - [第 6 部分：输入和输出](https://briancallahan.net/blog/20210819.html)
  - [第 7 部分：数组](https://briancallahan.net/blog/20210822.html)
  - [第 8 部分：字符串、向前引用和结论](https://briancallahan.net/blog/20210826.html)

### 网络编程

- 让我们编写一个 TCP/IP 栈

  - [第 1 部分：以太网和 ARP](http://www.saminiir.com/lets-code-tcp-ip-stack-1-ethernet-arp/)
  - [第 2 部分：IPv4 和 ICMPv4](http://www.saminiir.com/lets-code-tcp-ip-stack-2-ipv4-icmpv4/)
  - [第 3 部分：TCP 基础知识和握手](http://www.saminiir.com/lets-code-tcp-ip-stack-3-tcp-handshake/)
  - [第 4 部分：TCP 数据流和套接字 API](http://www.saminiir.com/lets-code-tcp-ip-stack-4-tcp-data-flow-socket-api/)
  - [第 5 部分：TCP 重传](http://www.saminiir.com/lets-code-tcp-ip-stack-5-tcp-retransmission/)

- 并发服务器编程

  - [第 1 部分 - 介绍](https://eli.thegreenplace.net/2017/concurrent-servers-part-1-introduction/)
  - [第 2 部分 - 线程](https://eli.thegreenplace.net/2017/concurrent-servers-part-2-threads/)
  - [第 3 部分 - 事件驱动](https://eli.thegreenplace.net/2017/concurrent-servers-part-3-event-driven/)
  - [第 4 部分 - libuv](https://eli.thegreenplace.net/2017/concurrent-servers-part-4-libuv/)
  - [第 5 部分 - Redis 案例研究](https://eli.thegreenplace.net/2017/concurrent-servers-part-5-redis-case-study/)
  - [第 6 部分 - 回调、Promises 和 async/await](https://eli.thegreenplace.net/2018/concurrent-servers-part-6-callbacks-promises-and-asyncawait/)

- 从零开始构建一个 MQTT 代理
  - [第 1 部分 - 协议](https://codepr.github.io/posts/sol-mqtt-broker)
  - [第 2 部分 - 网络](https://codepr.github.io/posts/sol-mqtt-broker-p2)
  - [第 3 部分 - 服务器](https://codepr.github.io/posts/sol-mqtt-broker-p3)
  - [第 4 部分 - 数据结构](https://codepr.github.io/posts/sol-mqtt-broker-p4)
  - [第 5 部分 - 主题抽象](https://codepr.github.io/posts/sol-mqtt-broker-p5)
  - [第 6 部分 - 处理程序](https://codepr.github.io/posts/sol-mqtt-broker-p6)
  - [奖励 - 多线程](https://codepr.github.io/posts/sol-mqtt-broker-bonus)

### OpenGL:

- 使用 C++ 和 OpenGL 创建 2D Breakout 游戏克隆
  - [Breakout](https://learnopengl.com/In-Practice/2D-Game/Breakout)
  - [设置](https://learnopengl.com/In-Practice/2D-Game/Setting-up)
  - [渲染精灵](https://learnopengl.com/In-Practice/2D-Game/Rendering-Sprites)
  - [关卡](https://learnopengl.com/In-Practice/2D-Game/Levels)
  - 碰撞
    - [球](https://learnopengl.com/In-Practice/2D-Game/Collisions/Ball)
    - [碰撞检测](https://learnopengl.com/In-Practice/2D-Game/Collisions/Collision-detection)
    - [碰撞解决](https://learnopengl.com/In-Practice/2D-Game/Collisions/Collision-resolution)
  - [粒子](https://learnopengl.com/In-Practice/2D-Game/Particles)
  - [后处理](https://learnopengl.com/In-Practice/2D-Game/Postprocessing)
  - [电源增强](https://learnopengl.com/In-Practice/2D-Game/Powerups)
  - [音频](https://learnopengl.com/In-Practice/2D-Game/Audio)
  - [渲染文本](https://learnopengl.com/In-Practice/2D-Game/Render-text)
  - [最后的思考](https://learnopengl.com/In-Practice/2D-Game/Final-thoughts)
- [Handmade Hero](https://handmadehero.org)
- [用 Java 构建一个简单的 HTTP 服务器](http://javarevisited.blogspot.com/2015/06/how-to-create-http-server-in-java-serversocket-example.html)
- [用 Android 和 Java 构建手电筒应用](https://www.youtube.com/watch?v=dhWL4DC7Krs)（视频）
- [使用 Java 和 Spring Boot 构建具有用户认证的应用程序](https://spring.io/guides/gs/securing-web/)
- [使用 Java 和 JavaFX 构建 GUI 应用程序](https://openjfx.io/openjfx-docs/)
- [使用 Java 和 Maven 构建 RESTful Web 服务](https://www.baeldung.com/building-a-restful-web-service-with-spring-and-java-based-configuration)
- [使用 JavaFX 构建一个简单的游戏](https://gamedevelopment.tutsplus.com/tutorials/introduction-to-javafx-for-game-development--cms-23835)
- [使用 JavaFX 构建一个简单的图像浏览器](https://edencoding.com/javafx-image-viewer-tutorial/)
- [使用 JavaFX 构建一个简单的音乐播放器](https://levelup.gitconnected.com/build-a-simple-music-player-in-javafx-54c48b28e647)
- [使用 JavaFX 和 JDBC 构建一个简单的数据库应用程序](https://www.jenkov.com/javafx/tutorials/database.html)
- [使用 JavaFX 构建一个简单的文本编辑器](https://www.geekmj.org/java/javafx/building-a-text-editor-in-javafx-part-1/)


以下是一些关于编程的教程，涵盖了不同的主题和技术栈：

## JavaScript:

- [在 30 天内使用 30 个教程构建 30 个项目](https://javascript30.com)
- [用纯 JS 构建一个应用](https://medium.com/codingthesmartway-com-blog/pure-javascript-building-a-real-world-application-from-scratch-5213591cfcd6)
- [构建一个 Jupyter Notebook 扩展](https://link.medium.com/wWUO7TN8SS)
- [用 JavaScript 构建一个井字游戏](https://medium.com/javascript-in-plain-english/build-tic-tac-toe-game-using-javascript-3afba3c8fdcc)
- [用纯 JavaScript 构建一个简单的天气应用](https://webdesign.tutsplus.com/tutorials/build-a-simple-weather-app-with-vanilla-javascript--cms-33893)
- [用 JavaScript 构建一个待办事项列表应用](https://github.com/dwyl/javascript-todo-list-tutorial)

## HTML 和 CSS:

- [构建一个加载动画](https://medium.freecodecamp.org/how-to-build-a-delightful-loading-screen-in-5-minutes-847991da509f)
- [使用 JS 构建 HTML 计算器](https://medium.freecodecamp.org/how-to-build-an-html-calculator-app-from-scratch-using-javascript-4454b8714b98)
- [使用 JavaScript、HTML 和 CSS 构建贪吃蛇游戏](https://www.freecodecamp.org/news/think-like-a-programmer-how-to-build-snake-using-only-javascript-html-and-css-7b1479c3339e/)

### 移动应用:

- [用 React Native 构建一个待办事项应用](https://egghead.io/courses/build-a-react-native-todo-application)
- [用 React Native 和 Redux Thunk 构建一个应用](https://medium.com/@alialhaddad/how-to-use-redux-thunk-in-react-and-react-native-4743a1321bd0)

### Web 应用:

#### React:

- [创建无服务器的 React.js 应用](http://serverless-stack.com/)
- [创建一个 Trello 克隆](http://codeloveandboards.com/blog/2016/01/04/trello-tribute-with-phoenix-and-react-pt-1/)
- [使用 React、Node、MongoDB 和 SocketIO 创建一个角色投票应用](http://sahatyalkabov.com/create-a-character-voting-app-using-react-nodejs-mongodb-and-socketio)
- [React 教程：克隆 Yelp](https://www.fullstackreact.com/articles/react-tutorial-cloning-yelp/)
- [使用 Mocha、React、Redux 和 Immutable 构建一个完整的电影投票应用](https://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html)
- [使用 React 和 Node 构建一个 Twitter 流应用](https://scotch.io/tutorials/build-a-real-time-twitter-stream-with-node-and-react-js)
- [使用 React.js 和 Node.js 构建一个简单的 Medium 克隆](https://medium.com/@kris101/clone-medium-on-node-js-and-react-js-731cdfbb6878)
- [集成 MailChimp](https://medium.freecodecamp.org/how-to-integrate-mailchimp-in-a-javascript-web-app-2a889fb43f6f)
- [用 React + Parcel 构建一个 Chrome 扩展](https://medium.freecodecamp.org/building-chrome-extensions-in-react-parcel-79d0240dd58f)
- [用 React Native 构建一个 ToDo 应用](https://blog.hasura.io/tutorial-fullstack-react-native-with-graphql-and-authentication-18183d13373a)
- [制作一个聊天应用](https://medium.freecodecamp.org/how-to-build-a-chat-application-using-react-redux-redux-saga-and-web-sockets-47423e4bc21a)
- [使用 React Native 创建一个新闻应用](https://medium.freecodecamp.org/create-a-news-app-using-react-native-ced249263627)
- [学习 Webpack 用于 React](https://medium.freecodecamp.org/learn-webpack-for-react-a36d4cac5060)
- [使用 Puppeteer 和 Jest 测试 React 应用](https://blog.bitsrc.io/testing-your-react-app-with-puppeteer-and-jest-c72b3dfcde59)
- [构建自己的 React 脚手架](https://medium.freecodecamp.org/how-to-build-your-own-react-boilerplate-2f8cbbeb9b3f)
- [使用 React 创建生命游戏](https://medium.freecodecamp.org/create-gameoflife-with-react-in-one-hour-8e686a410174)
- [一个基本的 React+Redux 入门教程](https://hackernoon.com/a-basic-react-redux-introductory-tutorial-adcc681eeb5e)
- [构建一个预约调度应用](https://hackernoon.com/build-an-appointment-scheduler-using-react-twilio-and-cosmic-js-95377f6d1040)
- [用 Sentiment Analysis 构建一个聊天应用](https://codeburst.io/build-a-chat-app-with-sentiment-analysis-using-next-js-c43ebf3ea643)
- [使用 React、Node.js、Express 和 Webpack 构建一个完整的 Web 应用](https://hackernoon.com/full-stack-web-application-using-react-node-js-express-and-webpack-97dbd5b9d708)
- [使用 React 和 Firebase 创建 Todoist 克隆](https://www.youtube.com/watch?v=hT3j87FMR6M)
- 构建一个随机引语机器
  - [第 1 部分](https://www.youtube.com/watch?v=3QngsWA9IEE)
  - [第 2 部分](https://www.youtube.com/watch?v=XnoTmO06OYo)
  - [第 3 部分](https://www.youtube.com/watch?v=us51Jne67_I)
  - [第 4 部分](https://www.youtube.com/watch?v=iZx7hqHb5MU)
  - [第 5 部分](https://www.youtube.com/watch?v=lpba9vBqXl0)
  - [第 6 部分](https://www.youtube.com/watch?v=Jvp8j6zrFHE)
  - [第 7 部分](https://www.youtube.com/watch?v=M_hFfrN8_PQ)
- [React Phone E-Commerce 项目（视频）](https://www.youtube.com/watch?v=-edmQKcOW8s)

#### Angular:

- [使用 Angular 1.x 构建一个 Instagram 克隆](https://hackhands.com/building-instagram-clone-angularjs-satellizer-nodejs-mongodb/)
- 使用 Angular 2+ 构建一个离线可用的 Hacker News 客户端
  - [第 1 部分](https://houssein.me/angular2-hacker-news)
  - [第 2 部分](https://houssein.me/progressive-angular-applications)
- [使用 Django 和 AngularJS（Angular 1.x）构建一个 Google+ 克隆](https://thinkster.io/django-angularjs-tutorial)
- [使用 Angular 8 构建一个漂亮的实际应用程序](https://medium.com/@hamedbaatour/build-a-real-world-beautiful-web-app-with-angular-6-a-to-z-ultimate-guide-2018-part-i-e121dd1d55e)
- [使用 Angular 6 构建响应式布局](https://medium.com/@tomastrajan/how-to-build-responsive-layouts-with-bootstrap-4-and-angular-6-cfbb108d797b)
- 使用 Angular 5 构建一个 ToDo 应用
  - [Angular 入门](http://www.discoversdk.com/blog/intro-to-angular-and-the-evolution-of-the-web)
  - [第 1 部分](http://www.discoversdk.com/blog/angular-5-to-do-list-app-part-1)

#### Node:

- [使用 NodeJS 构建一个实时 Markdown 编辑器](https://scotch.io/tutorials/building-a-real-time-markdown-viewer)
- [使用 Node、Postgres 和 Knex 进行测试驱动开发](http://mherman.org/blog/2016/04/28/test-driven-development-with-node/)
- 使用 Node.js 编写 Twitter 机器人
  - [第 1 部分](https://codeburst.io/build-a-simple-twitter-bot-with-node-js-in-just-38-lines-of-code-ed92db9eb078)
  - [第 2 部分](https://codeburst.io/build-a-simple-twitter-bot-with-node-js-part-2-do-more-2ef1e039715d)
- [在 30 分钟内构建一个简单的搜索机器人](https://medium.freecodecamp.org/how-to-build-a-simple-search-bot-in-30-minutes-eb56fcedcdb1)
- [构建一个职位爬取 Web 应用](https://medium.freecodecamp.org/how-i-built-a-job-scraping-web-app-using-node-js-and-indreed-7fbba124bbdc)
- [构建一个 GitHub 应用](https://blog.scottlogic.com/2017/05/22/gifbot-github-integration.html)
- 如何使用 JavaScript、Node.JS、MongoDB 和 Web Sockets 构建自己的 Uber-for-X 应用
  - [第 1 部分](https://www.ashwinhariharan.tech/blog/how-to-build-your-own-uber-for-x-app/)
  - [第 2 部分](https://www.ashwinhariharan.tech/blog/how-to-build-your-own-uber-for-x-app-part-2/)

#### Vue

- [Vue 2 + Firebase：如何在 15 分钟内使用 Vue 构建具有 Firebase 认证系统的应用](https://medium.com/@anas.mammeri/vue-2-firebase-how-to-build-a-vue-app-with-firebase-authentication-system-in-15-minutes-fdce6f289c3c)
- [Vue.js 应用程序教程 - 使用 Vue 创建一个简单的预算应用](https://matthiashager.com/complete-vuejs-application-tutorial/)
- [使用 Vue、GraphQL 和 Apollo 构建一个博客 Web 应用](https://scotch.io/tutorials/build-a-blog-with-vue-graphql-and-apollo-client)
- 使用 MEVN（MongoDB、Express、Vue、Node）堆栈构建一个完整的全栈 Web 应用程序
  - [第 1 部分](https://medium.com/@anaida07/mevn-stack-application-part-1-3a27b61dcae0)
  - [第 2 部分](https://medium.com/@anaida07/mevn-stack-application-part-2-2-9ebcf8a22753)
- [Vue.js ToDo List 教程（视频）](https://www.youtube.com/watch?v=78tNYZUS-ps)
- [Vue 2 + Pub/Sub：使用 Vue 构建点对点多用户平台的游戏](https://www.ably.io/tutorials/peer-to-peer-vue)

#### 其他（Hapi、Express...）:

- 构建一个渐进式 Web 应用（PWA）
  - [第 1 部分](https://bitsofco.de/bitsofcode-pwa-part-1-offline-first-with-service-worker/)
  - [第 2 部分](https://bitsofco.de/bitsofcode-pwa-part-2-instant-loading-with-indexeddb/)
  - [第 3 部分](https://bitsofco.de/bitsofcode-pwa-part-3-push-notifications/)
- [用 JS 构建一个本地桌面应用](https://medium.freecodecamp.org/building-a-native-desktop-apps-with-javascript-a49ede90d8e9)
- 使用 NodeJs、GraphQL 和 Hapi 构建一个强大的 API
  - [第 1 部分](https://medium.com/@wesharehoodies/how-to-setup-a-powerful-api-with-nodejs-graphql-mongodb-hapi-and-swagger-e251ac189649)

#### D3.js

- [使用示例学习 D3](https://www.sitepoint.com/d3-js-data-visualizations/)
- [学习制作折线图](https://medium.freecodecamp.org/learn-to-create-a-line-chart-using-d3-js-4f43f1ee716b)

### 游戏开发:

- [使用 Phaser 制作 2D 打砖块游戏](https://developer.mozilla.org/en-US/docs/Games/Tutorials/2D_breakout_game_Phaser)
- 使用 Phaser 在 HTML5 和 JavaScript 中制作 Flappy Bird
  - [第 1 部分](http://www.lessmilk.com/tutorial/flappy-bird-phaser-1)
  - [第 2 部分](http://www.lessmilk.com/tutorial/flappy-bird-phaser-2)

### 桌面应用程序:

- [使用 React 和 Electron 构建一个桌面聊天应用](https://medium.freecodecamp.org/build-a-desktop-chat-app-with-react-electron-and-chatkit-744d168e6f2f)

### 其他:

- [如何在不到 20 行代码中构建一个 Web 框架](https://www.pubnub.com/blog/build-yourself-a-web-framework-in-less-than-20-lines-of-code/)
- [构建自己的 Redux](https://zapier.com/engineering/how-to-build-redux/)
- [如何编写自己的虚拟 DOM](https://medium.com/@deathmood/how-to-write-your-own-virtual-dom-ee74acc13060)
- [使用 AWS 在 WebSockets 上构建一个实时的 Serverless GraphQL API](https://andrewgriffithsonline.com/blog/serverless-websockets-on-aws/)

## Kotlin:

- [Keddit - 在开发 Android 应用程序的同时学习 Kotlin](https://medium.com/@juanchosaravia/learn-kotlin-while-developing-an-android-app-introduction-567e21ff9664)

## Lua:

### LÖVE:

- BYTEPATH: 使用 Lua 和 LÖVE 创建一个完整游戏
  - [第 0 部分：介绍](https://github.com/SSYGEN/blog/issues/30)
  - [第 1 部分：游戏循环](https://github.com/SSYGEN/blog/issues/15)
  - [第 2 部分：库](https://github.com/SSYGEN/blog/issues/16)
  - [第 3 部分：房间和区域](https://github.com/SSYGEN/blog/issues/17)
  - [第 4 部分：练习](https://github.com/SSYGEN/blog/issues/18)
  - [第 5 部分：游戏基础](https://github.com/SSYGEN/blog/issues/19)
  - [第 6 部分：玩家基础](https://github.com/SSYGEN/blog/issues/20)
  - [第 7 部分：玩家状态和攻击](https://github.com/SSYGEN/blog/issues/21)
  - [第 8 部分：敌人](https://github.com/SSYGEN/blog/issues/22)
  - [第 9 部分：导演和游戏循环](https://github.com/SSYGEN/blog/issues/23)
  - [第 10 部分：编码实践](https://github.com/SSYGEN/blog/issues/24)
  - [第 11 部分：被动技能](https://github.com/SSYGEN/blog/issues/25)
  - [第 12 部分：更多被动技能](https://github.com/SSYGEN/blog/issues/26)
  - [第 13 部分：技能树](https://github.com/SSYGEN/blog/issues/27)
  - [第 14 部分：控制台](https://github.com/SSYGEN/blog/issues/28)
  - [第 15 部分：最终](https://github.com/SSYGEN/blog/issues/29)

## Python:

### 网络爬虫:

- [使用 Python 挖掘 Twitter 数据](https://marcobonzanini.com/2015/03/02/mining-twitter-data-with-python-part-1/)
- [使用 Scrapy 和 MongoDB 爬取网站](https://realpython.com/blog/python/web-scraping-with-scrapy-and-mongodb/)
- [如何使用 Python 和 Selenium WebDriver 进行网页爬取](http://www.byperth.com/2018/04/25/guide-web-scraping-101-what-you-need-to-know-and-how-to-scrape-with-python-selenium-webdriver/)
- [使用 BeautifulSoup 构建一个电影推荐系统](https://medium.com/@nishantsahoo.in/which-movie-should-i-watch-5c83a3c0f5b1)


### Web 应用程序:

- [使用 Flask 构建微博](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
- [在 Django 中创建博客 Web 应用程序](https://tutorial.djangogirls.org/en/)
- [选择自己的冒险演示文稿](https://www.twilio.com/blog/2015/03/choose-your-own-adventures-presentations-wizard-mode-part-1-of-3.html)
- [使用 Flask 和 RethinkDB 构建 Todo 列表](https://realpython.com/blog/python/rethink-flask-a-simple-todo-list-powered-by-flask-and-rethinkdb/)
- [使用 Django 和测试驱动开发构建 Todo 列表](http://www.obeythetestinggoat.com/)
- [使用 Python 构建 RESTful 微服务](http://www.skybert.net/python/developing-a-restful-micro-service-in-python/)
- [使用 Docker、Flask 和 React 构建微服务](https://testdriven.io/)
- [使用 Flask 构建一个简单的 Web 应用程序](https://pythonspot.com/flask-web-app-with-python/)
- [在不到 20 分钟内创建一个 Django API](https://codeburst.io/create-a-django-api-in-under-20-minutes-2a082a60f6f3)
- 使用 Django、Postgres 和 JavaScript 构建社区驱动的交付应用程序
  - [第 1 部分](https://www.ashwinhariharan.tech/blog/thinking-of-building-a-contact-tracing-application-heres-what-you-can-do-instead/)
  - [第 2 部分](https://www.ashwinhariharan.tech/blog/thinking-of-building-a-contact-tracing-application-heres-what-you-can-do-instead-part-2/)
- 使用 Vue、django-notifs、RabbitMQ 和 uWSGI 构建实时聊天应用程序
  - [第 1 部分](https://danidee10.github.io/2018/01/01/realtime-django-1.html)
  - [第 2 部分](https://danidee10.github.io/2018/01/03/realtime-django-2.html)
  - [第 3 部分](https://danidee10.github.io/2018/01/07/realtime-django-3.html)
  - [第 4 部分](https://danidee10.github.io/2018/01/10/realtime-django-4.html)
  - [第 5 部分](https://danidee10.github.io/2018/01/13/realtime-django-5.html)
  - [第 6 部分](https://danidee10.github.io/2018/03/12/realtime-django-6.html)



### 机器人（Bots）:

- [构建 Reddit 机器人](http://pythonforengineers.com/build-a-reddit-bot-part-1/)
- [如何制作 Reddit 机器人 - YouTube](https://www.youtube.com/watch?v=krTUf7BpTc0)（视频）
- [构建 Facebook Messenger 机器人](https://blog.hartleybrody.com/fb-messenger-bot/)
- [制作 Reddit + Facebook Messenger 机器人](https://pythontips.com/2017/04/13/making-a-reddit-facebook-messenger-bot/)
- 如何使用 Python 创建 Telegram 机器人
  - [第 1 部分](https://khashtamov.com/en/how-to-create-a-telegram-bot-using-python/)
  - [第 2 部分](https://khashtamov.com/en/how-to-deploy-telegram-bot-django/)
- [使用 Python 创建 Twitter 机器人](https://medium.freecodecamp.org/creating-a-twitter-bot-in-python-with-tweepy-ac524157a607)

### 数据科学（Data Science）:

- 通过完成几个项目来学习 Python 数据科学（视频）:
  - [第 1 部分: 介绍](https://www.youtube.com/watch?v=T5pRlIbr6gg)
  - [第 2 部分: Twitter 情感分析](https://www.youtube.com/watch?v=o_OZdbCzHUA)
  - [第 3 部分: 推荐系统](https://www.youtube.com/watch?v=9gBC9R-msAk&list=PL2-dafEMk2A6QKz1mrk1uIGfHkC1zZ6UU&index=3)
  - [第 4 部分: 预测股票价格](https://www.youtube.com/watch?v=SSu00IRRraY&index=4&list=PL2-dafEMk2A6QKz1mrk1uIGfHkC1zZ6UU)
  - [第 5 部分: TensorFlow 中的 Deep Dream](https://www.youtube.com/watch?v=MrBzgvUNr4w&list=PL2-dafEMk2A6QKz1mrk1uIGfHkC1zZ6UU&index=5)
  - [第 6 部分: 遗传算法](https://www.youtube.com/watch?v=dSofAXnnFrY&index=6&list=PL2-dafEMk2A6QKz1mrk1uIGfHkC1zZ6UU)

### 机器学习（Machine Learning）:

- [从头开始用 Python 编写线性回归](https://www.youtube.com/watch?v=uwwWVAgJBcM)（视频）
- [逐步进行 Python 机器学习](https://machinelearningmastery.com/machine-learning-in-python-step-by-step/)
- [预测葡萄酒的质量](https://medium.freecodecamp.org/using-machine-learning-to-predict-the-quality-of-wines-9e2e13d7480d)
- [解决水果分类问题](https://towardsdatascience.com/solving-a-simple-classification-problem-with-python-fruits-lovers-edition-d20ab6b071d2)
- [学习无监督学习（Unsupervised Learning）](https://scikit-learn.org/stable/unsupervised_learning.html)
- [从头开始用 Python 构建自己的神经网络](https://towardsdatascience.com/how-to-build-your-own-neural-network-from-scratch-in-python-68998a08e4f6)
- [在 Python 中使用线性回归，无需使用 sklearn](https://medium.com/we-are-orb/linear-regression-in-python-without-scikit-learn-50aef4b8d122)
- [在 Python 中进行多元线性回归，无需使用 sklearn](https://medium.com/we-are-orb/multivariate-linear-regression-in-python-without-scikit-learn-7091b1d45905)
- [使用 KNN 实现音乐推荐](https://towardsdatascience.com/how-to-build-a-simple-song-recommender-296fcbc8c85)
- 找到类似的 Quora 问题-
  - [使用 BOW、TFIDF 和 Xgboost](https://towardsdatascience.com/finding-similar-quora-questions-with-bow-tfidf-and-random-forest-c54ad88d1370)
  - [使用 Word2Vec 和 Xgboost](https://towardsdatascience.com/finding-similar-quora-questions-with-word2vec-and-xgboost-1a19ad272c0d)
- [使用 Python 和机器学习检测假新闻](https://data-flair.training/blogs/advanced-python-project-detecting-fake-news/)

### OpenCV:

- [构建文档扫描器](https://www.pyimagesearch.com/2014/09/01/build-kick-ass-mobile-document-scanner-just-5-minutes/)
- [使用 OpenCV 和深度学习构建人脸检测器](https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/)
- [使用 OpenCV 和深度学习构建最快的自定义对象检测系统（YOLOv3）（视频播放列表）](https://www.youtube.com/playlist?list=PLKHYJbyeQ1a0oGzgRXy-QwAN1tSV4XZxg)
- [使用 OpenCV、Python 和深度学习构建人脸识别系统](https://www.pyimagesearch.com/2018/06/18/face-recognition-with-opencv-python-and-deep-learning/)
- [在图像中检测显著特征](https://www.pyimagesearch.com/2018/07/16/opencv-saliency-detection/)
- [构建条形码扫描器](https://www.pyimagesearch.com/2018/05/21/an-opencv-barcode-and-qr-code-scanner-with-zbar/)
- [学习人脸聚类](https://www.pyimagesearch.com/2018/07/09/face-clustering-with-python/)
- [使用 Camshift 进行对象跟踪](https://www.pyimagesearch.com/wp-content/uploads/2014/11/opencv_crash_course_camshift.pdf)
- [OpenCV 和深度学习进行语义分割](https://www.pyimagesearch.com/2018/09/03/semantic-segmentation-with-opencv-and-deep-learning/)
- [在图像和视频中检测文本](https://www.pyimagesearch.com/2018/08/20/opencv-text-detection-east-text-detector/)
- [使用 OpenCV 进行人数统计](https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/)
- [使用 OpenCV 跟踪多个对象](https://www.pyimagesearch.com/2018/08/06/tracking-multiple-objects-with-opencv/)
- [使用 OpenCV 进行神经风格转移](https://www.pyimagesearch.com/2018/08/27/neural-style-transfer-with-opencv/)
- [OpenCV OCR 和文本识别](https://www.pyimagesearch.com/2018/09/17/opencv-ocr-and-text-recognition-with-tesseract/)
- [文本倾斜校正教程](https://www.pyimagesearch.com/2017/02/20/text-skew-correction-opencv-python/)
- [人脸标记检测教程](https://www.pyimagesearch.com/2017/04/03/facial-landmarks-dlib-opencv-python/)
- [使用 Mask-R-CNN 进行对象检测](https://www.learnopencv.com/deep-learning-based-object-detection-and-instance-segmentation-using-mask-r-cnn-in-opencv-python-c/)
- [自动目标检测教程](https://www.pyimagesearch.com/2015/05/04/target-acquired-finding-targets-in-drone-and-quadcopter-video-streams-using-python-and-opencv/)
- [使用 OpenCV 进行特征脸（EigenFaces）](https://www.learnopencv.com/eigenface-using-opencv-c-python/)
- [使用更快的（5 点）人脸标记检测教程](https://www.pyimagesearch.com/2018/04/02/faster-facial-landmark-detector-with-dlib/)
- [手部关键点检测](https://www.learnopencv.com/hand-keypoint-detection-using-deep-learning-and-opencv/)
- Dlib 相关性对象跟踪 -
  - [单个对象跟踪器](https://www.pyimagesearch.com/2018/10/22/object-tracking-with-dlib/)
  - [多个对象跟踪器](https://www.pyimagesearch.com/2018/10/29/multi-object-tracking-with-dlib/)
- [使用 OpenCV 和 Python 进行图像拼接](https://www.pyimagesearch.com/2018/12/17/image-stitching-with-opencv-and-python/)
- [OpenCV 中的实例分割](https://www.pyimagesearch.com/2018/11/26/instance-segmentation-with-opencv/)
- [面部口罩检测器](https://www.pyimagesearch.com/2020/05/04/covid-19-face-mask-detector-with-opencv-keras-tensorflow-and-deep-learning/)

### 深度学习（Deep Learning）:

- [使用卷积神经网络检测面部关键点](http://danielnouri.org/notes/2014/12/17/using-convolutional-neural-nets-to-detect-facial-keypoints-tutorial/)
- [使用 TensorFlow 进行图像分类](https://www.tensorflow.org/tutorials/images/classification)
- [使用 TensorFlow 进行情感分析](https://www.tensorflow.org/tutorials/text/text_classification_rnn)
- [使用 Keras 进行情感分析](https://towardsdatascience.com/understanding-rnn-and-lstm-f7cdf6dfc14e)
- [使用 TensorFlow 进行物体检测](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/index.html)
- [使用 Keras 进行风格转移](https://towardsdatascience.com/neural-transfer-learning-for-artistic-style-transfer-7eaf81175ef5)
- [使用 TensorFlow 构建循环神经网络（RNN）](https://www.tensorflow.org/tutorials/text/text_generation)
- [使用 Keras 进行图像生成](https://towardsdatascience.com/generating-new-faces-with-variational-autoencoders-d13cfcb5f0a8)
- [使用 TensorFlow 构建生成对抗网络（GAN）](https://www.tensorflow.org/tutorials/generative/dcgan)
- [使用 Keras 进行图像分类](https://www.tensorflow.org/tutorials/keras/classification)
- [使用 TensorFlow 进行文本生成](https://www.tensorflow.org/tutorials/text/text_generation_rnn)
- [使用 Keras 构建序列到序列（Sequence-to-Sequence）模型](https://machinelearningmastery.com/develop-encoder-decoder-model-sequence-sequence-prediction-keras/)
- [使用 TensorFlow 构建变分自编码器（VAE）](https://towardsdatascience.com/intuitively-understanding-variational-autoencoders-1bfe67eb5daf)
- [使用 Keras 进行图像分割](https://towardsdatascience.com/introduction-to-keras-for-deep-learning-2c74f96665)
- [使用 TensorFlow 构建循环神经网络（RNN）](https://www.tensorflow.org/tutorials/text/text_generation)
- [使用 Keras 进行图像生成](https://towardsdatascience.com/generating-new-faces-with-variational-autoencoders-d13cfcb5f0a8)
- [使用 TensorFlow 构建生成对抗网络（GAN）](https://www.tensorflow.org/tutorials/generative/dcgan)
- [使用 Keras 进行图像分类](https://www.tensorflow.org/tutorials/keras/classification)
- [使用 TensorFlow 进行文本生成](https://www.tensorflow.org/tutorials/text/text_generation_rnn)
- [使用 Keras 构建序列到序列（Sequence-to-Sequence）模型](https://machinelearningmastery.com/develop-encoder-decoder-model-sequence-sequence-prediction-keras/)
- [使用 TensorFlow 构建变分自编码器（VAE）](https://towardsdatascience.com/intuitively-understanding-variational-autoencoders-1bfe67eb5daf)
- [使用 Keras 进行图像分割](https://towardsdatascience.com/introduction-to-keras-for-deep-learning-2c74f96665)


以下是一些关于不同编程语言的资源，可以帮助你学习和开发：

## OCaml:

- [使用OCaml实现LLVM编程语言](https://llvm.org/docs/tutorial/#kaleidoscope-implementing-a-language-with-llvm-in-objective-caml)
- [使用OCaml编写Game Boy模拟器](https://linoscope.github.io/writing-a-game-boy-emulator-in-ocaml/)

## Ruby:

- [使用Ruby构建网络堆栈](https://medium.com/geckoboard-under-the-hood/how-to-build-a-network-stack-in-ruby-f73aeb1b661b)
- 自己构建Redis
  - [第0部分：介绍](https://rohitpaulk.com/articles/redis-0)
  - [第1部分：基础的TCP服务器](https://rohitpaulk.com/articles/redis-1)
  - [第2部分：PING <-> PONG](https://rohitpaulk.com/articles/redis-2)
  - [第3部分：并发客户端](https://rohitpaulk.com/articles/redis-3)
  - [第4部分：ECHO](https://rohitpaulk.com/articles/redis-4)
- [使用Ruby重新构建Git](https://thoughtbot.com/blog/rebuilding-git-in-ruby)

### Ruby on Rails:

- [Ruby on Rails教程](https://www.railstutorial.org/book)
- [使用Ruby on Rails从头构建Instagram](https://www.dropbox.com/s/9vq430e9s3q7pu8/Let%27s%20Build%20Instagram%20with%20Ruby%20on%20Rails%20-%20Free%20Edition.pdf?dl=0)
- [使用Rails构建社交网络](https://medium.com/rails-ember-beyond/how-to-build-a-social-network-using-rails-eb31da569233)
- [如何构建一个Ruby on Rails应用程序](https://www.digitalocean.com/community/tutorials/how-to-build-a-ruby-on-rails-application)

## Haskell:

- [写一个Haskell编译器](http://dev.stephendiehl.com/fun/)
- [48小时内自己编写一个Scheme解释器](https://en.wikibooks.org/wiki/Write_Yourself_a_Scheme_in_48_Hours)
- [写一个Scheme解释器](https://github.com/write-you-a-scheme-v2/scheme)
- [自己编写IRC机器人](https://wiki.haskell.org/Roll_your_own_IRC_bot)
- [制作电影Monad](https://lettier.github.io/posts/2016-08-15-making-movie-monad.html)
- [使用Haskell制作网站（过时）](http://adit.io/posts/2013-04-15-making-a-website-with-haskell.html)

## R:

- [使用Shiny构建Web应用](http://shiny.rstudio.com/tutorial/)
- [构建一个加密货币机器人](https://towardsdatascience.com/build-a-cryptocurrency-trading-bot-with-r-1445c429e1b1)
- [学习关联规则挖掘（Association Rule Mining）](https://towardsdatascience.com/association-rule-mining-in-r-ddf2d044ae50)

## Rust:



- 使用Rust构建简单的Web应用程序
  - [第1部分](http://joelmccracken.github.io/entries/a-simple-web-app-in-rust-pt-1/)
  - [第2a部分](http://joelmccracken.github.io/entries/a-simple-web-app-in-rust-pt-2a/)
  - [第2b部分](http://joelmccracken.github.io/entries/a-simple-web-app-in-rust-pt-2b/)
- [使用纯Rust编写操作系统](https://os.phil-opp.com/)
- [使用Rust构建浏览器引擎](https://limpet.net/mbrubeck/2014/08/08/toy-layout-engine-1.html)
- [使用Rust编写微服务](http://www.goldsborough.me/rust/web/tutorial/2018/01/20/17-01-11-writing_a_microservice_in_rust/)
- [使用Too Many Linked Lists学习Rust](http://cglab.ca/~abeinges/blah/too-many-lists/book/README.html)
- Rust详解：从零开始编写可扩展的聊天服务
  - [第1部分：实现WebSocket介绍](https://nbaksalyar.github.io/2015/07/10/writing-chat-in-rust.html)
  - [第2部分：发送和接收消息](https://nbaksalyar.github.io/2015/11/09/rust-in-detail-2.html)
- [使用Rust编写桌面和Web的Roguelike游戏](https://aimlesslygoingforward.com/blog/2019/02/09/writing-a-rust-roguelike-for-the-desktop-and-the-web/)
- [使用Rust构建单页应用程序](http://www.sheshbabu.com/posts/rust-wasm-yew-single-page-application/)
- [使用Rust编写NES模拟器](https://bugzmanov.github.io/nes_ebook/)
- 创建一个使用神经网络和遗传算法进行进化模拟的应用程序，并将其编译为WebAssembly
  - [第1部分](https://pwy.io/en/posts/learning-to-fly-pt1/)
  - [第2部分](https://pwy.io/en/posts/learning-to-fly-pt2/)
  - [第3部分](https://pwy.io/en/posts/learning-to-fly-pt3/)
  - [第4部分](https://pwy.io/en/posts/learning-to-fly-pt4/)

## Scala:

- [简单的基于actor的区块链](https://www.freecodecamp.org/news/how-to-build-a-simple-actor-based-blockchain-aac1e996c177/)
- [无魔法：正则表达式](https://rcoh.svbtle.com/no-magic-regular-expressions)

## Swift:

- [Hacking with Swift - 通过39个项目学习Swift](https://www.hackingwithswift.com/read)
- [从零开始制作复古第一人称射击游戏](https://github.com/nicklockwood/RetroRampage)

## 其他资源

- [React Redux链接](https://github.com/markerikson/react-redux-links)
- [Udemy.com](https://www.udemy.com/)
- [全栈Python](https://www.fullstackpython.com/)
-[Node School](https://nodeschool.io/)
- [ScotchIO](https://scotch.io/)
- [Exercism](http://www.exercism.io/)
- [Egghead.io](http://www.egghead.io/)
- [Michael Herman的博客](http://mherman.org/)
- [Thinkster.io](http://thinkster.io)
- [Enlight](https://enlight.nyc/)
- [Hack Club Workshops](https://hackclub.com/workshops/)
- [CodeCrafters](https://codecrafters.io/)

