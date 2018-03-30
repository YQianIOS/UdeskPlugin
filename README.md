### UdeskPlugin
udesk集成插件

```
/**
* 必传值
* sdktoken：唯一标识，用来识别身份
* nickName：用户昵称(optional)
* customerUrl：用户图像（optional）
* domain：域名
*/

let goodsInfo = {sdktoken: '',nickName: '',customerUrl: '',appId:'',appKey: '',domain: ''};

cordova.exec(success, faild, "UdeskPlugin", "uDeskMethod", [goodsInfo]);

```

