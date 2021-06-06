# URL Cafe

## Install

You must have [poetry](https://python-poetry.org/) installed, then:

```bash
poetry install
```

Now that you have poetry installed, we'll need to create an `.env` file. Please take a look at the `env.example` , and change the variables accordingly.

Then we can run the application:

```bash
uvicorn app.main:app --reload --env-file .env
```

In production you may want to use gunicorn with uvicorn workers. You can get all the information about deployment from [here](https://www.uvicorn.org/deployment/).
 