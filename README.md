# XMR-encrypt
加密门罗币账号、密码、助记码等关键恢复钱包的信息，生成一把钥匙、和加密文件，避免明文存储在电脑上
（本软件所有加解密操作都在你本地）


# 开发背景
在没有本软件之前，你的账号信息存在哪？大脑或者明文存储在电脑上？

人的记忆以及磁盘不是100%可靠，人有可能忘事、磁盘可能坏了、你的明码文件被别人看到了，对于有大量门罗币的玩家，
需要将账号信息保密的存储起来，就好像金融大鳄把钱放保险柜、保险柜的钥匙放另一个地方，任意
一个泄露都不会导致金额损失。


# 使用方法
将本项目下载到任意路径下，双击打开index.html,即可在浏览器中进行操作

## 加密
填写完助记码(seed）、钱包恢复高度（restore height）、钱包地址（Public address）、View秘钥(View key)、
Spend秘钥(Spend key)，点击加密按钮即可生成机密秘钥和机密文本
## 解密
填写生成的加密秘钥、生成的加密字符即可反向解密出门罗币的账号信息

建议将生成的加密秘钥、生成的加密字符分开存储在不同的地方，比如前者存手机，后者存云盘。

下面为具体的演示：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20201229121733944.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzMwMDU0OTYx,size_16,color_FFFFFF,t_70)
