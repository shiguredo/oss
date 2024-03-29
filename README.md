# 時雨堂のオープンソースソフトウェアについて

## Discord

時雨堂では Discord にコミュニティサーバーを持っています。

https://discord.gg/shiguredo

アイコンの設定をすることをお勧めします。

### 時雨堂メンバーや管理者による Discord の対応時間について

Discord への時雨堂メンバーや管理者による対応は、
時雨堂の営業時間である平日の午前 10:00-13:00 と午後 14:00-17:00 の対応になります。
リアクションで 👀 が付いたら確認済みですので、ゆっくりと反応をお待ちください。

### Sora の SDK やツールについて

Sora の SDK や Sora のツールは Sora を利用されている場合のみ対応します。
そのため、質問をするときは必ず Sora のバージョンを教えてください。

Sora のバージョンが分からない場合は、あらかじめ契約者に確認の上でお問い合わせください。

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
どの Discord チャネルへの投稿すべきかわからない場合、
`#help` チャネルでどのチャネルに投稿すべきかを確認してください。

時雨堂メンバーは **貢献ラベルを保持している方** からの質問を優先的に回答します。

プログラミング言語やフレームワークの利用方法については [Stack Overflow](https://stackoverflow.com/) などを利用してください。

### 問題があって困っている場合

何がわかれば問題が解決するかを教えてください。こちらで再現を行うため必ず問題の再現手順を共有してください。

### 使い方がわからなくて困っている場合

何がやりたくて困っているかを教えてください。
Gist などを利用してこちらがわかるように丁寧にお伝えください。

### カスタマイズ関連の質問

**カスタマイズ関連の質問に時雨堂メンバーまたは管理者は対応しません**

- カスタマイズに関する質問に対しては「カスタマイズ関連の質問には時雨堂メンバーまたは管理者は対応しません」と回答します
- Discord で質問すること自体は問題ありません

### ビルド関連の質問

**ビルド関連の質問に時雨堂メンバーまたは管理者は対応しません**

- ビルド済みバイナリを利用して下さい
- 自前でビルドしたい人は GitHub Actions の設定を参考にして下さい
- ビルドに関する質問に対しては「ビルド関連の質問には時雨堂メンバーまたは管理者は対応しません」と回答します
- Discord で質問すること自体は問題ありません

## バグ報告

バグ報告はまず Discord のそれぞれのチャネルへお願いします。
ただし、 Sora のライセンス契約の有無に関わらず、応答時間と解決を保証しませんのでご了承ください。

## GitHub Issues

Discord で相談されて、時雨堂メンバーまたは管理者から Issues へ報告を依頼されたときのみ利用してください。

## GitHub Pull-Request

改善や修正の Pull-Request を送りたい場合、まず Discord のそれぞれのチャネルへお願いします。

1 度マージした改善や修正は継続的にメンテナンスする必要があります。そのため「議論」と「説得」を求めます。
それが難しいと感じた場合は fork して利用してください。時雨堂の OSS は開発についてはクローズドです。

## 優先機能実装について

時雨堂が公開しているオープンソースソフトウェアは実装を予定している機能を「優先して実装する」という有償での依頼を受けているものがあります。

- [WebRTC SFU Sora JavaScript SDK](https://github.com/shiguredo/sora-js-sdk)
- [WebRTC SFU Sora DevTools](https://github.com/shiguredo/sora-devtools)
- [WebRTC SFU Sora iOS SDK](https://github.com/shiguredo/sora-ios-sdk)
- [WebRTC SFU Sora Android SDK](https://github.com/shiguredo/sora-android-sdk)
- [WebRTC SFU Sora Unity SDK](https://github.com/shiguredo/sora-unity-sdk)
- [WebRTC SFU Sora C++ SDK](https://github.com/shiguredo/sora-cpp-sdk)
- [WebRTC SFU Sora Python SDK](https://github.com/shiguredo/sora-python-sdk)
- [WebRTC SFU Sora C SDK](http://github.com/shiguredo/sora-c-sdk)
- [WebRTC Load Testing Tool Zakuro](https://github.com/shiguredo/zakuro)
- [Recording Composition Tool Hisui](https://github.com/shiguredo/hisui)
- [WebRTC Stats Collector Kohaku](https://github.com/shiguredo/kohaku)
- [Audio Streaming Gateway Suzu](https://github.com/shiguredo/suzu)
- [Prometheus exporter for WebRTC SFU Sora metrics](https://github.com/shiguredo/sora_exporter)
- [WebRTC Native Client Momo](https://github.com/shiguredo/momo)
- [Media Processors](https://github.com/shiguredo/media-processors)
- [webrtc-build](https://github.com/shiguredo-webrtc-build/webrtc-build)

優先機能実装を依頼できるのは WebRTC SFU Sora のライセンスを購入しているお客様のみとさせていただいております。

## サポートやカスタマイズについて

時雨堂が公開しているオープンソースソフトウェアのサポートやカスタマイズは、提供しておりません。

## 有償でのサポートについて

時雨堂が公開しているオープンソースソフトウェアの有償のサポートは、提供しておりません。

## 有償でのカスタマイズについて

時雨堂が公開しているオープンソースソフトウェアの有償でのカスタマイズは、提供しておりません。
