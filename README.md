# Dude Suite Web 渗透测试工具

Dude Suite 是一款集成化的Web渗透测试工具集，包含了Web渗透测试活动中使用频率非常高的功能，可以帮助我们高效地完成对Web应用程序的渗透测试和攻击。
测试人员可依据自身对漏洞及渗透测试技术的理解使用DudeSuite进行渗透测试工作，半自动Web渗透测试就目前的来说依然是主流，相比起全自动化的扫描器及批量化脚本可以在测试时具有更大的灵活性和准确性来挖掘复现Web应用中的安全风险。

程序核心功能为六个部分组成，分别是网站浏览、数据监视、结构分析、数据重放、数据爆破、漏洞验证、工具箱。分别负责几个常见的渗透测试业务场景：网页的浏览调试、浏览调试过程中访问及响应触发的网络数据(HTTP/S数据包)的监视捕获、网站结构扫描分析、网络数据的修改重放测试、基于网络数据重放的数据暴力破解枚举遍历及自定义POC漏洞验证、外部功能插件的增强、外置程序调用、自定义Web脚本的制作调用、个人网址收藏便捷访问。提供各类型得GUI图形化插件，所有功能设计时尽可能降低操作步骤及学习成本尽量实现填个地址一键完成，尽量不把时间浪费在调整参数和上网搜索命令示例上，把更多的时间用于思考。  

## 程序下载

**Beta v1.1.0.2**  
下载地址：https://codeload.github.com/x364e3ab6/DudeSuite/zip/refs/heads/main  

**Final v1.1.0.2**  
下载地址：https://github.com/x364e3ab6/DudeSuite/releases/download/v1.1.0.2/Dude_v1.1.0.2.zip

## 运行环境
1. 本机需已安装.Net Framework 4.7.2 （Windows10 1709、Windows Server 1709 版本以上无需额外安装.Net Framework）  
2. 本机需已安装Edge浏览器或Edge WebView2 Runtime （如不想安装Edge相关程序提高便携性可以进行程序绿化摆脱对Edge的依赖）  

## 程序绿化 
访问: https://developer.microsoft.com/zh-cn/microsoft-edge/webview2/#download-section ，下载“已修复版本 最新版本 x64”将文件解压到BrowserRuntime目录中，即可无需Edge依赖运行

## 插件下载  
访问: https://github.com/x364e3ab6/DudePlugins  

## Poc下载
访问: https://github.com/x364e3ab6/DudePoc  

## 更新提示 (v1.1.0.2) 2023.6.10
1. 【改进】针对“数据爆破”的并发线程收敛进行优化；
2. 【改进】针对“漏洞验证”的功能进行验证及优化；
3. 【修复】数据监视功能监听“特殊”的302跳转时丢失记录；
4. 【修复】POST和PUT请求头中存在Content-Length: 0 则自动计算Content-Length请求大小
5. 【新增】更新第一批WebPoc共97个，主要类别为Apache Struts2及Office Automation；
6. 【修复】对部分代码BUG、细节和效率进行优化。

## 界面演示

https://github.com/x364e3ab6/DudeSuite/assets/73023058/b0cf9088-a4f3-4c44-9b99-7f14505e9a25



