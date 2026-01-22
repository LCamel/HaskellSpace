<!--

 _   _           _        _ _ _____
| | | |         | |      | | /  ___|
| |_| | __ _ ___| | _____| | \ `--. _ __   __ _  ___ ___
|  _  |/ _` / __| |/ / _ \ | |`--. \ '_ \ / _` |/ __/ _ \
| | | | (_| \__ \   <  __/ | /\__/ / |_) | (_| | (_|  __/
\_| |_/\__,_|___/_|\_\___|_|_\____/| .__/ \__,_|\___\___|
                                   | |
                                   |_|


https://github.com/xero/figlet-fonts/blob/main/Doom.flf
-->


# HaskellSpace

Practicing Haskell in a browser.

Built on top of [GitHub Codespaces](https://github.com/features/codespaces), each GitHub account can use it for free for 60 hours per month.

You can click on "Code / Codespaces / Create codespace on main" in the upper right corner of the page (login first).

[![codespaces_thumb](https://github.com/user-attachments/assets/0be53469-dea5-46b3-b315-c01ab9b7d055)](https://www.youtube.com/watch?v=hcx0SSvk7zg)


Or click this link: [https://codespaces.new/LCamel/HaskellSpace](https://codespaces.new/LCamel/HaskellSpace)

List all active codespaces: [https://github.com/codespaces/](https://github.com/codespaces/)


## Stack

To use stack, please use the snapshot from `~/.haskell-devcontainer/stackage-version` in the image.
```bash
# Create a sample project
# Build and install foo-exe in the PATH
# Run
# Clean up the generated project

stack new foo --bare --resolver "$(cat ~/.haskell-devcontainer/stackage-version)"
stack install
foo-exe
git clean -fx .
```
If Haskell shows unreasonable errors in the editor, try executing `>Haskell: Restart Haskell LSP server` in the Command Palette.

[![codespaces_thumb](https://github.com/user-attachments/assets/a56b1e88-84e6-4b31-8527-48fa0ffdca67)](https://www.youtube.com/watch?v=g1kK50rIAv4)



## Advanced Usage

Just copy the [devcontainer.json](.devcontainer/devcontainer.json) file and your project can also be edited in the browser.

If you want to use it locally, please refer to [LCamel/haskell-devcontainer 🚀](https://github.com/LCamel/haskell-devcontainer) used by this project.


## License
[MIT-0](https://opensource.org/licenses/MIT-0) / [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/)
