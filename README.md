# 時雨堂のオープンソースソフトウェアについて

## 開発について

時雨堂のオープンソースソフトウェアはコードはオープンですが、開発についてはオープンではありません。
そのため Discord での相談なしの Issue や Pull-Request は閉じます。

なにかある場合は、まずは Discord にてご相談してください。

### Lua の開発スタイルを参考にしています

[Lua はオープンソフトウェアだが、オープン開発されたことは一度もない](https://medium.com/@voluntas/lua-%E3%81%AF%E3%82%AA%E3%83%BC%E3%83%97%E3%83%B3%E3%82%BD%E3%83%95%E3%83%88%E3%82%A6%E3%82%A7%E3%82%A2%E3%81%A0%E3%81%8C-%E3%82%AA%E3%83%BC%E3%83%97%E3%83%B3%E9%96%8B%E7%99%BA%E3%81%95%E3%82%8C%E3%81%9F%E3%81%93%E3%81%A8%E3%81%AF%E4%B8%80%E5%BA%A6%E3%82%82%E3%81%AA%E3%81%84-61ea83ef96f7)

## ライセンスについて

時雨堂が公開しているオープンソースソフトウェアはすべて Apache License 2.0 で公開しています。

[Apache License, Version 2\.0](https://www.apache.org/licenses/LICENSE-2.0)

## バージョン番号について

```
YYYY.RELEASE[.FIX]
```

- YYYY は年
- RELEASE はその年にリリースした回数
- FIX はオプションでバグフィックス対応のみのアップデートに利用
- npm などのバージョンの形式が固定されている場合は `YYYY.RELEASE.0` を利用することがあります
    - YYYY.RELEASE と YYYY.RELEASE.0 は同一です
- バージョン例
    - 2021.1
    - 2021.1.0
    - 2021.3

### Canary バージョンについて

```
YYYY.RELEASE[.FIX]-canary.CANARY-RELEASE
```

- リリース前に Canary として開発版を定期的にリリースすることがあります
- CANARY-RELEASE は 0 から始まり、リリースされるまで 1,2,3... と増えていきます

- バージョン例
    - 2021.1-canary.0
    - 2021.3.1-canary.3

## 言語

時雨堂メンバーまたは管理者は日本語以外には対応しません。

## 質問

**ドキュメントを読んでから質問してください**

質問は Discord のそれぞれのチャネルへお願いします。

時雨堂メンバーは **誰かの質問に回答した人からの質問** しか回答しません。

### ビルド関連の質問

**ビルド関連の質問には対応しません**

- ビルド済みバイナリを利用して下さい
- 自前でビルドしたい人は GitHub Actions の設定を参考にして下さい

## 改善希望やバグ報告

改善希望やバグ報告はまず Discord のそれぞれのチャネルへお願いします。
ただし、 Sora のライセンス契約の有無に関わらず、応答時間と解決を保証しませんのでご了承ください。

## GitHub Issues

Discord で相談されて、時雨堂メンバーまたは管理者から Issues へ報告を依頼されたときのみ利用してください。

## GitHub Pull-Request

改善や修正 Pull-Request はまず Discord のそれぞれのチャネルへお願いします。

1 度マージした改善や修正は継続的にメンテナンスする必要があります。そのため「議論」と「説得」を求めます。
それが難しいと感じた場合は fork して利用してください。時雨堂の OSS は開発についてはクローズドです。

## 優先機能実装について

時雨堂が公開しているオープンソースソフトウェアの一部は実装を予定している機能を「優先して実装する」という有償での依頼を受けているものがあります。

- Sora Unity SDK
- WebRTC Native Client Momo

優先機能実装を依頼できるのは WebRTC SFU Sora のライセンスを購入しているお客様のみとさせていただいております。

## 有償でのサポートについて

時雨堂が公開しているオープンソースソフトウェアは、有償のサポートを提供しておりません。

## 有償でのカスタマイズについて

時雨堂が公開しているオープンソースソフトウェアは、有償でのカスタマイズを提供しておりません。

## Discord

時雨堂では Discord にコミュニティを持っており、３つのサーバを管理しています。

- OpenMomo サーバ
    - OpenMomo プロジェクトのサーバ
    - https://discord.gg/gmEuZye
- OpenAyame サーバ
    - OpenAyame プロジェクトのサーバ
    - https://discord.gg/mDesh2E
- Sora Labo / Sora 関連 OSS
    - Sora Labo サービスと Sora SDK のサーバ
    - https://discord.gg/k68nkRR

それぞれのオープンソース向けのチャネル向けにも招待 URL を用意してありますが、
上記 3 つのサーバに参加した場合は、個別の参加は不要です。

### Sora JavaScript SDK

Sora Labo / Sora SDK サーバ の #javascript チャネル

https://discord.gg/uZ5wgHE

### Sora iOS SDK

Sora Labo / Sora SDK サーバ の #ios チャネル

https://discord.gg/Ac9fJ9S

### Sora Android SDK

Sora Labo / Sora SDK サーバ の #android チャネル

https://discord.gg/QWUKD2f

### Sora Unity SDK

Sora Labo / Sora SDK サーバ の #unity チャネル

https://discord.gg/pFPQ5pS

### Sora E2EE ライブラリ

Sora Labo / Sora SDK サーバ の #e2ee チャネル

https://discord.gg/EbbB59s

### Sora デモ機能

Sora Labo / Sora SDK サーバ の #sora-demo チャネル

https://discord.gg/wYqeSyF

### WebRTC Load Testing Tool Zakuro

Sora Labo / Sora SDK サーバ の #zakuro チャネル

https://discord.gg/eEUZf6j

### Recoridng Composition Tool Hisui / cpp-mp4

Sora Labo / Sora SDK サーバ の #hisui チャネル

https://discord.gg/S3NWYW6Nv6

### WebRTC Native Client Momo

OpenMomo サーバ

https://discord.gg/gmEuZye

### Ayame WebRTC Signaling Server

OpenAyame サーバ

https://discord.gg/mDesh2E

### React Native WebRTC Kit

Sora Labo / Sora SDK サーバ の #react-native-webrtc-kit チャネル

https://discord.gg/HqfAgEs
