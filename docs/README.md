# Documentation

The documentation is available at: <https://flyvis.github.io/flyvis/>

## Building the Documentation

You can build the docs locally by running the following command from this subfolder:

```bash
jupyter nbconvert --to markdown ../examples/*.ipynb --output-dir docs/examples/
mkdocs serve
```

<!-- The docs can be updated to GitHub using:

```bash
jupyter nbconvert --to markdown ../examples/*.ipynb --output-dir docs/examples/
mkdocs gh-deploy
``` -->
