# Dart lint rules

The Dart linter is a static analyzer for identifying possible problems in your
Dart source code. More than a hundred linter rules are available,
checking anything from potential typing issues, coding style, and formatting. This package - package:pro_lints - contains the lint settings recommended by me :).

## Enabling the lints

For existing apps or packages, you can enable these lints via:

1. In a terminal, located at the root of your package, run this command:

    ```terminal
    dart pub add --dev pro_lints
    ```

2. Create a new `analysis_options.yaml` file, next to the pubspec, that
    includes the lints package:

    ```yaml
    include: package:pro_lints/common.yaml
    ```

## Customizing the predefined lint sets

For details on customizing static analysis above and beyond the predefined lint sets, see [customizing static analysis](https://dart.dev/guides/language/analysis-options).
