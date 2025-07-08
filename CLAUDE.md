# murack-workspace

楽曲ライブラリ管理システム「Murack」の、各種アプリケーションの開発環境。

## リポジトリ構造

- murack-workspace : 各リポジトリを submodule で参照する DevContainer 開発環境
- murack-core : Murack システムの共通コアライブラリ
- murack-web-frontend : ライブラリ編集のためのメイン GUI となる Web アプリ
- murack-web-backend : Murack Web のバックエンド部分
- murack-sync : 楽曲ファイル, DB, DAP 間の同期を担当する、デスクトップ用 GUI アプリ
- murack-dock-android : DAP への DB データ反映を Android からできるアプリ
