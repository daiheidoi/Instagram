# Instagram_clone
インスタグラムクローンのテスト作成

## しなければいけないこと
### COCOAPODS
```
gem install cocoapods
pod install
```

### AdobeCreativeSDK
https://creativesdk.adobe.com/downloads.html

上記からアカウント登録後、SDK落とす。
SDKを`AdobeSDK`ディレクトリ作って格納する

```
CLIENT_SECRET
API_KEY
```

上記をキーにした`Adobe-sdk-Info.plist`を生成

### Firebase
https://console.firebase.google.com/?hl=ja

上記からFirebase設定を行い、Plistを落とす

### `AdobeCreativeSDK``Firebase`のPlistを`Plist`ディレクトリを作り、格納
