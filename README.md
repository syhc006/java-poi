# java-poi

**自动刷文档程序说明**

自动刷Word文档格式程序使用Java为基础语言，使用开源组件poi对Office Word文档结构进行解析，对格式不正确的内容予以纠正，实现效果如下：

 ![img](image/微信图片_20200410124809.png)![img](image/微信图片_20200410124814.png)

目前提供了两种方式方便大家使用

（1）客户端程序

![img](image/微信图片_20200410124819.png)


使用方法

a)    打开format.exe程序，显示WORD格式化文档窗体

b)    将需要刷格式文档拖动到WORD格式化文档窗体内，松开鼠标

c)    程序在当前文件夹生成另一个格式化好格式的文档

d)    点击格式化好格式的文档查看

（2）服务器程序

![img](image/微信图片_20200410124825.png)

使用方法

a)    打开测试服务器地址http://192.168.10.72:3000

b)    选择需要刷格式的文档，点击“提交”按钮，文件被上传到服务器刷新格式。

c)    当浏览器提示下载文件，选择好保存路径后点击“保存”按钮

d)    打开格式化好格式的文档查看

程序为特定结构设计，仅适用于编写标书格式内容，不能解决非标书各种格式，如需其他格式文档批量格式需重新定义和编写代码。