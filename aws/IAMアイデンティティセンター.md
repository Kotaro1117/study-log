外部アプリケーションとのシングルサインオン

# IAMアイデンティティセンター認証
## アイデンティティセンターディレクトリー
- デフォルト
- 使用したいディレクトリがないとき
- ユーザー名、パスワードをIAMアイデンティティセンターで管理

## Active Directory
- AD ConnectorかAWS Managed Microsoft ADを選択

## 外部IDプロバイダー
- Azure AD、Oktaなど外部IDプロバイダーを使用

# AWSアカウントへの許可セット
- AWSアカウントにシングルサインオンしたときの権限を設定
- 作成したポリシーとOrganizationsのメンバーアカウントを紐づけ

# IAMアイデンティティセンターを使用しないケース
- すでにAD FS(Active Directory Federation Service)や認証だけではなくOkta、OneLoginの
ポータルサイトなど他のシングルサインオンを使用している場合には使用せず設定するケースがある
- その場合は