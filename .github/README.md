# HaskellSpace

這是一個適合教學與測試的, 有瀏覽器就能使用的 Haskell 環境.

建構於 [GitHub Codespaces](https://github.com/features/codespaces) 之上, 每個 GitHub 帳號每個月可以免費使用 60 小時.

你可以點選頁面右上角的 "Code / Codespaces / Create codespace on main" 來使用(先 Login).

或者是點這個連結: [https://codespaces.new/LCamel/HaskellSpace](https://codespaces.new/LCamel/HaskellSpace)

列出所有使用中的 codespaces: [https://github.com/codespaces/](https://github.com/codespaces/)


## Stack

請使用 image 中 `~/stackage-version` 的 snapshot.
```bash
# Create a sample project and run it
stack new foo --bare --resolver "$(cat ~/stackage-version)"
stack install
foo-exe
```
如果 Haskell 不能正常顯示, 可在 Command Palette 執行 `>Haskell: Restart Haskell LSP server`.


## 進階使用

只要複製 [devcontainer.json](.devcontainer/devcontainer.json) 一個檔案, 你的專案也能在 browser 中編輯.

如果想在本機使用, 請參考本專案使用的 [LCamel/haskell-devcontainer 🚀](https://github.com/LCamel/haskell-devcontainer).


## License
[MIT-0](https://opensource.org/licenses/MIT-0) / [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/)
