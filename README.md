# gitmoji-commit-message-template

A handy guide for using gitmoji(emoji) as commit message prefixes.

Make your commit history easier to read, add some visual fun, and boost your mood while coding.

We also have a commit template below that can be used with shell.

コミットメッセージのprefixとしてgitmoji(emoji)を使用する際に使えるガイドです。

履歴を見やすくしつつ、見た目に賑やかにしてテンションを上げましょう。

shellで使用可能なcommitテンプレートも下に置いてあります。

## Gitmoji prefix and escape guide

| gitmoji | escape | prefix | description | 説明（日本語訳） | example |
|---------|--------|--------|-------------|------|---------|
| ✨ | `:sparkles:` | feat | Add new feature | 新機能の追加 | `✨ feat: add user profile editing feature` |
| 🐞 | `:lady_beetle:` | fix | Fix a bug (including security fixes) | バグ修正（セキュリティ修正含む） | `🐞 fix: fix display failure` |
| 📝 | `:memo:` | docs | Add or update documentation | ドキュメントの追加・修正 | `📝 docs: add new endpoint to API specification` |
| 💄 | `:lipstick:` | ui | Update UI and style files | UIに関する変更 | `💄 ui: change button color to brand color` |
| ⚡ | `:zap:` | perf | Improve performance | パフォーマンス改善 | `⚡ perf: reduce API response time by 300ms` |
| ♻️ | `:recycle:` | refactor | Refactor code without changing functionality | 機能変更を伴わないリファクタリング | `♻️ refactor: split authentication process into functions` |
| 🎨 | `:art:` | style | Improve structure/format of the code | コードの意味を変えない整形（インデント、スペースなど） | `🎨 style: unify indentation to 2 spaces` |
| 🍱 | `:bento:` | assets | Add or update assets | アセットの追加・更新（画像、音声、フォントなど） | `🍱 assets: add new logo image` |
| 🗑️ | `:wastebasket:` | remove | Remove code or files | ファイル・コード・機能の削除 | `🗑️ remove: delete deprecated API endpoint` |
| 🧪 | `:test_tube:` | test | Add or update tests | テストの追加・修正 | `🧪 test: add unit tests for user registration API` |
| 📦 | `:package:` | build | Add or update build system or dependencies | ビルドシステムや依存関係の変更 | `📦 build: update lodash to v4.17.21` |
| 🚑 | `:ambulance:` | hotfix | Critical hotfix | 緊急修正 | `🚑 hotfix: fix crash in production environment` |
| 🔧 | `:wrench:` | chore | Add or update configuration files or scripts | 設定ファイルや開発用スクリプトの変更 | `🔧 chore: update ESLint config and DB init script` |
| 🚧 | `:construction:` | wip | Work in progress | 作業途中のコミット | `🚧 wip: implement partial UI for dashboard` |
| ⏪ | `:rewind:` | revert | Revert changes | 変更の取り消し | `⏪ revert: revert commit abc123` |
| 🔀 | `:twisted_rightwards_arrows:` | merge | Merge branches | ブランチのマージ | `🔀 merge: merge feature/login into develop` |
| 🏷️ | `:bookmark:` | release | Release / Version tags | バージョンリリース | `🏷️ release: v1.0.0` |
| 🚀 | `:rocket:` | deploy | Deploy stuff | 本番やステージングへのデプロイ | `🚀 deploy: release v1.2.0 to production` |
| 🎉 | `:tada:` | init | Begin a project | プロジェクト初期コミット | `🎉 init: create project structure` |

## Template
Uncomment out the line to be used and write a comment.

```zsh
# ✨ feat: 
# └ Add new feature
# 🐞 fix: 
# └ Fix a bug (including security fixes)
# 📝 docs: 
# └ Add or update documentation
# 💄 ui: 
# └ Update UI and style files
# ⚡ perf: 
# └ Improve performance
# ♻️ refactor: 
# └ Refactor code without changing functionality
# 🎨 style: 
# └ Improve structure/format of the code
# 🍱 assets: 
# └ Add or update assets
# 🗑️ remove: 
# └ Remove code or files
# 🧪 test: 
# └ Add or update tests
# 📦 build: 
# └ Add or update build system or dependencies
# 🚑 hotfix: 
# └ Critical hotfix
# 🔧 chore: 
# └ Add or update configuration files or scripts
# 🚧 wip: 
# └ Work in progress
# ⏪ revert: 
# └ Revert changes
# 🔀 merge: 
# └ Merge branches
# 🏷️ release: 
# └ Release / Version tags
# 🚀 deploy: 
# └ Deploy stuff
# 🎉 init: 
# └ Begin a project
```

## How to set the template
Use this as `~/.gitmessage` (name and location optional), and set that file as a template in git config in following steps:

```
touch ~/.gitmessage.txt
git config --global commit.template ~/.gitmessage.txt
```
