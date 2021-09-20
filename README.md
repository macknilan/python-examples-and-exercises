# python-examples-and-exercises

It is a repository where I have examples and exercises in python

-   1. [Importing - Internal & External - Python]()
-   2. [Send Email & Read Inbox - Python TUTORIAL]()
-   3. [Files - Create, Read & Download]()
-   4. [Web Scraping Box Office $$ Numbers]()
-   5. [Scrape & Automate behind Password Protected Apps with Selenium & Python]()
-   6. [The Spotify API]()
-   7. []()
-   8. []()

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
