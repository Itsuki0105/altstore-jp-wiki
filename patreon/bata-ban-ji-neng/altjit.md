# 🏎 AltJIT

AltJITを使用すると、AltStoreでサイドロードしたAppで、JIT(ジャストインタイムコンパイル）を使用することができます。JITを使用すると、一部のAppは大幅に高速化されますが、Appleのセキュリティ上の仕様によりAppにJITを使用することを許可していません。

AltJITでは、AltStore独自の回避手法で、AltServerと同一のWi-Fiネットワークに接続されている場合であればいつでも、サイドロードされたAppのJITを有効化することができます。

AltJITを使用する場合には、"My Apps"タブを開き、JITを使用したいAppを長押しし、"Enable JIT"をタップした上で、Appを起動すると、数秒後にJITが有効化されたことを示すAltStoreからの通知が表示されます。\
これで、AppがクラッシュすることなくJIT関連の機能を使用することができるようになります。

{% hint style="info" %}
AltJITを有効にすると、アプリスイッチャーから強制終了するか、バックグラウンドで休止中の状態になり、メモリから削除されるまでの間動作し続けます。
{% endhint %}

もし、AltJITを使用する際に問題が発生した場合は、[トラブルシューティングガイド](../../getting\_start/toraburushtingu.md)を参照してください。
