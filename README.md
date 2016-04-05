# memo

CodeDeploy + Github hockを使って自動デプロイ。

1. AWS CodeDeployを設定
2. Github連携用のIAMユーザーを作成
3. GithubのWebhooks & servicesでAWS CodeDeployの設定を入れる
  1. AccessKey/Secret, CodeDeployのARNが必要
4. GitHubのWebhooks & servicesでAuto-Deploymentを設定

デフォルトのブランチに更新があった時、CodeDeployがフックされるようになる。
