
## 5.1.0

Bump environment sdk to ^3.10.0

**Added 11 new rules:**

- `document_ignores` - Document ignored linter rules
- `invalid_runtime_check_with_js_interop_types` - Runtime checks with JS interop types
- `omit_obvious_property_types` - Omit obvious property types
- `remove_deprecations_in_breaking_versions` - Remove deprecations in breaking versions
- `specify_nonobvious_property_types` - Specify non-obvious property types
- `strict_top_level_inference` - Strict top-level type inference
- `unintended_html_in_doc_comment` - Detect unintended HTML in doc comments
- `unnecessary_async` - Detect unnecessary async
- `unnecessary_ignore` - Detect unnecessary ignore directives
- `unnecessary_underscores` - Detect unnecessary underscores
- `unsafe_variance` - Unsafe variance in generics

**Removed:**

- `unsafe_html` - Replaced by `unsafe_variance`

**Fixed:**

- Removed duplicate rules from `analyzer.errors` section that were already in `linter.rules`

## 5.0.0

Bump environment sdk to ^3.9.0

Add:
`switch_on_type`, `unnecessary_unawaited` rules.

## 4.0.0

Bump environment sdk to ^3.8.0
Add: `use_null_aware_elements` rule

## 3.0.1

Fix syntax

## 3.0.0

Bump environment sdk to ^3.6.0

## 2.0.4

Bump environment sdk to ^3.4.0

## 2.0.3

Bump environment sdk to ^3.3.0

Removed:
`always_require_non_null_named_parameters`
Add:
`annotate_redeclares`

## 2.0.2

avoid_equals_and_hash_code_on_mutable_classes: false by default

## 2.0.1

unnecessary_final: false by default

## 2.0.0

* dart_code_metrics - removed from dependencies

## 1.0.1

* Fix for dart_code_metrics

## 1.0.0+2

* Updated readme

## 1.0.0+1

* Updated readme

## 1.0.0

* Initial version.
