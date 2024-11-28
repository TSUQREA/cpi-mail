# iOS TLS Configuration Profile

## 概要

このプロファイルは、iOS 18以降で制限されているTLS 1.0/1.1の通信を、特定のドメイン（*.secure.ne.jp）に対してのみ許可するための設定プロファイルです。

### インストール方法

1. [こちらのリンク](https://mc-nekoneko.github.io/cpi-mail/cpi-mail-profile.mobileconfig)をiOSデバイスで開く
2. プロファイルのダウンロードを許可
3. 設定アプリを開く
4. 「プロファイルがダウンロードされました」という通知をタップ
5. インストールボタンをタップ
6. デバイスのパスコードを入力
7. 警告を確認してインストールを完了

### アンインストール方法

1. 設定アプリを開く
2. 「一般」→「VPNとデバイス管理」を選択
3. [TLS Exception Settings] を選択し、プロファイルを削除

### 注意事項
- このプロファイルは`*.secure.ne.jp`ドメインのみに影響します
- 必要がなくなった場合は設定からプロファイルを削除してください。


### インストール用QR
![qrcode_mc-nekoneko github io](https://github.com/user-attachments/assets/0266d0ee-eda9-4246-8f6c-7b613dc21ef4)
