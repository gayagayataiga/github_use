# GitHub 入門リポジトリ
[![Stars](https://img.shields.io/github/stars/ユーザー名/リポジトリ名)](https://github.com/ユーザー名/リポジトリ名/stargazers)
[![Issues](https://img.shields.io/github/issues/ユーザー名/リポジトリ名)](https://github.com/ユーザー名/リポジトリ名/issues)

このリポジトリは **GitHub の基本的な使い方** を学ぶための教材です。  
アカウント作成から、リポジトリの作成、Pull Request の方法までを解説します。

---

## 📖 目次
1. [GitHubとは？](#githubとは)
2. [アカウントの作成](#アカウントの作成)
3. [リポジトリを作成する](#リポジトリを作成する)
4. [ファイルを追加する](#ファイルを追加する)
5. [コミットとプッシュ](#コミットとプッシュ)
6. [ブランチとプルリクエスト](#ブランチとプルリクエスト)
7. [IssuesとDiscussions](#issuesとdiscussions)
8. [まとめ](#まとめ)

---

## 🔰 GitHubとは？
GitHubは、ソースコードを管理・共有するためのサービスです。  
特徴：
- Git によるバージョン管理
- チーム開発が簡単
- 無料で使える
- 世界中のOSSに貢献できる

---

## 📝 アカウントの作成
1. [GitHub公式サイト](https://github.com/) にアクセス  
2. 「Sign up」をクリック  
3. ユーザー名・メールアドレス・パスワードを入力  
4. 確認メールで認証  

---

## 📂 リポジトリを作成する
1. GitHub の右上の **+ → New repository** を選択  
2. リポジトリ名を入力  
3. `Public` か `Private` を選択  
4. `Initialize with README` にチェックすると最初から README.md が作成される  

---

## ✍️ ファイルを追加する
### ブラウザから追加する方法
1. リポジトリを開く  
2. **Add file → Upload files** を選択  
3. ファイルをドラッグ&ドロップ  

### コマンドラインから追加する方法
```bash
git clone https://github.com/ユーザー名/リポジトリ名.git
cd リポジトリ名
echo "Hello GitHub" > hello.txt
git add hello.txt
git commit -m "Add hello.txt"
git push origin main
