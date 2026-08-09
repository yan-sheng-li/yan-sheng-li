<!--
================================================================================
  Profile README · yan-sheng-li
  6 个主要区块以成对注释标记界定（TYPING_BANNER / ABOUT_ME / TECH_STACK / STATS / SOCIAL / FOOTER）。
--------------------------------------------------------------------------------
  全局配色常量（后续所有区块统一取色依据；≤4 主色，不引入方案外额外主色）
  PRIMARY_SKY = #38BDF8   天蓝主强调（卡片标题色 / 区块标题装饰 / 主徽章底色）
  ACCENT_CYAN    = #22D3EE   次强调（打字横幅文字 / 图标色 / 访客计数徽章）
  ACCENT_MINT    = #2DD4BF   薄荷点缀（关键徽章 / 分隔装饰渐变收尾）
  BASE_INK       = 深色态 #C9D1D9 / 浅色态 #1F2328   中性正文文字（随主题切换）

  深色主题面：bg=#0D1117  border=#30363D  text=#C9D1D9
  浅色主题面：bg=#FFFFFF  border=#D0D7DE  text=#1F2328

  统一分隔元素：天蓝→青→薄荷 渐变分隔条（capsule-render type=rect），
  位于每个主要区块标题下方，作为可辨识的层次锚点；相邻区块间分隔类型一致。
  仅使用 GitHub 允许的内联 HTML 子集：div/table/tr/td/picture/source/img/a/sub/sup/h1-h4/hr/b/br。
================================================================================
-->

<!-- SECTION:TYPING_BANNER:START -->
<!--
  打字横幅：文档最顶部第一个可见区块（位于任何其他内容之前，无标题以确保居首）。
  顶部先放一条 capsule-render 渐变波浪装饰(waving)，再放 readme-typing-svg 打字动画，整体 <div align="center"> 居中。
  横幅字体改用 Google Fonts 的 "Ma Shan Zheng"（马善政毛笔书法体，艺术字），color=0891B2 加深青在深/浅两主题对比均达标，无需 <picture>。
  lines 以 ; 分隔，共 4 句（≥3）、每句 ≤50 字符，含昵称与简介，全中文以确保书法字体字形完整。
  【重要】中文必须做 URL 百分号编码，否则 GitHub 图片代理(camo)取不到图导致横幅空白。
-->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:38BDF8,50:22D3EE,100:2DD4BF&height=170&section=header" alt="顶部天蓝到薄荷渐变波浪装饰" />
  <br />
  <img
    src="https://readme-typing-svg.demolab.com/?font=Ma+Shan+Zheng&size=36&duration=3500&pause=800&center=true&vCenter=true&width=680&height=100&repeat=true&color=0891B2&lines=yan-sheng-li;%E4%B8%80%E4%B8%AA%E7%97%B4%E8%BF%B7%E4%BA%8E%E8%AE%A1%E7%AE%97%E6%9C%BA%E6%8A%80%E6%9C%AF%E7%9A%84%E5%AD%A6%E7%94%9F;A%20Student%20Obsessed%20With%20Computer%20Tech;%E5%AD%A6%E4%BB%A5%E8%87%B4%E7%94%A8%E6%89%8D%E6%98%AF%E7%8E%8B%E9%81%93;Learn%20By%20Doing%2C%20Master%20By%20Using"
    alt="yan-sheng-li - 一个痴迷于计算机技术的学生"
  />
  <br />
  <!-- 无限横向滚动跑马灯：手写 SMIL 动画 SVG，双拷贝无缝循环，边缘渐隐遮罩，本地资源稳定不破图 -->
  <img width="72%" src="assets/marquee.svg" alt="滚动横幅：学以致用才是王道 · Vibe Coding · Full-Stack · Game Dev · Automation · Open Source" />
  <br />
  <!-- 星空微光：手写 SMIL 动画 SVG，缓慢错峰闪烁 + 旋转四角星，天蓝主题，本地资源稳定 -->
  <img width="86%" src="assets/stars.svg" alt="星空微光装饰 · twinkling starfield" />
</div>
<!-- SECTION:TYPING_BANNER:END -->

<!-- SECTION:ABOUT_ME:START -->
<h2 align="center"><img height="28" src="https://img.icons8.com/fluency/48/user-male-circle.png" alt="关于我图标" />&nbsp; 关于我 · About Me</h2>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:38BDF8,50:22D3EE,100:2DD4BF&height=3" alt="天蓝到青到薄荷的渐变分隔条" width="100%" />
</div>

<h1 align="center">yan-sheng-li <sub>(he/him)</sub></h1>

<p align="center">一个痴迷于计算机技术的学生 · A student obsessed with computer technology</p>

<p align="center">
  <img height="20" src="https://img.icons8.com/fluency/48/quote-left.png" alt="格言" />
  <i>学习是永无止境的，学以致用才是王道！</i>
  <img height="20" src="https://img.icons8.com/fluency/48/quote-right.png" alt="格言" />
</p>

<p align="center">
  <img height="18" src="https://img.icons8.com/fluency/48/graduation-cap.png" alt="院校" /> <你的院校> · <Your University>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <img height="18" src="https://img.icons8.com/fluency/48/marker.png" alt="所在地" /> <你的城市> · <Your City>
</p>

<!-- 快捷入口：一进主页即可直达 网站 / B站 / 爱发电，并展示 GitHub 关注数；flat-square 轻量风格区别于底部社交区 -->
<p align="center">
  <a href="https://www.your-site.com"><img src="https://img.shields.io/badge/个人网站-Website-38BDF8?style=flat-square&logo=googlechrome&logoColor=white" alt="个人网站 · Website" /></a>
  <a href="https://space.bilibili.com/000000"><img src="https://img.shields.io/badge/Bilibili-哔哩哔哩-FB7299?style=flat-square&logo=bilibili&logoColor=white" alt="Bilibili · 哔哩哔哩" /></a>
  <a href="https://ifdian.net/a/youraccount"><img src="https://img.shields.io/badge/爱发电-Sponsor-2DD4BF?style=flat-square&logo=afdian&logoColor=white" alt="爱发电 · Sponsor" /></a>
  <a href="https://github.com/yan-sheng-li"><img src="https://img.shields.io/github/followers/yan-sheng-li?style=flat-square&logo=github&label=Followers&color=22D3EE&labelColor=0D1117" alt="GitHub Followers · GitHub 关注数" /></a>
</p>

- <img height="18" src="https://img.icons8.com/fluency/48/idea.png" alt="专注" /> 专注于计算机技术的学习与实践，热爱钻研底层原理与工程实现
- <img height="18" src="https://img.icons8.com/fluency/48/source-code.png" alt="开源" /> 持续维护多个开源项目，享受与社区一起打磨代码的过程
- <img height="18" src="https://img.icons8.com/fluency/48/gears.png" alt="自动化" /> 热衷于自动化工具的研发，让重复繁琐的工作交给程序完成
- <img height="18" src="https://img.icons8.com/fluency/48/artificial-intelligence.png" alt="AI" /> 资深 Vibe Coding 爱好者，享受与 AI 结对编程、把想法快速变成产品
- <img height="18" src="https://img.icons8.com/fluency/48/domain.png" alt="网站" /> 个人网站：[www.your-site.com](https://www.your-site.com)

<!--
  每日一言：由每日刷新工作流生成主题自适应 SVG 推到 output 分支，每日自动更新；
  作为「关于我」文字要点之后的动态卡片收尾，形成 文字 → 动态卡片 的自然流。
  单张自适应 SVG(内置 prefers-color-scheme)，非 <picture>；alt 非空描述用途。
-->
<div align="center">
  <img src="https://raw.githubusercontent.com/yan-sheng-li/yan-sheng-li/output/quote.svg" alt="每日一言 · 编程与学习箴言（每日自动更新）" />
</div>

<!-- SECTION:ABOUT_ME:END -->

<!-- SECTION:TECH_STACK:START -->
<h2 align="center"><img height="28" src="https://img.icons8.com/fluency/48/source-code.png" alt="技术栈图标" />&nbsp; 技术栈 · Tech Stack</h2>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:38BDF8,50:22D3EE,100:2DD4BF&height=3" alt="天蓝到青到薄荷的渐变分隔条" width="100%" />
</div>

<!--
  技能图标墙：skillicons.dev 一张 SVG 渲染整齐的技术图标网格，作为技术栈的视觉总览；下方为详细分类徽章。
-->
<div align="center">
  <img src="https://skillicons.dev/icons?i=py,java,kotlin,c,cpp,cs,ts,js,rust,go,vue,react,vite,tailwind,threejs,html,css,flutter,electron,tauri,nodejs,bun,fastapi,spring,dotnet,qt,mysql,postgres,mongodb,sqlite,redis,nginx,docker,kubernetes,linux,prometheus,grafana,unity,godot,unreal,ps,pr,git,github,vscode,pycharm,visualstudio,androidstudio,ubuntu,windows&perline=13" alt="技能图标墙：常用编程语言、框架、数据库、云原生、游戏与工具技术图标总览（GoLand 见下方分类徽章）" />
</div>

<!--
  技术栈徽章：<div align="center"> 内按 7 组排列 shields.io 徽章（style=for-the-badge）。
  每组前置 <h4 align="center"> 小标题；每个徽章含技术名称文字标签 + 官方 logo（有则带）+ 非空 alt。
  无官方图标的技术省略 logo 参数使用纯色文字徽章，仍保留名称与非空 alt。
  分组数 8（2~8）、徽章总数在 3~60 之间，必含 Python / TypeScript / Rust。
  徽章图片实时取自 img.shields.io（稳定），内容固定，属静态区块。
-->

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/code.png" alt="编程语言图标" />&nbsp; 编程语言 · Programming Languages</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" alt="C" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" alt="C Sharp" />
  <img src="https://img.shields.io/badge/GDScript-478CBF?style=for-the-badge&logo=godotengine&logoColor=white" alt="GDScript" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go" />
</p>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/web.png" alt="前端图标" />&nbsp; 前端 · Frontend</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
</p>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/multiple-devices.png" alt="跨端桌面图标" />&nbsp; 跨端 &amp; 桌面 · Cross-Platform &amp; Desktop</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white" alt="Electron" />
  <img src="https://img.shields.io/badge/Tauri-24C8DB?style=for-the-badge&logo=tauri&logoColor=white" alt="Tauri" />
  <img src="https://img.shields.io/badge/PyQt-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="PyQt" />
</p>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/server.png" alt="后端图标" />&nbsp; 后端 · Backend</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Bun-000000?style=for-the-badge&logo=bun&logoColor=white" alt="Bun" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Gin-00ADD8?style=for-the-badge&logo=gin&logoColor=white" alt="Gin" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt="dotNET" />
</p>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/database.png" alt="数据库图标" />&nbsp; 数据库 &amp; 中间件 · Databases &amp; Middleware</h4>
<p align="center">
  <img src="https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx" />
</p>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/cloud.png" alt="云原生图标" />&nbsp; 云原生 &amp; 运维 · Cloud Native &amp; DevOps</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana" />
</p>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/controller.png" alt="游戏多媒体图标" />&nbsp; 游戏 &amp; 多媒体 · Game &amp; Media</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" />
  <img src="https://img.shields.io/badge/Godot-478CBF?style=for-the-badge&logo=godotengine&logoColor=white" alt="Godot" />
  <img src="https://img.shields.io/badge/Unreal_Engine-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white" alt="Unreal Engine" />
  <img src="https://img.shields.io/badge/Blender-E87D0D?style=for-the-badge&logo=blender&logoColor=white" alt="Blender" />
  <img src="https://img.shields.io/badge/Photoshop-31A8FF?style=for-the-badge&logo=adobephotoshop&logoColor=white" alt="Photoshop" />
  <img src="https://img.shields.io/badge/Premiere_Pro-9999FF?style=for-the-badge&logo=adobepremierepro&logoColor=white" alt="Premiere Pro" />
  <img src="https://img.shields.io/badge/OBS_Studio-302E31?style=for-the-badge&logo=obsstudio&logoColor=white" alt="OBS Studio" />
  <img src="https://img.shields.io/badge/NetEase_ModSDK-38BDF8?style=for-the-badge" alt="NetEase ModSDK" />
</p>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/maintenance.png" alt="工具平台图标" />&nbsp; 工具 &amp; 平台 · Tools &amp; Platforms</h4>
<p align="center">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code" />
  <img src="https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=pycharm&logoColor=white" alt="PyCharm" />
  <img src="https://img.shields.io/badge/GoLand-000000?style=for-the-badge&logo=goland&logoColor=white" alt="GoLand" />
  <img src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white" alt="Visual Studio" />
  <img src="https://img.shields.io/badge/1Panel-0195FF?style=for-the-badge&logo=1panel&logoColor=white" alt="1Panel" />
  <img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" alt="Ubuntu" />
</p>

<!-- SECTION:TECH_STACK:END -->

<!-- SECTION:STATS:START -->
<h2 align="center"><img height="28" src="https://img.icons8.com/fluency/48/combo-chart.png" alt="数据统计图标" />&nbsp; GitHub 数据 · GitHub Stats</h2>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:38BDF8,50:22D3EE,100:2DD4BF&height=3" alt="天蓝到青到薄荷的渐变分隔条" width="100%" />
</div>

<!--
  自定义数据看板：由每日刷新工作流经 GitHub API 汇总 公开仓库数 / Star 总数 / Fork 总数 / Followers，
  生成主题自适应 SVG(dashboard.svg) 推到 output 分支，每日自动更新；alt 非空。
-->
<div align="center">
  <img src="https://raw.githubusercontent.com/yan-sheng-li/yan-sheng-li/output/dashboard.svg" alt="数据看板 · 公开仓库数 / Star 总数 / Fork 总数 / Followers（每日自动更新）" />
</div>

<!--
  最近动态：由每日刷新工作流经 GitHub Events API 抓取最近公开动态，生成中英双语主题自适应 SVG(activity.svg)，
  推到 output 分支每日自动更新；API 失败或无动态时兜底一行，不破图。
-->
<div align="center">
  <img src="https://raw.githubusercontent.com/yan-sheng-li/yan-sheng-li/output/activity.svg" alt="最近动态 · Recent Activity（近期推送 / 创建 / PR / Star 等，每日自动更新）" />
</div>

<!--
  三张统计卡片，均用 <picture> + <source media="(prefers-color-scheme: dark)"> + 浅色 <img> 回退实现深/浅主题切换。
  三卡配色参数取值完全一致且等于全局主题声明色值（Property 9）：
    深色 bg=0D1117 title=38BDF8 text=C9D1D9 icon=22D3EE border=30363D
    浅色 bg=FFFFFF title=0284C7 text=1F2328 icon=0891B2 border=D0D7DE
  streak-stats 参数名不同（background/ring/fire/currStreakLabel/sideLabels/dates/stroke 等），但色值取相同值。
-->

<!-- 通用统计 + 常用语言 并排一行（table 两列），连续贡献单独居中一行 -->
<table>
  <tr>
    <td width="50%" valign="top" align="center">
      <b><img height="18" src="https://img.icons8.com/fluency/48/combo-chart.png" alt="通用统计图标" /> 通用统计 · Overall Stats</b>
      <br />
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=yan-sheng-li&show_icons=true&count_private=true&include_all_commits=true&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9&icon_color=22D3EE&border_color=30363D" />
        <img alt="yan-sheng-li 的 GitHub 通用统计卡片：展示 Star 总数、提交数、Follower 数与贡献数" src="https://github-readme-stats.vercel.app/api?username=yan-sheng-li&show_icons=true&count_private=true&include_all_commits=true&bg_color=FFFFFF&title_color=0284C7&text_color=1F2328&icon_color=0891B2&border_color=D0D7DE" />
      </picture>
    </td>
    <td width="50%" valign="top" align="center">
      <b><img height="18" src="https://img.icons8.com/fluency/48/chat.png" alt="常用语言图标" /> 常用语言 · Most Used Languages</b>
      <br />
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs?username=yan-sheng-li&layout=compact&langs_count=8&bg_color=0D1117&title_color=38BDF8&text_color=C9D1D9&icon_color=22D3EE&border_color=30363D" />
        <img alt="yan-sheng-li 的常用编程语言占比卡片：展示占比最高的前若干种语言及其百分比" src="https://github-readme-stats.vercel.app/api/top-langs?username=yan-sheng-li&layout=compact&langs_count=8&bg_color=FFFFFF&title_color=0284C7&text_color=1F2328&icon_color=0891B2&border_color=D0D7DE" />
      </picture>
    </td>
  </tr>
</table>

<h4 align="center"><img height="20" src="https://img.icons8.com/fluency/48/light-on.png" alt="连续贡献图标" />&nbsp; 连续贡献 · Contribution Streak</h4>
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=yan-sheng-li&background=0D1117&ring=38BDF8&fire=22D3EE&currStreakLabel=38BDF8&currStreakNum=C9D1D9&sideLabels=C9D1D9&sideNums=C9D1D9&dates=C9D1D9&stroke=30363D" />
    <img alt="yan-sheng-li 的连续贡献天数卡片：展示当前连续贡献天数与历史最长连续贡献天数" src="https://streak-stats.demolab.com/?user=yan-sheng-li&background=FFFFFF&ring=0284C7&fire=0891B2&currStreakLabel=0284C7&currStreakNum=1F2328&sideLabels=1F2328&sideNums=1F2328&dates=1F2328&stroke=D0D7DE" />
  </picture>
</div>

<!-- SECTION:STATS:END -->

<!-- SECTION:SOCIAL:START -->
<h2 align="center"><img height="28" src="https://img.icons8.com/fluency/48/link.png" alt="联系图标" />&nbsp; 联系我 · Connect With Me</h2>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:38BDF8,50:22D3EE,100:2DD4BF&height=3" alt="天蓝到青到薄荷的渐变分隔条" width="100%" />
</div>

<!--
  社交链接：<div align="center"> 内每个平台为 [![alt](shields.io badgeURL)](targetURL) 形式的静态 Markdown 超链接徽章（Property 11 / 需求 6.4）。
  每个徽章 = shields.io badge（style=for-the-badge，含平台 Logo logo=、平台名称文字标签、非空 alt）。
  - 个人网站 → https://www.your-site.com（含协议前缀绝对 URL，需求 6.1），主色天蓝 38BDF8。
  - Bilibili  → https://space.bilibili.com/<你的UID>（需求 6.2），官方品牌粉 FB7299。
  邮箱徽章：<your-email@example.com>，使用 mailto: 链接目标 + 邮箱图标 + 地址文本标签（满足需求 6.5）。
  markdown 徽章置于 <div align="center"> 内，前后留空行以确保 GitHub 正常渲染 Markdown 语法。
-->
<div align="center">

[![个人网站 www.your-site.com](https://img.shields.io/badge/个人网站-www.your-site.com-38BDF8?style=for-the-badge&logo=googlechrome&logoColor=white)](https://www.your-site.com)
[![Bilibili 主页 哔哩哔哩](https://img.shields.io/badge/Bilibili-哔哩哔哩-FB7299?style=for-the-badge&logo=bilibili&logoColor=white)](https://space.bilibili.com/<你的UID>)
[![Gitee 主页 码云](https://img.shields.io/badge/Gitee-码云-C71D23?style=for-the-badge&logo=gitee&logoColor=white)](https://gitee.com/<你的用户名>)
[![爱发电 主页 Afdian](https://img.shields.io/badge/爱发电-Afdian-2DD4BF?style=for-the-badge&logo=afdian&logoColor=white)](https://ifdian.net/a/<你的爱发电ID>)
[![邮箱 Email <你的邮箱>](https://img.shields.io/badge/邮箱_Email-<你的邮箱>-0891B2?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:<你的邮箱>)

</div>

<!-- SECTION:SOCIAL:END -->

<!-- SECTION:FOOTER:START -->
<h2 align="center"><img height="28" src="https://img.icons8.com/fluency/48/like.png" alt="感谢图标" />&nbsp; 感谢访问 · Thanks for Visiting</h2>
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:38BDF8,50:22D3EE,100:2DD4BF&height=3" alt="天蓝到青到薄荷的渐变分隔条" width="100%" />
</div>

<!--
  页脚收尾：与其它区块一致的居中标题 + 渐变分隔条已在上方给出。
  此处补充一句居中的感谢/收尾文字，呼应"青云"主题与开源精神，保持整体视觉一致性（需求 8.2）。
-->
<p align="center">感谢你抵达这里 · 愿代码与热爱同行 <img height="18" src="https://img.icons8.com/fluency/48/rocket.png" alt="火箭" /></p>

<p align="center"><sub>Designed with <img height="14" src="https://img.icons8.com/fluency/48/like.png" alt="爱心" /> by yan-sheng-li · Powered by GitHub Actions &amp; Open Source</sub></p>

<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2DD4BF,50:22D3EE,100:38BDF8&height=150&section=footer" alt="底部薄荷到天蓝渐变波浪装饰" />
</div>

<!-- SECTION:FOOTER:END -->
