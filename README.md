# Pro Lints

[![pub package](https://img.shields.io/pub/v/pro_lints.svg)](https://pub.dev/packages/pro_lints)

A comprehensive and opinionated set of lint rules for Dart and Flutter projects. This package provides strict but practical linting rules to help you write clean, maintainable, and error-free code.

## Features

- 🎯 **200+ lint rules** carefully selected for production-ready code
- 🔒 **Strict type safety** with disabled implicit casts and dynamic types
- 📏 **Consistent code style** enforcing best practices
- ⚡ **Production-focused** rules that catch common bugs early
- 🛠️ **Easy setup** - just one line in your `analysis_options.yaml`

## Installation

Add `pro_lints` as a dev dependency to your project:

```bash
dart pub add --dev pro_lints
```

Or for Flutter projects:

```bash
flutter pub add --dev pro_lints
```

## Usage

Create or edit `analysis_options.yaml` in the root of your package:

```yaml
include: package:pro_lints/recommended.yaml
```

That's it! The analyzer will now use the comprehensive lint rules from this package.

## What's Included

### Analyzer Settings

- **Strict mode enabled**: No implicit casts or dynamic types
- **Build folder excluded** from analysis
- **Critical errors enforced**: Missing returns, invalid assignments, required parameters

### Key Lint Rules

This package enables:

- ✅ Type safety and null safety rules
- ✅ Code style consistency (trailing commas, quotes, formatting)
- ✅ Performance optimizations
- ✅ Flutter best practices
- ✅ Documentation requirements for public APIs
- ✅ Import organization and dependency management
- ✅ Error handling patterns
- ✅ Const correctness

### Notable Rules

- `always_declare_return_types` - Explicit return types everywhere
- `prefer_final_locals` / `prefer_final_fields` - Immutability by default
- `require_trailing_commas` - Better diffs and formatting
- `lines_longer_than_80_chars` - Readable line length
- `prefer_relative_imports` - Cleaner import structure
- `avoid_dynamic_calls` - Type safety enforcement
- `use_build_context_synchronously` - Async Flutter safety

## Customization

You can override any rule by adding it to your `analysis_options.yaml`:

```yaml
include: package:pro_lints/common.yaml

linter:
  rules:
    # Disable a specific rule
    lines_longer_than_80_chars: false
    
    # Or enable additional rules
    always_specify_types: true
```

For more details on customizing static analysis, see the [official Dart documentation](https://dart.dev/guides/language/analysis-options).

## Version History

See [CHANGELOG.md](CHANGELOG.md) for version history.

## Contributing

Contributions are welcome! Please open an issue or pull request on [GitHub](https://github.com/pro100andrey/pro_lints).

## License

See [LICENSE](LICENSE) file for details.
