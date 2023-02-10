# Dude（大佬）

这是一款手工WEB渗透辅助工具，开发这款工具的动机主要是个人在日常进行渗透测试时，发现在进行WEB渗透这块主要工具还是WEB漏扫、浏览器、Burpsuite完成，在空闲的时候把经常使用到的功能集合成一个程序，期望能替代浏览器及Burpsuite的一些常用功能进行快速操作，其实还写了很多辅助的小工具但是鉴于如果把这些东西全塞进进去程序会变得很臃肿而且未必是常用的，后续会把这些小工具做成插件供大家在程序里有选择的调用。

# 功能介绍：
用户手册实在是懒得写（我错了...请等我的用户手册），粗略介绍一下主要功能和应用范围。

1. 网站浏览、数据监视
  提供常规的网站浏览，主要实现浏览器UserAgent和Cookie的快速修改，配合数据监视可精准定位重要请求以便进行后续的数据包修改，实在不满足还有F12控制台功能，实现更复杂的操作。
    ![网站浏览](https://user-images.githubusercontent.com/73023058/216890682-8df98fff-7f58-47c4-937e-faf1ca7aa8fd.png)
    ![数据监视](https://user-images.githubusercontent.com/73023058/216890669-cb6e7ef5-1c4e-4f4e-aab1-f29a1e5bf607.png)
   
2. 数据重放
提供数据改发包功能，在实际应用中什么POC验证、注入、上传、伪造IP、COOKIE都可以在这里实现，并具有插入荷载功能方便操作不可见字符和字符串进行编码加密等，后续更多的功能会增加。
    ![数据重放](https://user-images.githubusercontent.com/73023058/216890722-5171a8ce-2604-4503-b1f4-681a8d12b69d.png)
    
3. 数据爆破
提供灵活自定义的爆破功能，在数据重放的基础上实现自动化，主要是通过插入字典标记来实现各类型的爆破，例如账号密码爆破、文件爆破、路径爆破等等，字典标记可结合荷载标记直接让字典实现编码和加密。
    ![数据爆破](https://user-images.githubusercontent.com/73023058/216890747-b0dfd274-d110-497a-9255-d092ceda8e57.png)
    
# 插件列表
1. Dude Nmap GUI 下载地址：https://github.com/x364e3ab6/Dude/tree/main/插件列表/Nmap
    ![DudePlus_Nmap](https://user-images.githubusercontent.com/73023058/217595152-3b257f4c-bd3b-406a-994c-a3b8dd766063.png)

# 运行环境
.net framework 4.7.2 （Windows10 1709、Windows Server 1709 版本以上不用额外安装）

