# Development commands
## Creating a new virtual environment
```
python -m venv develop-env
```

## Opening the environment
```
source develop-env/bin/activate
```

## Closing the environment
```
deactivate
```

## Installing dependencies
```
pip install mkdocs
pip install mkdocs-material
```

## Testing the site locally
```
mkdocs serve
```

## Building the pages and push to github pages
```
cd Recipes
mkdocs build
mkdocs gh-deploy
```
