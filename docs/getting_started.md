## Clone my repo

Clone my [repo](https://github.com/FrancescoSaverioZuppichini/Modern-Python-Doc-Example)


```bash
$ git clone git@github.com:FrancescoSaverioZuppichini/Modern-Python-Doc-Example.git && cd Modern-Python-Doc-Example
```

Then you can start `mkdocs` with the following command

<div class="termy">

```console
$ mkdocs serve -w 
INFO     -  Building documentation...
INFO     -  Cleaning site directory
INFO     -  Documentation built in 0.23 seconds
INFO     -  [11:11:17] Watching paths for changes: 'docs', 'mkdocs.yml', '.'
INFO     -  [11:11:17] Serving on http://localhost:8000/
```

</div>

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

