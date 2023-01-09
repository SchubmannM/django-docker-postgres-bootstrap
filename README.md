# Django Bootstrap
1. Replace all "django_project" and "django_app" strings with whatever you're building.
2. Fill out the variables in the .env files
3. Install the correct python version with `CFLAGS="-I$(brew --prefix openssl@1.1)/include" LDFLAGS="-L$(brew --prefix openssl@1.1)/lib" asdf install`
4. Run `python -m pip install pipenv` and `python -m pipenv install --dev`
5. Set your VSCode python interpreter path to the pipenv env (obtainable through `python -m pipenv --venv`)
6. Start hacking away :)
