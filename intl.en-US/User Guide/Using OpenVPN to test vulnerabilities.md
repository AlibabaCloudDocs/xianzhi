# Using OpenVPN to test vulnerabilities {#task_pwr_wpy_wdb .task}

This article describes how to test vulnerabilities by using the OpenVPN tool.

Certain projects on the Crowdsourced Security Testing platform require that you use a VPN service when you perform testing. On the enterprise page, if certain VPN testing requirement message appears, it means that the company requires testing using a VPN. Without a VPN, your reports cannot pass the vulnerability review.

**Note:** 

OpenVPN on the Mac system may not resolve domain names correctly. We recommend that you try the following methods:

-   Directly enter the IP address to access the test target.
-   Use a Windows virtual machine to perform testing.

1.   Click to download the [OpenVPN compressed file](http://docs-aliyun.cn-hangzhou.oss.aliyun-inc.com/assets/attach/52078/cn_zh/1492660005214/vpn_file.zip) to a local folder. 
2.   Extract the compressed file. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/15356535293301_en-US.jpg)

3.   Run the openvpn-install-2.3.14-I601-x86\_64.exe file to install OpenVPN. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/15356535293302_en-US.jpg)

4.   Run OpenVPN. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/15356535293303_en-US.jpg)

5.   Enter the user name and password you have received in the password.txt file and save it. The first line is the user name and the second line is the password. 
6.   Modify the client.ovpn file. Add the IP address and port of the VPN server after `remote`. For example, `remote 1.1.1.1 1194`。 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/15356535293304_en-US.jpg)

7.   Install the ca.crt certificate file, and add the certificate to the trusted root certificates. 

    **Note:** You have to manually import certificates into your mobile device and PC to establish VPN connections.

8.   Save the configured ca.crt, client.ovpn, and password.txt files in the config folder of OpenVPN. For example, C:\\Program Files\\OpenVPN\\config. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/15356535293306_en-US.jpg)

9.   Double-click the application icon in the lower right-hand corner to run OpenVPN. 

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/15356535293307_en-US.jpg)

    The connection is now established.

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/12688/15356535293308_en-US.jpg)


