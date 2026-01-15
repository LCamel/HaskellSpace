# HaskellSpace

This is a Haskell environment suitable for teaching and testing that works in your browser.

Built on top of [GitHub Codespaces](https://github.com/features/codespaces), each GitHub account can use it for free for 60 hours per month.

You can click on "Code / Codespaces / Create codespace on main" in the upper right corner of the page (login first).



[Video](https://www.youtube.com/watch?v=w1oCE8Ua7p8)<br>
[![codespaces_thumb](https://github.com/user-attachments/assets/6780b29c-aff9-4641-aef1-2fc64200a1d8)](https://www.youtube.com/watch?v=w1oCE8Ua7p8)




Or click this link: [https://codespaces.new/LCamel/HaskellSpace](https://codespaces.new/LCamel/HaskellSpace)

List all active codespaces: [https://github.com/codespaces/](https://github.com/codespaces/)


## Stack

To use stack, please use the snapshot from `~/stackage-version` in the image.
```bash
# Create a sample project
# Build and install foo-exe in the PATH
# Run
# Clean up the generated project

stack new foo --bare --resolver "$(cat ~/stackage-version)"
stack install
foo-exe
git clean -fx .
```
If Haskell shows unreasonable errors in the editor, try executing `>Haskell: Restart Haskell LSP server` in the Command Palette.

[Video](https://www.youtube.com/watch?v=g1kK50rIAv4)<br>
[![codespaces_thumb](https://github.com/user-attachments/assets/bb61fd75-4f2a-4808-a964-cc530d69e4c8)](https://www.youtube.com/watch?v=g1kK50rIAv4)


## Advanced Usage

Just copy the [devcontainer.json](.devcontainer/devcontainer.json) file and your project can also be edited in the browser.

If you want to use it locally, please refer to [LCamel/haskell-devcontainer 🚀](https://github.com/LCamel/haskell-devcontainer) used by this project.


## License
[MIT-0](https://opensource.org/licenses/MIT-0) / [CC0-1.0](https://creativecommons.org/publicdomain/zero/1.0/)
