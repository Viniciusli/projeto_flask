# projeto_flask Flask Application

This is a Flask application.

## Installation

From source:

```bash
git clone https://github.com/Viniciusli/projeto_flask projeto_flask
cd projeto_flask
make install
```

From pypi:

```bash
pip install projeto_flask
```

## Executing

This application has a CLI interface that extends the Flask CLI.

Just run:

```bash
$ projeto_flask
```

or

```bash
$ python -m projeto_flask
```

To see the help message and usage instructions.

## First run

```bash
projeto_flask create-db   # run once
projeto_flask populate-db  # run once (optional)
projeto_flask add-user -u admin -p 1234  # ads a user
projeto_flask run
```

Go to:

- Website: http://localhost:5000
- Admin: http://localhost:5000/admin/
  - user: admin, senha: 1234
- API GET:
  - https://localhost:5000/api/v1/product/
  - https://localhost:5000/api/v1/product/1
  - https://localhost:5000/api/v1/product/2
  - https://localhost:5000/api/v1/product/3


> **Note**: You can also use `flask run` to run the application.
