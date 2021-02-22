MkDocs only (no Material theme) example to reproduce https://github.com/squidfunk/mkdocs-material/discussions/2313

* [docs/index.md](docs/index.md) - minimal page that embeds [docs/snippet.txt](docs/snippet.txt), with some text before and after the embedded snippet
* [mkdocs.yml](mkdocs.yml) - minimal configuration of vanilla MkDocs plus `pymdownx.snippets` extension


## Result: everything works as expected

Search result preview for text that occurs *before* the embedded snippet: 🟢 WORKS

> ![](works-1.png)

Search result preview for text that occurs *inside* the embedded snippet: 🟢 WORKS

> ![](works-2.png)

Search result preview for text that occurs *after* the embedded snippet: 🟢 WORKS

> ![](works-3.png)


## Environment

* macOS 10.15.7
* Python 3.9.1
* mkdocs v1.1.2
* pymdown-extensions v8.1.1
