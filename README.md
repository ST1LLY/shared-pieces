```
[mypy]
#
# https://mypy.readthedocs.io/en/stable/config_file.html
#
# Disallows usage of types that come from unfollowed imports
# disallow_any_unimported = True
#
# Disallows usage of generic types that do not specify explicit type parameters.
disallow_any_generics = True
#
# Disallows calling functions without type annotations from functions with type annotations
disallow_untyped_calls = True
#
# Disallows functions that have Any in their signature after decorator transformation
# disallow_any_decorated = True
#
# Enables or disables strict Optional checks. (Default True)
# strict_optional = False
#
# Warns about unneeded # type: ignore comments.
warn_unused_ignores = True
#
# Suppresses error messages about imports that cannot be resolved.
ignore_missing_imports = True
#
# Type-checks the interior of functions without type annotations.
check_untyped_defs = True
#
# Disallows defining functions with incomplete type annotations.
disallow_incomplete_defs = True
#
# Disallows defining functions without type annotations or with incomplete type annotations.
disallow_untyped_defs = True
#
# Warns about casting an expression to its inferred type.
warn_redundant_casts = True
#
# Warns about per-module sections in the config file that do not match any files processed when invoking mypy.
warn_unused_configs = True
#
# Prohibit equality checks, identity checks, and container checks between non-overlapping types.
strict_equality = True
#
# Shows a warning when encountering any code inferred to be unreachable or redundant after performing type analysis.
warn_unreachable = True
#
# When false, mypy will not re-export unless the item is imported using from-as or is included in __all__.
implicit_reexport = True

# Ignore restrictions for tests folder
[mypy-tests.*]
ignore_errors = True
```
