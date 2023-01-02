# ISAC-SIMO Documentation

We use MkDocs for building and generating the documentations. MkDocs is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation. Documentation source files are written in Markdown, and configured with a single YAML configuration file.

[Learn About MkDocs](https://www.mkdocs.org/)

The Markdown files listed above are used for their specific documentation. They can be edited and built into HTML documentation pages.

## Building Documentation:

You you have not setup `Pipenv` already, then MkDocs and a template need to be installed first using `pip`

```sh
pip install mkdocs
pip install mkdocs-material
```

From the root our repository, we need to run:

```sh
mkdocs build
```

If `Pipenv` is setup then from virtual shell or from the root our repository, we need to run:

```sh
pipenv run mkdocs build
```

This, will build the documentation as HTML and saves them in the `site` directory. Note that we use some mkdocs markdown extensions that can be viewed in `mkdocs.yml` file.

The Documentation is hosted at: [https://docs.isac-simo.net/](https://docs.isac-simo.net/)

## All Documentation:

- [Documentaion Home](https://docs.isac-simo.net/)
- [Getting Started](https://docs.isac-simo.net/getting-started/)
- [Web Application](https://docs.isac-simo.net/web-application/)
- [Mobile Application](https://docs.isac-simo.net/mobile-application/)
- [Developer Guide](https://docs.isac-simo.net/developer-guide/)
- [Mobile API Guide](https://docs.isac-simo.net/mobile-api-guide/)
- [Lite Dashboard](https://docs.isac-simo.net/lite-dashboard/)
- [External Integration](https://docs.isac-simo.net/integration/)
