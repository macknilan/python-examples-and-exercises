# python-examples-and-exercises

It is a repository where I have examples and exercises in python

-   a. [Importing - Internal & External - Python]()
-   b. [Send Email & Read Inbox - Python TUTORIAL]()
-   c. [Files - Create, Read & Download]()
-   d. [Web Scraping Box Office $$ Numbers]()
-   e. [Scrape & Automate behind Password Protected Apps with Selenium & Python]()
-   f. [The Spotify API - jupyter notebook]()
-   g. [Python Google Sheets API]()
-   h. []()

Black

```bash
black */*.py
```

Flake8

```bash
flake8 */*.py
```

isort multiples configuraciones

```bash
# sort multiple files
isort views.py urls.py

# show a diff before applying any change
isort views.py --diff

# just check for errors
isort urls.py --check-only
```

Aplicar cambios o verificar errores recursivamente

```bash
# check which files will be sorted
isort --recursive --check-only

# sort the whole project
isort --recursive .
```

pylint

```bash
pylint */*.py
```

Jupyter notebook

```bash
jupyter notebook
# or
pipenv run jupyter notebook
```
