# 螃蟹云
这是螃蟹云的官方Github页面。不管你们怎么说，我们都已经将所有APP的源码发了出来。你可自行编译开发第三方版本。
Windows：/windows/[版本号，例如3.2]
Linux：/linux/[版本号]
Android：/android/[版本号]
下载站：/Download/index.html（可通过optioncrab.github.io/CrabCloudOffical/Download/index.html访问
# 关于API的使用说明

## 站外API

### 调取用户信息：https://api.crabhouse.top/apiv2/crabdisk/userdata.php

直接访问的错误：

<html>
    <head>_</head>
    <body>{"status":"failed"}</body>
</html>


成功访问：

{"status":"success","id":1,"created_at":"2020-07-05 10:05:05.829729143+08:00","updated_at":"2020-08-04 15:07:04.749974848+08:00","deleted_at":null,"email":"admin@cloudreve.org","nick":"\u8783\u87f9\u8c08\u79d1\u6280","password":"oHUySM4hwPiAg211:5eda26ec57e77f62a936b88db8896dc12f145bc5","group_id":1,"storage":8794686100,"open_id":"","two_factor":"","avatar":"file","options":"{\"preferred_policy\":1}","authn":"[{\"ID\":\"KK8\/lyPqOBQdHXGtYni\/QFEbpPMOa7sfmI0YSYHSW8U=\",\"PublicKey\":\"pAEDAzkBACBZAQDxzgC3cAdt8ex+Ymxn3IAg6KTT5eiFdPWHn\/TFKxAtcBeps5Kd4R\/eUHXJHb7XIgyf0azp9uSiYQL9fQYGiWmp6iXZgr88id8SnLW3luAS7MBGxHZgcaQRht0gjU1OvZHo32mVreRhBxsmsx0TXFjqfTI\/akVMZcJZhb1piBfSxnBnxGEaFmxa+iqsAPFnb+8CWXKpBY8AI8am6Jh7xNi3ZjyU0lnSNrWY7yeT\/CKXysnz5DpdM5Adm3P8ojnbq14+zQyqQ3OLyVN787s3UJxMVO8WbZKo\/zWzfI2do5fNqLx\/9jDofMCORq3jNfjvKm9EqJnILNFNxx0zGDj9AIXNIUMBAAE=\",\"AttestationType\":\"packed\",\"Authenticator\":{\"AAGUID\":\"YCiwF7HUTAK0s6\/Nr8lrsg==\",\"SignCount\":0,\"CloneWarning\":false}},{\"ID\":\"B194Dn1UpaCo\/a5NO6CQ8Vz5W4VQtMsaijJx2QXknCw=\",\"PublicKey\":\"pCBZAQDNPT\/bjxUnl5WHOyPUTShMxLvFiDcK77lUIW158FKOWwXaVFNHwcZj\/anW+p0EzwL6f\/e+Gx4zsWgrRtWjeCu9xdereoi1tVwnxJtPrCVEgdu4h8AUsWxtUAE2X3DDMUPdVaNcl4YiPRgy5Hlnm9m5f458Umfzyb6whZsyHIReQaQLzrBftWrzpf3RQnG6UwsM4oxqAp+19cECG3zubaCVT8FtJnr+VI0iLbGHYvbSkq\/3G6Y3WisVfM40sIhaTpK0lDiafCjDSyWJhfcODp7Rdq\/FV7UkaDP1ETx4S0mtIVtCGVO+KoZqLv0sklUe7EqaKyGaee6TOHVYVjn7sC1NIUMBAAEBAwM5AQA=\",\"AttestationType\":\"packed\",\"Authenticator\":{\"AAGUID\":\"YCiwF7HUTAK0s6\/Nr8lrsg==\",\"SignCount\":0,\"CloneWarning\":false}}]","score":0,"previous_group_id":0,"group_expires":null,"notify_date":null}
其中，nick这项无论中文英文全部是unicode，需要自行解密
#### 访问格式：https://api.crabhouse.top/apiv2/crabdisk/userdata.php?UserID=[用户邮箱]

## 站内API
### 目前状态未知，我也没搞明白
上传文件：api/v3/file/upload
文件列表：api/v3/file/list
站点配置：api/v/site/config
其他的自己摸索...

###提示：需要在可视化页面登录，否则直接返回401/403

# 提出Bug
请在Issues或者螃蟹云官方兔小巢反馈问题。QQ私信或者B站私信一概不回

# 赞助螃蟹云
## 第一种方法：购买VIP（赤裸裸的金钱捐助）
打开云盘，选择扩容，购买容量包，切换到VIP选项卡。
## 第二种方法：爱发电（同上）
https://afdian.net/@crabTech_
##第三种方法：B站投喂电池
@螃蟹谈科技
或者直接通过链接重定向：https://redirect.crabhouse.top/ref=11228

# 非常感谢你能看到这里！
