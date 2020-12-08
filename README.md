# covid-forecast

## Dev Instructions
Run `poetry install` to install the env.  
TODO: Run `poetry run pre-commit install` to initialize the git hooks.  
TODO: Run `poetry run pre-commit run --all-files` if there are file that were committed before adding the git hooks.  
Activate the shell with: `poetry shell`  
Lint with: `poetry run pylint app/`

## Run the App
Run the app: `poetry run streamlit run app/app.py --server.port 8000`