# GET_STARTED

## 1. Install the Dart SDK

[mise] manages the Dart SDK version for this repository.
The [mise VS Code extension] symlinks that SDK to `.vscode/mise-tools/dart` for the Dart extension.

1. Install mise. See the [mise installation guide].
2. Execute the following command in the project root.
    ```shell
    mise install
    ```
3. Install the recommended extensions and reload the window.
    The workspace settings turn on automatic configuration and symlinks.
    The mise extension then creates `.vscode/mise-tools/dart`, which `dart.sdkPath` points at.
4. Run the command `mise exec -- dart --version` to check the version.

To use `dart` directly, activate mise in your shell. See the [mise getting started guide](https://mise.jdx.dev/getting-started.html).

## 2. Install dependencies

```shell
mise exec -- dart pub get
```

<!-- Links -->
[mise]: https://mise.jdx.dev/
[mise installation guide]: https://mise.jdx.dev/installing-mise.html
[mise VS Code extension]: https://marketplace.visualstudio.com/items?itemName=hverlin.mise-vscode
