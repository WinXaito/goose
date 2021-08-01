# goose docs website

The documentation is available at [pressly/goose docs](pressly.github.io/goose)

Installation instructions from here:

https://squidfunk.github.io/mkdocs-material/getting-started/

Going to use Docker here:

```bash
docker pull squidfunk/mkdocs-material
```

### Create project

```bash
docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material new .
```

### Preview project

This uses a Docker container under the hood.

```bash
make preview
```

Available at: http://localhost:8000