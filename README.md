# LetMicrosoft365GraphConnect
Microsoft Graph へのモダン接続方法のまとめ
Azure AD Graph と MSOnline の PowerShell licensing assignment APIs は 2022 年 8 月 26 日でサポート終了を迎えます。
このタイミングまでに Microsoft Graph へライセンス付与機能を移行していく必要がありますが、
PowerShell から Microsoft Graph への接続方法として、今までのような基本認証は行えません。
これを解決する方法は Azure にアプリケーションとして登録する方法となります。
この資料は Azure へのアプリケーション登録方法を記しています。
証明書での接続が通常の方法ですが、シークレットを用いた接続方法も説明しています。
自身の環境にあったものを利用していきましょう。
© 2022 Tomoharu Misawa All rights reserved.
本コンテンツの著作権、および本コンテンツ中に出てくる商標権、団体名、ロゴ、製品、サービスなどはそれぞれ、各権利保有者に帰属します。
