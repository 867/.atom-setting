# ATOM setting

ATOM の設定ファイル

## パッケージの管理

パッケージをインストールした時に次を実行して「packages.txt」リストに反映。

    $ apm list --installed --bare > packages.txt

## パッケージのインストール

次を実行してリストに記載されたパッケージを一括で入れる。

    $ apm install --packages-file packages.txt
