# infra-sandbox

ArgoCDを用いたインフラ管理用リポジトリ (サンドボックス用)

このリポジトリに含まれるYAMLファイルを用いることで、使い捨てのテスト用サーバーをデプロイすることができます。
なお、このリポジトリは本番環境のMinecraftサーバーをデプロイする用途には使用しないでください。

## このリポジトリに含まれるもの

- [minecraft/common.yaml](minecraft/common.yaml) ... spigot.ymlなどのデフォルトの設定が入っているファイル。
- [template/server.yaml](template/server.yaml) ... 使い捨てMinecraftサーバーを立てるためのテンプレートファイル。`minecraft`フォルダ内にコピーして編集することで使用可能です。
  - そのままコピーするとViaVersion / ViaBackwardsだけが入ったサーバーが自動で構築され、`/server sandbox-test`で参加可能になります。
