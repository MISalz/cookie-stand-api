# Lab 34 - Salmon Cookies
## Project: API Deployment Salmon_cookies
## Author: Michelle Salazar

### PORT - Port Number
see env

## Links and Resources

### Deployed URL
[SalmonCookies](https://cookie-stand-api-ms.herokuapp.com/)

### Github
[gh](https://github.com/MISalz/cookie-stand-api)

## Setup
--.sample.env
required .env samples

## DATABASE_URL - URL to the running Postgres instance/db

Elephantsql
DB_URL = postgres://vcnggiji:Dw-4hOqLmu8SJvgMlooKFzC7xbHsnKqW@heffalump.db.elephantsql.com/vcnggiji

How to initialize/run your application (where applicable)
~ docker compose up

How to use your library (where applicable)
pip freeze > requirements.txt


### Tests
How do you run tests?
Any tests of note?
Describe any tests that you did not complete, skipped, etc

---

Problem Domain:

## Customization Steps

- DO NOT migrate yet
- add additional dependencies as needed
  - Re-export requirements.txt as needed
- change `things` folder to the app name of your choice
- Search through entire code base for `Thing`,`Things` and `things` to modify code to use your resource
  - `project/settings.py`
  - `project/urls.py`
  - App's files
    - `views.py`
    - `urls.py`
    - `admin.py`
    - `serializers.py`
    - `permissions.py`
- Update ThingModel with fields you need
  - Make sure to update other modules that would be affected by Model customizations. E.g. serializers, tests, etc.
- Rename `project/.env.sample` to `.env` and update as needed
- Run makemigrations and migrate commands
- Optional: Update `api_tester.py`
