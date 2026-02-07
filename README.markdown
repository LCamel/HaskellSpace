<!--
 _   _           _        _ _ _____
| | | |         | |      | | /  ___|
| |_| | __ _ ___| | _____| | \ `--. _ __   __ _  ___ ___
|  _  |/ _` / __| |/ / _ \ | |`--. \ '_ \ / _` |/ __/ _ \
| | | | (_| \__ \   <  __/ | /\__/ / |_) | (_| | (_|  __/
\_| |_/\__,_|___/_|\_\___|_|_\____/| .__/ \__,_|\___\___|
                                   | |
                                   |_|
-->


# HaskellSpace

A Haskell workspace in your browser (GHC + Stackage + HLS).

Built on [GitHub Codespaces](https://github.com/features/codespaces). Personal accounts include 60 free hours per month ([plan](https://docs.github.com/en/billing/concepts/product-billing/github-codespaces) dependent).

To run locally, see [LCamel/haskell-devcontainer](https://github.com/LCamel/haskell-devcontainer).


## Quick Start (Codespaces)

- In GitHub, click `Code → Codespaces → Create codespace on main` (sign in first).
- Or open: [https://codespaces.new/LCamel/HaskellSpace](https://codespaces.new/LCamel/HaskellSpace)
- Manage your Codespaces: [https://github.com/codespaces/](https://github.com/codespaces/)

![start](https://github.com/user-attachments/assets/fe0eb52d-cbd1-4955-a1f8-86d0dfc1df40)

## Stack

Use the snapshot pinned in `~/.haskell-devcontainer/stackage-version` .
```bash
# Create a sample project
# Build and install foo-exe into your PATH
# Run
# Clean up the generated project

stack new foo --bare --resolver "$(cat ~/.haskell-devcontainer/stackage-version)"
stack install
foo-exe
git clean -fx .
```
If you see incorrect or stale Haskell diagnostics in the editor, run `>Haskell: Restart Haskell LSP server` from the Command Palette.

[![stack](https://github.com/user-attachments/assets/ebeac349-372c-402a-9a82-a7128556f05b)](https://www.youtube.com/watch?v=ReRydamqHjw)

## Customization

Copy [.devcontainer/devcontainer.json](.devcontainer/devcontainer.json) into your own repo so it can also be opened in the browser. See [this guide](https://code.visualstudio.com/docs/devcontainers/create-dev-container) for further customization.


## License

[MIT-0](https://opensource.org/licenses/MIT-0) / [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/)

<!--
ASCII Banner:
https://patorjk.com/software/taag
https://github.com/xero/figlet-fonts/blob/main/Doom.flf
-->
