# aws-cliのオプション

- --profile _profile_name_ : プロファイルを指定できる
- --rigion ap-northeast-1 : リージョンの指定
- --output json : 出力形式
- --filters _conditions_ : 参照系のコマンドに対して検索条件を指定してリソースを取得できる・aws側でフィルタリングを行うため、結果が大量の場合、件数を減らすような検索条件を設定すればレスポンスが早くなるケースもある
- --query _conditions_ : 結果を絞り込めたり、加工したりできる、取得後の結果を加工するため `--filters` のようにレスポンスが改善することはない
