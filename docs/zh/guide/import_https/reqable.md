# Reqable

## 证书安装

需要安装app生成的证书至系统里以实现https流量解析，详见[Reqable证书安装](https://reqable.com/zh-CN/docs/getting-started/installation/#mobile).

## 目标请求

仅需 FGO 登录时的请求，其网址为:

- 国服: 其中`line3-s2-ios-fate`随账号所在服务器(iOS/b 服/渠道服)以及所在地理位置等有所不同，最重要的是`_key=toplogin`

```:no-line-numbers
https://line3-s2-ios-fate.bilibiligame.net/rongame_beta//rgfate/60_1001/ac.php?_userId=xxxx&_key=toplogin
```

- 台服: 与国服类似，域名格式`https://line3-s1-all.fate-go.com.tw`，由于无台服账号，待确认
- 日服:

```:no-line-numbers
https://game.fate-go.jp/login/top?_userId=xxxx
```

- 美服:

```:no-line-numbers
https://game.fate-go.us/login/top?_userId=xxxx
```

找到目标请求后，切换到`响应 -> 响应体`页面，选择Text或JSON格式，点击复制按钮或下载按钮，再到Chaldea里导入。
