# Cli Parser

> Auto-generated documentation for [mypy_boto3_builder.cli_parser](https://github.com/youtype/mypy_boto3_builder/blob/main/mypy_boto3_builder/cli_parser.py) module.

CLI parser.

- [mypy-boto3-builder](../README.md#mypy_boto3_builder) / [Modules](../MODULES.md#mypy-boto3-builder-modules) / [Mypy Boto3 Builder](index.md#mypy-boto3-builder) / Cli Parser
    - [Namespace](#namespace)
    - [get_absolute_path](#get_absolute_path)
    - [parse_args](#parse_args)

## Namespace

[[find in source code]](https://github.com/youtype/mypy_boto3_builder/blob/main/mypy_boto3_builder/cli_parser.py#L30)

```python
dataclass
class Namespace():
```

CLI arguments namespace.

## get_absolute_path

[[find in source code]](https://github.com/youtype/mypy_boto3_builder/blob/main/mypy_boto3_builder/cli_parser.py#L16)

```python
def get_absolute_path(path: str) -> Path:
```

Get absolute path from a string.

#### Arguments

- `path` - String containing path.

#### Returns

Absolute path.

## parse_args

[[find in source code]](https://github.com/youtype/mypy_boto3_builder/blob/main/mypy_boto3_builder/cli_parser.py#L47)

```python
def parse_args(args: Sequence[str]) -> Namespace:
```

Main CLI parser for builder.

#### Returns

Argument parser.

#### See also

- [Namespace](#namespace)
