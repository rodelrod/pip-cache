PIP-CACHE
=========

Contains requirements file pointing to Python package that I commonly use. This will allow me to preemptively download a bunch of packages that I constantly use in new developments, so that I can be more effective in trains and planes.


Usage
-----

Just populate the cache by installing in this virtualenv:

```bash
$ pip install -r requirements.txt
```

The packages installed in this virtualenv will be available to install even if you're offline.


For More Complex Needs
----------------------

You can use `pip download -d CACHE_DIR -r requirements.txt` and then install using --find-links to point to the CACHE_DIR.


