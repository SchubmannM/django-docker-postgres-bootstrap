# Django Bootstrap
Replace all "django_project" and "django_app" strings with whatever you're building.
Fill out the variables in the .env files
Install the correct python version with `CFLAGS="-I$(brew --prefix openssl@1.1)/include" LDFLAGS="-L$(brew --prefix openssl@1.1)/lib" asdf install`
Run `python -m pip install pipenv` and `python -m pipenv install --dev`
Set your VSCode python interpreter path to the pipenv env (obtainable through `python -m pipenv --venv`)
Start hacking away :)