# GET_STARTED

## 1. Install the Dart SDK

[mise] manages the Dart SDK version for this repository.

1. Install mise globally.
    ```shell
    brew install mise
    ```
2. Execute the following commands in the project root.
    ```shell
    mise install
    mise run link-sdk
    ```
    `mise install` installs the pinned Dart SDK. `mise run link-sdk` points `.dart_sdk` at that SDK so the Dart extension can find it.
3. Run the command `mise exec -- dart --version` to check the version.

To use `dart` directly, activate mise in your shell. See the [mise getting started guide](https://mise.jdx.dev/getting-started.html).

## 2. Install dependencies

```shell
mise exec -- dart pub get
```

<!-- Links -->
[mise]: https://mise.jdx.dev/
