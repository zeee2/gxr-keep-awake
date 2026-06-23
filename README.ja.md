# Galaxy XR Keep Awake

[English](README.md) | [한국어](README.ko.md) | [日本語](README.ja.md)

Galaxy XR Keep Awake は、Galaxy XR を装着したまま VRChat で眠ることをより快適にするための小さな補助アプリです。

Galaxy XR の非アクティブ警告を検知し、意図して使用している間にヘッドセットがスリープしないように補助します。

## Windows インストーラーでインストール

1. 最新の [Releases](https://github.com/zeee2/gxr-keep-awake/releases) から `GalaxyXRKeepAwakeInstaller.exe` をダウンロードします。
2. Windows PC でインストーラーを実行します。
3. 使用する言語を選択します。
4. インストーラーの Galaxy XR 準備画面に従います。
5. USB ケーブルで Galaxy XR と PC を接続します。
6. ヘッドセット内に USB デバッグ許可画面が表示されたら、許可を選択します。
7. インストーラーのインストールボタンを押します。
8. Galaxy XR でアクセシビリティ設定を開き、Galaxy XR Keep Awake を有効にします。

APK ファイルや ADB を手動でインストールする必要はありません。

## インストール後

アクセシビリティ設定でアプリを有効にしたままにしてください。

設定後はアプリをバックグラウンドに置いて使用できます。Keep Awake 機能を使う間は、アプリを強制終了しないでください。

## 注意

このアプリは Samsung、Google、VRChat、SteamVR、Virtual Desktop の公式アプリではありません。

Galaxy XR は OLED パネルを使用しています。長時間の使用や同じ画面の繰り返し表示により、焼き付きが発生する可能性があります。このアプリは自己責任で使用してください。焼き付きやディスプレイ損傷について、開発者は責任を負いません。

## 開発メモ

このアプリを制作する中で、Samsung が OS を変更する際にアクセシビリティ権限を非常に強く制限していることを確認しました。

そのため、このリリースではアクセシビリティ設定でアプリを有効にできるようにするための互換性回避策を使用しています。2026-06-22 時点では動作していますが、今後のソフトウェアアップデートでブロックされる可能性があります。

## クレジット

- 開発者: JINDESU ([X](https://x.com/jindesu_vr), [GitHub](https://github.com/zeee2))
- 制作協力: ilsubyeega ([GitHub](https://github.com/ilsubyeega))
