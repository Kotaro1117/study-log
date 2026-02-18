# VPN

## クライアントVPN

### 認証タイプ

- Active Directry → Managed Microsoft AD , AD Connector
- シングルサインオン → SAMLフェデレーションでIAM SAML IDプロバイダー作成しクライアントVPNエンドポイントの認証
- 相互認証 → ACMにサーバー証明書とクライアント証明書をアップしして使用

## site-to-site VPN

- ASN → 1つのネットワークのまとまりを表す識別子
- BGP → AS同士がネット経路情報を交換するためのルーティングプロトコル

- VPNでつなぐときはそれぞれのASNで経路を決める
- BGPが有効 → 動的ルーティング
- 無効 → 静的ルーティング