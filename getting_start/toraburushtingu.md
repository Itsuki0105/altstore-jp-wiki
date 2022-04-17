---
description: AltStoreやAltServerに問題が起きた時のページです。ここにある対処法をひとまずお試しください。
---

# 🙋 トラブルシューティング

### インストール

<mark style="color:purple;">**Q. 指示に従ってAltStoreをインストールしようとしたが、上手くできません。**</mark>

A. 以下の項目を確認してみてください

* デバイスをPCに接続した際に、信頼を行いましたか？デバイスを接続した状態でiTunesやFinderを開き、デバイスの項目を開いた際に、デバイスを信頼するかどうかのダイヤログが表示されるかを確認します。\
  詳しい内容についてはAppleのサポートページを確認してください\
  [https://support.apple.com/ja-jp/HT202778](https://support.apple.com/ja-jp/HT202778)
* 一度別のApple IDを使用して試すか、AltStore用に新規でApple IDを取得しお試しください\
  新規作成を行う場合は[こちら](https://appleid.apple.com/account#!\&page=create)から可能です。（リンク先はApple IDを作成するページです）
* AltServerを実行中、iTunesとiCloudが起動しているかを確認してください。
* (Windowsの場合)AltServerを管理者として実行してください。
* (Windowsの場合)iTunesとiCloudがMicrosoft Storeからダウンロードされている場合は一度アンインストールを行い、再度Appleから直接ダウンロードした最新のiTunesとiCloudのインストーラを使用してみてください。\
  [詳しい操作方法についてはここから確認できます。](altstorenoinsutruwindows.md#altstorewoinsutrusuruni)
* まれに、正しい方法でインストールしているのにiCloud not foundやiTunes not found が出る場合があります。この場合は、〇〇 not foundのウィンドウ内の「Choose Files...」を選択し、C:¥Program Files(x86)¥Common Files¥Appleを選択の上、OKを押すと先に進むかもしれません（なお、Program Files(x86)は環境によって異なる場合があります。）

### サインイン

<mark style="color:purple;">**Q. AltStoreがフリーズし、サインインできません。**</mark>

A. この症状は、様々な理由で起こります。この問題が発生している場合は、以下の項目を確認してみて　　ください。

* 公共/職場/学校のWi-Fiで試している場合、相互検出機能がうまく使えない可能性があります。\
  別のWi-Fiで試すか、もしくは別の端末がある場合、テザリング機能を利用して、iPhoneとPCの同期を試してください。(iPadを利用している場合は、iPadがホットスポットに接続されているか確認してください)
* デバイスをPCに接続した際に、信頼を行いましたか？デバイスを接続した状態でiTunesやFinderを開き、デバイスの項目を開いた際に、デバイスを信頼するかどうかのダイヤログが表示されるかを確認します。\
  詳しい内容についてはAppleのサポートページを確認してください\
  [https://support.apple.com/ja-jp/HT202778](https://support.apple.com/ja-jp/HT202778)
* (Windowsの場合)ファイヤーウォールが接続を遮断している可能性があります。ファイヤーウォール設定でAltStoreの通信が許可されているかを確認してください。
* (Windowsの場合)iTunesとiCloudがMicrosoft Storeからダウンロードされている場合は一度アンインストールを行い、再度Appleから直接ダウンロードした最新のiTunesとiCloudのインストーラを使用してみてください。\
  [詳しい操作方法についてはここから確認できます。](altstorenoinsutruwindows.md#altstorewoinsutrusuruni)
* AltServerを実行中、iTunesとiCloudが起動しているかを確認してください。
* 最終手段として、iPhone / iPadを直接接続してみてください。これで接続性に関しての問題は解決するはずですが、AltStoreがWi-Fi経由で、Appのバックグラウンド更新ができない可能性があります。

### AltServer

<mark style="color:purple;">**Q. Appをサイドロードまたは、更新を行った際に、「AltServerが見つかりません」と表示されてしまいます。**</mark>

A. Appをサイドロードや更新するには、AltServerとAltStoreの入ったデバイスが同じWi-Fiに接続されている必要があります。もし、同じWi-Fiに接続されているのであれば、以下の項目を確認してみてください。

* 公共/職場/学校のWi-Fiで試している場合、相互検出機能がうまく使えない可能性があります。\
  別のWi-Fiで試すか、もしくは別の端末がある場合、テザリング機能を利用して、iPhoneとPCの同期を試してください。(iPadを利用している場合は、iPadがホットスポットに接続されているか確認してください)
* デバイスをPCに接続した際に、信頼を行いましたか？デバイスを接続した状態でiTunesやFinderを開き、デバイスの項目を開いた際に、デバイスを信頼するかどうかのダイヤログが表示されるかを確認します。\
  詳しい内容についてはAppleのサポートページを確認してください\
  [https://support.apple.com/ja-jp/HT202778](https://support.apple.com/ja-jp/HT202778)
* (Windowsの場合)ファイヤーウォールが接続を遮断している可能性があります。ファイヤーウォール設定でAltStoreの通信が許可されているかを確認してください。
* (Windowsの場合)iTunesとiCloudがMicrosoft Storeからダウンロードされている場合は一度アンインストールを行い、再度Appleから直接ダウンロードした最新のiTunesとiCloudのインストーラを使用してみてください。\
  [詳しい操作方法についてはここから確認できます。](altstorenoinsutruwindows.md#altstorewoinsutrusuruni)
* AltServerを実行中、iTunesとiCloudが起動しているかを確認してください。
* 最終手段として、iPhone / iPadを直接接続してみてください。これで接続性に関しての問題は解決するはずですが、AltStoreがWi-Fi経由で、Appのバックグラウンド更新ができない可能性があります。

<mark style="color:purple;">**Q. ネットワーク設定が変わってから、相互に通信できなくなってしまった（例: 公共/職場/学校のWi-Fiなど)**</mark>

A. iPhone / iPadを直接接続することで、直接サイドロードや更新を行うことができますが、AltStoreがWi-Fi経由で、Appのバックグラウンド更新ができない可能性があります。

