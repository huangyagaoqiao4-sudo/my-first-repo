# 2026-06-19 学習ログ

## 今日やったこと

### GitHub SSH接続
- SSH鍵を作成
- GitHubへ公開鍵を登録
- ssh -T git@github.com で接続確認

### Gitリポジトリ作成
- ローカルリポジトリ作成
- README.md作成
- git add
- git commit
- git push

---

## 失敗したこと

### 1. リモートURLを間違えた

誤:
git@github.com:huangyagaoqiao4-/my-first-repo.git

結果:
Repository not found

原因:
GitHubユーザー名が間違っていた

学んだこと:
git remote -v で必ず確認する

---

### 2. SSH接続確認で yes を入力しなかった

表示:
Are you sure you want to continue connecting (yes/no/[fingerprint])?

原因:
yes と入力する必要があることを知らなかった

学んだこと:
初回接続時は yes を入力する

---

### 3. GitHubアカウントの確認不足

原因:
ログインしているアカウント名と
リポジトリ所有者を確認していなかった

学んだこと:
GitHub右上のプロフィールを確認する

---

### 4. push先の確認不足

原因:
どのリポジトリへ送っているか把握していなかった

学んだこと:
git remote -v
で確認する

---

## 最後に成功したこと

- GitHubへpush成功
- docs.mdアップロード成功
- mainブランチへ反映成功

---

## 明日の目標

- READMEを編集する
- 新しいファイルを追加する
- GitHub上で変更履歴を確認する
- pull操作を試す
