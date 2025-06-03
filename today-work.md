# 今日の作業記録 🛠️

## ✅ 1. GitHubでリモートリポジトリの設定
- **リポジトリ名**: `bloombox`
- GitHubに新しいリポジトリを作成し、Ubuntuのローカルリポジトリと接続。

## ✅ 2. ローカルリポジトリの作成と管理
- `git init` によるローカルリポジトリの初期化（済）
- `git add` でファイル追加
- `git commit` で変更を保存
- `git push origin main` でリモートリポジトリへアップロード成功 🎉

## ✅ 3. SSH認証の設定
- `ssh-keygen -t rsa -b 4096` でSSHキーを生成
- `~/.ssh/id_rsa.pub` の公開鍵をGitHubに登録
- `ssh -T git@github.com` でSSH接続確認 → **成功！**

## ✅ 4. ローカルのディレクトリ整理
- `mv my_git_project bloombox` で **リポジトリのディレクトリ名を変更**
- `cd bloombox` で新しいディレクトリへ移動
- `git status` でリポジトリが正しく動いていることを確認 ✅

## ✅ 5. Markdownに関する検討
- Markdownを使ったドキュメント管理や開発アイデアを検討
- 作業記録 (`today-work.md`) を Markdown で整理 ✍️

## 次のステップ 🚀
- Markdownを活用したプロジェクトを考える
- `README.md` を作成してプロジェクトの概要を整理
- シンプルなMarkdown管理ツールを作るアイデアを検討
