# OpenVPN使用教程 {#task_pwr_wpy_wdb .task}

介绍如何使用OpenVPN工具进行测试。

先知平台上部分项目要求必须通过 VPN 来进行测试，当企业页面中出现如下提示框时，说明企业要求必须通过专用 VPN 来进行测试，否则无法通过漏洞审核。

![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/3300_zh-CN.jpg)

**说明：** 

Mac 环境下使用 OpenVPN 可能会出现 DNS 问题，导致无法解析域名，建议您尝试以下解决方法：

-   尝试直接通过 IP 对测试目标进行访问。
-   在 Mac 环境下，使用 Windows 虚拟机进行测试。

1.   单击下载 [OpenVPN工具压缩包](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/52078/cn_zh/1492660005214/vpn_file.zip) 到本地。 
2.   解压已下载的压缩包。 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/3301_zh-CN.jpg)

3.   双击运行 openvpn-install-2.3.14-I601-x86\_64.exe 文件，安装 OpenVPN 工具。 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/3302_zh-CN.jpg)

4.   安装完成后，运行 OpenVPN 工具。 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/3303_zh-CN.jpg)

5.   将已分配给您的账号密码，填入 password.txt 文件中并保存，第一行为帐号，第二行为密码。 
6.   修改 client.ovpn 文件，在`remote`后面添加 VPN 服务器的 IP 和端口，如 `remote 1.1.1.1 1194`。 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/3304_zh-CN.jpg)

7.   安装 ca.crt 证书文件，并将该证书添加至受信任的根证书。 

    **说明：** 手机和电脑端都需要手工导入该证书。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/3305_zh-CN.jpg)

8.   将已配置的 ca.crt、client.ovpn、password.txt 文件存放至 OpenVPN 安装目录下的 config 文件夹中，如 c:\\Program Files\\OpenVPN\\config。 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/3306_zh-CN.jpg)

9.   启动 OpenVPN 工具，双击菜单栏右下角图标。 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/3307_zh-CN.jpg)

    连接成功。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/3308_zh-CN.jpg)


