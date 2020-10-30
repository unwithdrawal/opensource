# SkyWay P2P Videochat /hyoi MVP

```
swift 4.0以上
Xcode 9.0以上
ios 9.0以上
Cocoapods 1.0.0以上

```

# opensource

NTT Communications より配布されているSkyWayのソースコードを、Apache License 2.0に基づき改変・再配布したものです。

## セットアップ
 
 ### cocoapods
 
SkyWayをインストールできる状態のpodfileが付属しています。
pod installしてください。

```
cd {REPO}
$ pod install
```


### APIKey,Domainの書き換え

https://webrtc.ecl.ntt.com/からAPIKeyとDomainを取得してください。
AppDelegateにそれぞれ追記してください。

```
// AppDelegate.swift
// https://webrtc.ecl.ntt.com/からAPIKeyとDomainを取得してください
var skywayAPIKey:String? = "xxx"
var skywayDomain:String? = "xxx"

```
