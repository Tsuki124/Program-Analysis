# Program Analysis
Index
- Basic Knowledge
  - Static program analysis
    - Compilation Principle(编译原理)
  - Static Application Security Testing(SAST)
- Related tool
  - [CodeQL](https://github.com/pen4uin/Program-Analysis/#codeql)
  - [Soot](https://github.com/pen4uin/Program-Analysis/#soot)
  - [Gadget Inspector](https://github.com/pen4uin/Program-Analysis/#gadget-inspector)
  - [FlowDroid](https://github.com/pen4uin/Program-Analysis/#flowdroid)
## Basic Knowledge
### Static Program Analysis
- 视频教程
  - Program Analysis (Winter 2021) https://www.bilibili.com/video/BV1aL4y167vY
  - 南京大学《软件分析》 https://www.bilibili.com/video/BV1b7411K7P4

- 相关文章
  - [Java静态分析&gadgetinspector改造扫描sb](https://lfysec.top/2020/08/03/Java%E9%9D%99%E6%80%81%E5%88%86%E6%9E%90&gadgetinspector%E6%94%B9%E9%80%A0%E6%89%AB%E6%8F%8Fsb/)
  - [从AST到100个某知名OA前台注入](https://www.freebuf.com/articles/web/237291.html)
#### Compilation Principle

视频教程
- https://time.geekbang.org/column/intro/219

相关Github
- https://github.com/KpLi0rn/LearnCompiler

相关文章
- 编译原理初学者入门指南 https://mp.weixin.qq.com/s/ZTxVG6KG-4vzbvclC_Q1LQ
- 基本功 | Java即时编译器原理解析及实践 https://mp.weixin.qq.com/s/7PH8o1tbjLsM4-nOnjbwLw
- Java编译原理(javac) https://mp.weixin.qq.com/s/0KaYN30yn-EaMpmlG6RV_w
- Java 动态编译原理深入研究 https://mp.weixin.qq.com/s/QmyNwHQ1Vm2N-QDc8GqyAg
- 深入分析Java的编译原理 https://mp.weixin.qq.com/s/nS7HbYsEPFoZBaBi2Y3r0Q

#### Static Application Security Testing(SAST)
相关文章
- 58集团白盒代码审计系统建设实践系列1：技术选型 https://www.anquanke.com/post/id/235226
- 58集团白盒代码审计系统建设实践2：深入理解SAST https://www.anquanke.com/post/id/237801
## 相关工具
### Codeql
视频教程
- Github
  - [CodeQL Live Episode 1](https://www.youtube.com/watch?v=AMzGorD28Ks)
  - [LiveQL Episode 2 - The Rhino in the room.](https://www.youtube.com/watch?v=wPqK-Ealz-0)
  - [Community-powered security analysis with CodeQL - GitHub Universe 2020](https://www.youtube.com/watch?v=Y6PjAaZKNYk)
  - [Finding security vulnerabilities in JavaScript with CodeQL - GitHub Satellite 2020](https://www.youtube.com/watch?v=pYzfGaLTqC0)
  - [Finding security vulnerabilities in Java with CodeQL - GitHub Satellite 2020](https://www.youtube.com/watch?v=nvCd0Ee4FgE)
  - [Security: Workshop 2 - Finding security vulnerabilities in C/C++ with CodeQL](https://www.youtube.com/watch?v=eAjecQrfv3o)
  - [Workshop: Finding security vulnerabilities in Java with CodeQL: All roads lead to RCE](https://www.youtube.com/watch?v=h3f1s8ACfPo)
- Other
  - [CodeQL as an Audit Oracle (workshop) by Alvaro Muñoz during HacktivityCon 2021](https://www.youtube.com/watch?v=-bJ2Ioi7Icg)
  - [h@cktivitycon 2020: Discover vulnerabilities with CodeQL](https://www.youtube.com/watch?v=NygVkQKmGwI)
  - [Securing your code with CodeQL with Sasha Rosenbaum! - OWASP DevSlop](https://www.youtube.com/watch?v=G_yDbouY0tM)
  - [$3,000 CodeQL query for finding LDAP Injection - Github Security Lab - Hackerone](https://www.youtube.com/watch?v=qStzSfsEQGQ)
  - [CodeQL-youtube](https://www.youtube.com/playlist?list=PLX8G9idOAfzg3uTfdAgDkybK9CG71vsaq)
  - [Variant analysis to find SQL injection using CodeQL - CVE-2019-6986](https://www.youtube.com/watch?v=uUvhplNbQOI)
  - [Discover vulnerabilities with CodeQL by: Boik Su (@boik_su)](https://www.youtube.com/watch?v=UDDHXBFbuqo)

入门文章

- [CodeQL query help for Java](https://codeql.github.com/codeql-query-help/java/)
- [CodeQL从入门到放弃](https://www.freebuf.com/articles/web/283795.html)
- [Learn Codeql With L4yn3](https://bingbingzi.cn/learn-codeql-with-l4yn3/)
- [Codeql 挖洞？](https://mp.weixin.qq.com/s/-4E08dNeCdsc51VLE9qMAQ)
- [Mining an SQL Injection Vulnerability Using CodeQL](https://bingbingzi.cn/learn-codeql-with-l4yn3/) 基于java-sec-code项目
- [CodeQL初入](https://kiprey.github.io/2020/12/CodeQL-setup/)
- [使用 CodeQL 分析闭源 Java 程序](https://paper.seebug.org/1324/)
- [CodeQL学习笔记](http://blog.gamous.cn/post/codeql/)
- [CodeQL入门](https://aluvion.gitee.io/2021/05/29/CodeQL%E5%85%A5%E9%97%A8/)
- [CodeQL入门2](https://aluvion.gitee.io/2021/05/31/CodeQL%E5%85%A5%E9%97%A82/)
- [CodeQL笔记](https://lfysec.top/2020/06/03/CodeQL%E7%AC%94%E8%AE%B0/)
- [Codeql 入门](https://www.faiz2035.top/posts/codeql-getting-started/)
- [代码分析平台CodeQL学习手记-系列](https://www.4hou.com/posts/o6wX)
- https://lingze.xyz/pages/1948eb/
- [codeql学习——污点分析](https://xz.aliyun.com/t/7789)
- [CodeQL 快速上手](https://www.yuque.com/docs/share/738555ae-258e-4f27-8818-6024b8225488?#)
- [CodeQL学习笔记-by fynch3r](https://fynch3r.github.io/categories/CodeQL/)
- [从Java反序列化漏洞题看CodeQL数据流](https://www.anquanke.com/post/id/256967)
- [利用CodeQL寻找Java Deserialization Vulnerabilities](https://uxss.net/2020/05/04/%E5%88%A9%E7%94%A8CodeQL%E5%AF%BB%E6%89%BEJava%20Deserialization%20Vulnerabilities/)
- [Codeql分析Vulnerability-GoApp](https://www.freebuf.com/articles/web/253491.html)
- https://blog.ycdxsb.cn/categories/research/codeql/
- [codeql学习笔记1](https://mp.weixin.qq.com/s/KA-s62tMnoqkJwVjxrDYuQ)
- [codeql学习笔记2](https://mp.weixin.qq.com/s/JzAAsiuOr0QdL5nEfQv1fg)
- [Practical Introduction to CodeQL](https://jorgectf.gitlab.io/blog/post/practical-codeql-introduction/)
- [CodeQL上手笔记](https://mp.weixin.qq.com/s/aU9Gq_xRgAXqU-bwAvMmig)
- [为 CodeQL 自定义规则编写测试文件](https://mp.weixin.qq.com/s/rdLwBJrhDcYQFB5_gUitMQ)
- [CodeQL快速上手](https://mp.weixin.qq.com/s/9vWSKVolqR8P1gJhN4pEOQ)
- [CodeQL检测SpringBoot应用敏感信息的返回](https://mp.weixin.qq.com/s/7wJKMVyc36U-PciZGmjrcg)
- [codeql入门指南](https://mp.weixin.qq.com/s/JIBlYW5wVg13Hyk-PmFPXA)
- [白盒审计之CodeQL](https://mp.weixin.qq.com/s/q426UdHTxgux5iAlglFwPA)
- [CodeQL官方教程中几道QL练习题](https://ovi3.github.io/2021/03/04/codeql-exercises-from-ql-tutorial/)
- https://codeql.github.com/docs/writing-codeql-queries/ql-tutorials/#ql-tutorials
- [CodeQL 试用](https://anemone.top/whitebox-CodeQL%E5%88%9D%E6%8E%A2/)
- [Codeql 入门](https://mp.weixin.qq.com/s/cxsjCyIXcgVphIcCqTDqJw)
- [Codeql 入门 java-sec-code项目](https://www.faiz2035.top/posts/codeql-getting-started/)

实际案例(基于CVE漏洞)

- [深入学习CodeQL by security_lab](https://kiprey.github.io/2020/12/secLab-CodeQL-learning/)
- [Using CodeQL to detect client-side vulnerabilities in web applications](https://raz0r.name/articles/using-codeql-to-detect-client-side-vulnerabilities-in-web-applications/)
- [Deep-in-codeql](https://jimp.top/Deep-in-codeql/)
- [CodeQL从0到1（内附Shiro检测演示）](https://www.anquanke.com/post/id/255721)
- [CodeQL 的学习以及尝试漏洞挖掘](https://bestwing.me/codeql.html)
- [CodeQL漏洞挖掘实战](https://blog.rabit.pw/2020/codeql-uboot-bug-hunting/)
- [CodeQL：“查询”你的下一个漏洞](https://www.anquanke.com/post/id/212305)
- [S2-057漏洞原作者自述：如何利用自动化工具发现5个RCE](https://www.anquanke.com/post/id/157583)
- [使用codeql 挖掘 ofcms](https://www.anquanke.com/post/id/203674)
- [CodeQL 若干问题思考及 CVE-2019-3560 审计详解](https://lennysec.github.io/codql-and-cve-2019-3560/)
- [我是如何使用codeql挖掘CVE-2021-31856Meshery-sqli的](https://ssst0n3.github.io/post/%E7%BD%91%E7%BB%9C%E5%AE%89%E5%85%A8/%E5%AE%89%E5%85%A8%E6%B5%8B%E8%AF%95/%E6%B5%8B%E8%AF%95%E6%96%B9%E6%B3%95/%E8%87%AA%E5%8A%A8%E5%8C%96%E6%B5%8B%E8%AF%95/%E9%9D%99%E6%80%81%E4%BB%A3%E7%A0%81%E6%89%AB%E6%8F%8F/AST/codeql/codeql%E6%BC%8F%E6%B4%9E%E6%8C%96%E6%8E%98%E6%88%96%E5%88%86%E6%9E%90%E5%AE%9E%E8%B7%B5/%E6%88%91%E6%98%AF%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8codeql%E6%8C%96%E6%8E%98CVE-2021-31856Meshery-sqli%E7%9A%84.html)
- [使用 CodeQL 挖掘 CVE-2020-9297](https://xz.aliyun.com/t/7979)
- [如何用CodeQL数据流复现 apache kylin命令执行漏洞](https://xz.aliyun.com/t/8240)
- [使用codeql挖掘fastjson利用链](https://xz.aliyun.com/t/7482)
- [CodeQL 污点分析寻找fastjson jndi链](https://blog.sometimenaive.com/2020/05/21/find-fastjson-jndi-gadget-by-codeql-tainttracking/)
- [CodeQL with CVE-2021-2471](https://m0d9.me/2021/11/01/CodeQL-CVE-2021-2471/)
- [Variant analysis to find SQL injection using CodeQL - CVE-2019-6986](https://www.youtube.com/watch?v=uUvhplNbQOI)
- [Hunting for XSS with CodeQL](https://medium.com/codex/hunting-for-xss-with-codeql-57f70763b938)
- [如何用CodeQL数据流复现 apache kylin命令执行漏洞](https://mp.weixin.qq.com/s/9GgV4a5tgHH0zHOePqwySQ)
- [CODEQL数据流分析Hadoop](https://mp.weixin.qq.com/s/CyhWw4t8LdGhCpixacb6Xg)
- [漏洞精粹 | 复盘利用 codeql '神器'挖掘 Ognl 漏洞](https://mp.weixin.qq.com/s/9GgV4a5tgHH0zHOePqwySQ)
- [CodeQL挖掘React应用的XSS实践](https://mp.weixin.qq.com/s/zH0EhOLFgwgFk8rIWezk-g)
- [我是如何使用codeql发现CVE-2021-31856 Meshery sql注入的](https://mp.weixin.qq.com/s/Po35ErrD3RXCXhecFEPBTw)
- [利用CodeQL分析并挖掘Log4j漏洞](https://mp.weixin.qq.com/s/JYco8DysQNszMohH6zJEGw)

相关Github

- https://github.com/advanced-security/codeql-queries
- https://github.com/safe6Sec/CodeqlNote
- https://github.com/github/securitylab/tree/main/CodeQL_Queries
- https://github.com/SummerSec/learning-codeql
- https://github.com/SummerSec/LookupInterface
- https://github.com/githubsatelliteworkshops/codeql
- https://github.com/iflody/codeql-workshop CodeQL Workshop: Find bug in apache struts 2
- https://github.com/haby0/mark
- https://github.com/Semmle/SecurityQueries
- https://github.com/cldrn/codeql-queries
- https://github.com/hac425xxx/codeql-snippets
- https://github.com/msrkp/codeql_for_gadgets
- 

个人笔记

Codeql ships with(提供) extensive(大量的) libraries to empower(支持) variant(变量) analysis,
- Static Analysis
- Data Flow Analysis
- Taint Analysis(污点分析)
- CFG Analysis

将经验的能力扩大，将自己对漏洞的理解建模，覆盖更多的一类正在被发现的漏洞，就像我之前所听到的那样，“漏洞就在那里，”

### Soot

入门文章
- Soot使用笔记 https://www.cnblogs.com/xine/p/14511818.html
- 使用soot生成程序流程图和IR文件 https://www.jianshu.com/p/7444be64d5c9
- http://pkuduo.cn/blog/2018/05/08/SOOT/
- Soot的安装与使用 https://www.cnblogs.com/crossain/p/12813643.html
- 阅读笔记 | The Soot framework for Java program analysis:a retrospective  https://blog.csdn.net/cat_xing/article/details/115049644
- FlowDroid架构剖析 https://blog.csdn.net/qq_37206105/article/details/119334544
相关Github
- https://github.com/PL-Ninja/MySootScript
- https://github.com/noidsirius/SootTutorial


实际案例
- 利用Soot对APK插桩实践 https://www.cnblogs.com/xine/p/14533697.html

### Gadget Inspector
- https://github.com/JackOfMostTrades/gadgetinspector

### FlowDroid
- https://github.com/secure-software-engineering/FlowDroid

相关文章
- [FlowDroid 工具介绍和试用（草稿）](http://yufeiyang1995.github.io/FlowDroid%E4%BB%8B%E7%BB%8D-%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90%E5%8F%8A%E5%8A%9F%E8%83%BD%E4%BF%AE%E6%94%B9)
