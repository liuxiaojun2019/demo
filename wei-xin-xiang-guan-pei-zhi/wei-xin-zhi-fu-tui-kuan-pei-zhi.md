# 微信支付退款配置

**1、微信支付配置**

>第一步，登录商城后台，设置->交易设置->支付配置 ，选择微信支付，点击配置进入到微信支付参数配置界面。

![](/assets/微信支付的位置.png)

![](/assets/微信支付参数配置.png)

从应用ID和应用密钥下面的提示可以看出，微信支付ID和密钥为微信公众号的APPID和APP密钥，配置上即可。

>第二步，配置微信商户API密钥，登陆微信商户平台，点击账户中心，左侧导航栏找到API安全，需要安装证书。

![](/assets/安装操作证书.png)

然后安装控件。

![](/assets/安装控件.png)

申请安装操作证书。

![](/assets/申请安装操作证书.png)

最后设置API密钥。

![](/assets/设置api密钥.png)

>第三步，设置商户号。在商户平台帐户中心找到商户号，配置即可。

![](/assets/商户号.png)

>第四步,在后台找到支付授权目录，在商户平台，产品中心->开发配置,添加支付授权目录。

![](/assets/添加支付授权目录.png)

注意事项：

![](/assets/授权目录填写格式.png)

配置正确，开启微信支付即可。


** 2、微信原路退款配置**

>第一步，在商户平台->账户中心,下载退款证书。

![](/assets/下载退款证书.png)

>第二步,将下载好的退款证书上传到网站根目录。

![](/assets/退款证书上传网站根目录.png)

如：用宝塔直接上传

![](/assets/根目录上传文件.png)

>第三步，在商城系统后台配置退款证书在网站根目录的绝对路径，如：Linux系统"root/cert/apiclient_cert.pem"或window系统"d:\cert\apiclient_cert.pem"

如图：

![](/assets/退款绝对路径.png)

配置正确，开启微信退款即可。



