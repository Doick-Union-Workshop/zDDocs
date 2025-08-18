# zDDocs

**zDDocs** is a documentation repository for DUW (Doick's Union Workshop) project.
It contains guides, technical documentation, and reference materials for developers and users.

The documentation is built using [MkDocs](https://www.mkdocs.org/), making it easy to write, maintain, and publish project docs in Markdown format.

## Project setup

### Requirements
- `Python 3.10+`
- `pip`

### Create virtual environment

```sh
python -m venv env
```

### Activate virtual environment

#### Windows

##### PowerShell

```sh
.\venv\Scripts\Activate.ps1
```

If an “Execution Policy” error appears, you need to allow, for example:

```sh
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
```

##### CMD

```sh
venv\Scripts\activate.bat
```

#### Linux (bash, zsh) / MacOS (bash, zsh)

```sh
source venv/bin/activate
```

#### Fish shell (Linux/Mac)

```sh
source venv/bin/activate.fish
```

### Install dependencies

```sh
pip install -r requirements.txt
```

### Development (hot reload)

```sh
mkdocs serve
```

### Build for production

```sh
mkdocs build
```
