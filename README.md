# Sitemon
项目名称：Sitemon
    
项目描述：
    Sitemon项目主要以C++ Socket编程技术为基础，借助Windows平台下ws2_32.lib 与wininet.lib网络库进行相关的网络技术处理，其主要功能是持续监控网站是否可以正常访问，同时也提供了测试网络延迟、发送邮件给特定人员以及下载网站文件等的功能，可以在第一时间内发现网站出现的问题，便于服务端工作人员进行快速处理，给用户带来更优质的使用体验，更是便于网站的管理。

项目功能列表：
（1）监控网络是否可以正常访问（monitor函数）
（2）测试网络延迟（附加在monitor函数实现中）
（3）发送邮件（sendMail函数）
（4）对邮件加密发送（EncodeBase6函数，ConvertToBase64函数，Base64Date6结构体）
（5）下载网站HTML源代码文件，可选择性地将源代码保存在指定文件中（GetHtml函数）


项目配置说明：
    项目测试平台为Windows10下Microsoft Visual Studio 2017，Windows SDK版本为10.0.15063.0，平台工具集为Visual Stutio 2017（v141），字符集为Unicode字符集。