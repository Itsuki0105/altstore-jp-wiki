---
description: >-
  このページは、WindowsがインストールされているPCを使用してAltStoreをiPhoneやiPadにインストールする手順を確認し、すぐにアプリのサイドロードを行うのに役立ちます
---

# 🪟 AltStoreのインストール(Windows)

## AltStoreをインストールする前に（重要）

<mark style="color:red;">Windows 10以降では、Microsoft StoreからiTunes、iCloudをインストールすることがAppleから推奨されますが、この状態でAltStoreを使用するとエラーが発生してiPhoneやiPadにAltStoreのインストールが進められなくなってしまいます。そのため、必ず本項を必ず読んでいただき、この後の操作を行ってください。</mark>

1. Microsoft StoreからiTunes・iCloudをダウンロードしている場合は、以下のヒントにあるリンク先を参考にアンインストールを行ってください。（データの消失等の責任は負えませんのでご自身でバックアップ等お取りください）
2. iTunesとiCloudをAppleのサイトから直接ダウンロードしインストールを行います。<mark style="color:red;">（Microsoft Storeからのインストールは絶対に行わないでください）</mark>

{% hint style="info" %}
**手順1に関するヒント**

[Windows 7以降でiTunesとその関連ソフトウェアコンポーネントを削除して再インストールする（Appleサポート）](https://support.apple.com/ja-jp/HT204275)

上記のページにあるインストール手順（iTunesと関連するコンポーネントを再インストールする）はやらず、このページに戻ってください。\
\
[Windowsでアプリとプログラムを修復する(Microsoftサポート)](https://00m.in/Yd41a)
{% endhint %}

{% hint style="info" %}
手順2に関するヒント

以下のリンクからダウンロードしてください。（すべてAppleのサイトとなっています）

iCloud for Windowsのダウンロードリンク\
[https://updates.cdn-apple.com/2020/windows/001-39935-20200911-1A70AA56-F448-11EA-8CC0-99D41950005E/iCloudSetup.exe](https://updates.cdn-apple.com/2020/windows/001-39935-20200911-1A70AA56-F448-11EA-8CC0-99D41950005E/iCloudSetup.exe)\
\
iTunesのダウンロードリンク\
Windows 64bit: [https://www.apple.com/itunes/download/win64](https://www.apple.com/itunes/download/win64)

Windows 32bit: [https://www.apple.com/itunes/download/win32](https://www.apple.com/itunes/download/win32)
{% endhint %}

## AltStoreをインストールする

1. [altstore.io](https://altstore.io)からWindows版のAltServerをダウンロードしてください
2. zipファイルを解凍し、<mark style="background-color:green;">Setup.exe</mark>を実行します。
3. インストールが終わったら、「AltStore」を探し、右クリックし「管理者として実行」をクリックします。すると、AltStoreがタスクバーにアイコンとして表示されます。
4. iOS / iPadOSデバイスをコンピュータに接続します。この時、画面ロックは解除を行ってください。この際、デバイス上に「このコンピュータを信頼しますか？」と表示された場合は、信頼を行ってください。
5. iTunesを開き、該当デバイスのオプションにある「Wi-Fi経由でこのiPhone(iPad)と同期」にチェックを入れ、適用をクリックします。
6. 右下のタスクバーにあるAltStoreをクリックし、「Install AltStore」にカーソルを合わせ、該当のデバイスを選択します。
7. Apple IDとパスワードを入力し、「Install」をクリックします。これにより、AppleとAltServer間で認証を行い、サイドロードアプリをサポートするようにアカウントを構成できます。
8. 数秒待つと、AltStoreがデバイスに正常にインストールされたことを示す通知が表示されます。
9. iOS(iPad OS)で「設定」→「一般」→「VPNとデバイス管理」を開き、デベロッパAPPの項目に、自身のApple IDの項目を選択し、「"\[自身のApple ID]"を信頼」をタップし、もう一度「信頼」をタップします。

_**これで、AltStoreを使用してAppをサイドロードする準備が整いました。**_

{% hint style="info" %}
**手順3に関するヒント**

初回起動時にファイアウォール警告が表示されますが、必ず許可をするよう設定してください。
{% endhint %}

{% hint style="info" %}
**手順4に関するヒント**\
信頼を行う操作が分からない場合は、以下のリンクよりApple公式ページをご覧ください。

[iPhone、iPad、iPod touchで表示される「このコンピュータを信頼しますか？」という警告について](https://support.apple.com/ja-jp/HT202778)
{% endhint %}

{% hint style="info" %}
**手順7に関するヒント**\
Apple IDとパスワードは、Appleのサーバにのみ送られ他の所には送信されません。
{% endhint %}

{% hint style="info" %}
**手順8に関するヒント**

iPhone(iPad)のホーム画面にAltStoreが表示されていない場合、デバイスの再起動をお試しください。
{% endhint %}

{% hint style="info" %}
**手順9に関するヒント**

「VPNとデバイス管理」の名称は、バージョンや環境によって変わりますが、通常は「設定」→「一般」の下部にあります。
{% endhint %}

{% hint style="info" %}
もし、手順通りにやったのにiCloud not found やiTunes not foundが出た場合、手動でフォルダを指定してあげれば動作するかもしれません。

やり方としては、〇〇 not foundのウィンドウ内の「Choose Files...」を選択し、C:¥Program Files(x86)¥Common Files¥Appleを選択の上、OKを押すと先に進むかもしれません。
{% endhint %}

Appを探したい場合は、ここから[AltStoreでアプリを探す方法](../how\_to\_use\_altstore/altstore.md#browse)を確認してください。

もし、トラブルなどがあればここから[トラブルシューティングガイド](toraburushtingu.md)をご覧ください。
