# Unlock-Emby-Surge

使用Surge解锁Emby的macOS/iOS客户端

# 测试适用版本

Surge：4.1.0(1298)
macOS：11.3正式版

emby：App Store官方1.9.9(2)

# 食用方法

1. 在App Store上下载官方的emby客户端

![](https://eggleader-1253446050.cos.ap-chengdu.myqcloud.com/image/20210428150505.png)

2. 在Surge客户端点击`解密`选项卡，然后点击`MitM主机名`后的➕，输入`www.mb3admin.com`，点击完成后再添加一个`mb3admin.com`。

![](https://eggleader-1253446050.cos.ap-chengdu.myqcloud.com/image/20210428150850.png)

3. 在Surge客户端点击`解密`选项，点击`生成新证书`，再点击`将证书安装到系统`，并输入macOS的开机密码，最后将最上方的`HTTPS解密`开关打开，*如果配置成功，会显示`CA证书已被系统信任`*。

![](https://eggleader-1253446050.cos.ap-chengdu.myqcloud.com/image/20210428151155.png)

4. 在Surge客户端点击`更多`选项，点击`模块`，点击`从URL安装模块`，输入下方网站，并点击`应用`。

```html
1213
```

5. 重新打开Surge的代理开关，打开Emby客户端，尽情使用吧！