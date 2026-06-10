I would recommend changing the torch links in pyproject.toml to what is appropriate according to the CUDA version supported by your local machine (check out `MLFlow steps.ipynb`), 
then use
```uv sync```
and after ensuring that docker is installed and running, run
```docker compose up```