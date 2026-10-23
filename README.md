# THIDA フォロワーカウンター

THIDA TRAINING GYM のタブレット用、Instagram フォロワー数のリアルタイム表示画面です。

- 表示ページ: https://yuichi6312-hue.github.io/thida-follower-counter/
- フォロワー数は Supabase（プロジェクト thida-ig-counter）の Edge Function `ig-followers` から1分ごとに取得します。
- Instagram のトークンとパスコードは Supabase 側に保存されており、このリポジトリには含まれません。
- アカウントの切り替え・表示名の変更・QRコードの表示切替は、画面右下の「設定」から行います。
