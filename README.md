# Use gitmoji(Emoji) for Commit Message🚀

A simple guide to using gitmoji as commit message prefixes, plus a shell-ready commit template to keep your history clear and fun.

## gitmoji Prefix and Escape Guide

| gitmoji | Prefix | Description | Example |
|---------|--------|-------------|---------|
| ✨ `:sparkles:` | feat | Add new feature | `✨ feat: add user profile editing feature` |
| 🐞 `:lady_beetle:` | fix | Fix a bug (including security fixes) | `🐞 fix: fix display failure` |
| 📝 `:memo:` | docs | Add or update documentation | `📝 docs: add new endpoint to API specification` |
| 💄 `:lipstick:` | ui | Update UI and style files | `💄 ui: change button color to brand color` |
| ⚡ `:zap:` | perf | Improve performance | `⚡ perf: reduce API response time by 300ms` |
| ♻️ `:recycle:` | refactor | Refactor code without changing functionality | `♻️ refactor: split authentication process into functions` |
| 🎨 `:art:` | style | Changes that do not affect the meaning of the code (white-space, missing semi-colon, etc.) | `🎨 style: unify indentation to 2 spaces` |
| 🍱 `:bento:` | assets | Add or update assets | `🍱 assets: add new logo image` |
| 🗑️ `:wastebasket:` | remove | Remove code or files | `🗑️ remove: delete deprecated API endpoint` |
| 🧪 `:test_tube:` | test | Add or update tests | `🧪 test: add unit tests for user registration API` |
| 📦 `:package:` | build | Add or update build system or dependencies | `📦 build: update lodash to v4.17.21` |
| 🚑 `:ambulance:` | hotfix | Critical hotfix | `🚑 hotfix: fix crash in production environment` |
| 🔧 `:wrench:` | chore | Add or update configuration files or scripts | `🔧 chore: update ESLint config and DB init script` |
| 🚧 `:construction:` | wip | Work in progress | `🚧 wip: implement partial UI for dashboard` |
| ⏪ `:rewind:` | revert | Revert changes | `⏪ revert: revert commit abc123` |
| 🔀 `:twisted_rightwards_arrows:` | merge | Merge branches | `🔀 merge: merge feature/login into develop` |
| 🏷️ `:bookmark:` | release | Release / Version tags | `🏷️ release: v1.0.0` |
| 🚀 `:rocket:` | deploy | Deploy stuff | `🚀 deploy: release v1.2.0 to production` |
| 🎉 `:tada:` | init | Begin a project | `🎉 init: create project structure` |

## Template

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
# └ Changes that do not affect the meaning of the code
#   (white-space, missing semi-colon, etc.)
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

## How to use the template?
First, create `~/.gitmessage` (name and location optional) by `touch`.<br>
Then, copy the template and paste it into created file.<br>
Lastly, set that file as a template in git config.<br>

```
touch ~/.gitmessage.txt
git config --global commit.template ~/.gitmessage.txt
```

You're all set! 🎉<br>
Uncomment out the line for use to write a comment!
