# 時雨堂のオープンソースソフトウェアについて

## 開発について

時雨堂のオープンソースソフトウェアはコードはオープンですが、開発についてはオープンではありません。
そのため Discord での相談なしの Issue や Pull-Request はコメントなしでクローズします。

なにかある場合は、まずは Discord にてご相談してください。

### Lua の開発スタイルを参考にしています

[Lua はオープンソフトウェアだが、オープン開発されたことは一度もない](https://medium.com/@voluntas/lua-%E3%81%AF%E3%82%AA%E3%83%BC%E3%83%97%E3%83%B3%E3%82%BD%E3%83%95%E3%83%88%E3%82%A6%E3%82%A7%E3%82%A2%E3%81%A0%E3%81%8C-%E3%82%AA%E3%83%BC%E3%83%97%E3%83%B3%E9%96%8B%E7%99%BA%E3%81%95%E3%82%8C%E3%81%9F%E3%81%93%E3%81%A8%E3%81%AF%E4%B8%80%E5%BA%A6%E3%82%82%E3%81%AA%E3%81%84-61ea83ef96f7)

## ライセンスについて

時雨堂が公開しているオープンソースソフトウェアはすべて Apache License 2.0 で公開しています。

[Apache License, Version 2\.0](https://www.apache.org/licenses/LICENSE-2.0)

## バージョン番号について

```
YYYY.RELEASE.FIX
```

- YYYY は年
- RELEASE はその年にリリースした回数
- FIX は 0 から始まり、バグフィックス対応時にインクリメントする
- バージョン例
    - 2021.1.0
    - 2021.3.1

### Canary バージョンについて

```
YYYY.RELEASE.FIX-canary.CANARY-RELEASE
```

- リリース前に Canary として開発中のバージョンを定期的にリリースすることがあります
- CANARY-RELEASE は 0 から始まり、リリースされるまで 1,2,3... と増えていきます

- バージョン例
    - 2021.1.0-canary.0
    - 2021.3.1-canary.3

## 言語

時雨堂メンバーまたは管理者は日本語以外には対応しません。

## 質問

**ドキュメントを読んだり、実際に動かしてみてから質問してください**

質問は Discord のそれぞれのチャネルへお願いします。

時雨堂メンバーは **貢献ラベルを保持している方** からの質問を優先的に回答します。

プログラミング言語やフレームワークの利用方法については [Stack Overflow](https://stackoverflow.com/) などを利用してください。

### 問題があって困っている場合

何がわかれば問題が解決するかを教えてください。

### 使い方がわからなくて困っている場合

何がやりたくて困っているかを教えてください。

### ビルド関連の質問

**ビルド関連の質問には対応しません**

- ビルド済みバイナリを利用して下さい
- 自前でビルドしたい人は GitHub Actions の設定を参考にして下さい

## バグ報告

バグ報告はまず Discord のそれぞれのチャネルへお願いします。
ただし、 Sora のライセンス契約の有無に関わらず、応答時間と解決を保証しませんのでご了承ください。

## GitHub Issues

Discord で相談されて、時雨堂メンバーまたは管理者から Issues へ報告を依頼されたときのみ利用してください。

## GitHub Pull-Request

改善や修正 Pull-Request はまず Discord のそれぞれのチャネルへお願いします。

1 度マージした改善や修正は継続的にメンテナンスする必要があります。そのため「議論」と「説得」を求めます。
それが難しいと感じた場合は fork して利用してください。時雨堂の OSS は開発についてはクローズドです。

## 優先機能実装について

時雨堂が公開しているオープンソースソフトウェアは実装を予定している機能を「優先して実装する」という有償での依頼を受けているものがあります。

- [WebRTC SFU Sora JavaScript SDK](https://github.com/shiguredo/sora-js-sdk)
- [WebRTC SFU Sora デモアプリ](https://github.com/shiguredo/sora-demo)
- [WebRTC SFU Sora iOS SDK](https://github.com/shiguredo/sora-ios-sdk)
- [WebRTC SFU Sora Android SDK](https://github.com/shiguredo/sora-android-sdk)
- [WebRTC SFU Sora Unity SDK](https://github.com/shiguredo/sora-unity-sdk)
- [WebRTC Load Testing Tool Zakuro](https://github.com/shiguredo/zakuro)
- [Recording Composition Tool Hisui](https://github.com/shiguredo/hisui)
- [WebRTC Stats Collector Kohaku](https://github.com/shiguredo/kohaku)
- [WebRTC Native Client Momo](https://github.com/shiguredo/momo)
- [webrtc-build](https://github.com/shiguredo-webrtc-build/webrtc-build)

優先機能実装を依頼できるのは WebRTC SFU Sora のライセンスを購入しているお客様のみとさせていただいております。

## 有償でのサポートについて

時雨堂が公開しているオープンソースソフトウェアは、有償のサポートを提供しておりません。

## 有償でのカスタマイズについて

時雨堂が公開しているオープンソースソフトウェアは、有償でのカスタマイズを提供しておりません。

## Discord

時雨堂では Discord にコミュニティサーバを持っています。

https://discord.gg/shiguredo

アイコンの設定をすることをお勧めします。

### 非アクティブメンバーのキック

定期的に 30 日間オンラインになっていない非アクティブメンバーをキックしています。

もちろん、再度参加は可能ですので、ご安心下さい。

### Sora SDK について

Sora の SDK は Sora を利用している場合のみ対応をします。
そのため、質問をするときは必ず Sora のバージョンを教えてください。

Sora Labo の場合は Sora Labo と GitHub アカウントをお知らせ下さい。
