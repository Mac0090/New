##### 安装 x-ui  登陆信息 admin admin   IP/域名:54321  新建 vemss 路径选择 /ray 端口选择  80

```shell
bash <(curl -Ls https://raw.githubusercontent.com/vaxilu/x-ui/master/install.sh)
```

##### 解析域名到你的vps

##### 创建 cloudfront 优选 IP 分配  

测速地址： cachefly.cachefly.net

![](https://cdn.jsdelivr.net/gh/Mac0090/New/images/cloudfront/speed.png)

![](https://cdn.jsdelivr.net/gh/Mac0090/New/images/cloudfront/all.png)

##### 优选 IP 优选工具 下载 https://github.com/XIU2/CloudflareSpeedTest

##### cloudfront 的 IP 段 https://raw.githubusercontent.com/cnmeeia/aws-cft-ip/main/ip.txt

![](https://cdn.jsdelivr.net/gh/Mac0090/New/images/cloudfront/wjj.png)

```shell
➜  '/Users/meeia/Downloads/CloudflareST_darwin_amd64/CloudflareST(工具路径)' -t 1 -url https://换成上一步获取的域名.cloudfront.net//100mb.test 
```

##### 创建cloudfront 为 vmess分配

![](https://cdn.jsdelivr.net/gh/Mac0090/New/images/cloudfront/vmess.png)

![](https://cdn.jsdelivr.net/gh/Mac0090/New/images/cloudfront/all.png)

##### 修改vmess IP为优选的最佳 ip   混淆域名修改 cloudfront 为 vmess分配的 域名
