# Dockerfile Templates

Replaced by [Component Templates](https://github.com/keboola/component-generator).

Repository containing templates useful as initial templates for developing Docker
components for Keboola Connection.

## Usage

Clone this repository:

```console
git clone git@github.com:keboola/dockerfile-templates.git
```

Copy specific template as base for you new project:

```console
cp -R dockerfile-templates/php70 my-new-project
```

Test container:

```console
cd my-new-project
docker build -t my-new-project .
docker run -i -t my-new-project bash
```

## Examples

| Type | Dockerfile |
| --- | --- |
| PHP 7.0 | https://github.com/keboola/mongodb-extractor/blob/master/Dockerfile |

## License

MIT. See license file.
