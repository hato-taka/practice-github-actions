# Github Actions の学習用


`.github/workflows/` ディレクトリに `.yml`ファイルを作成する

## workflowのトリガー

`push`: リポジトリへのプッシュ時にワークフローを実行します。

```yaml
on:
  push:
    branches:
      - main
    paths:
      - '**.js'
```