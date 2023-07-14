# jogoTeca_Alura

<a href="https://pypi.org/project/Flask/">
  <img src="https://img.shields.io/badge/Flask-v2.3.2-blue" alt="latest release" />
</a>

<a href="https://pypi.org/project/virtualenv/">
  <img src="https://img.shields.io/badge/virtualenv-v20.23.0-blue" alt="latest release" />
</a>

<br>

## used API "virtualenv"
To import the package that can be used to work with the framework.

```sh
pip install Flask
```

### 📖 Documentation: <br>
[Flask](https://flask.palletsprojects.com/en/2.3.x/) <br>


## used API "virtualenv"
To import the package that can be used to work with the virtual environment.

```sh
pip install virtualenv
```

## Terminal
To create a "virtual environment" for your project and generate the "venv" or "yourVenv" folder
```python
>>> virtualenv -p python3 Venv
reated virtual environment
```

## Activate the environment
To activate the environment, we'll run `source venv/bin/activate`. From now on, there will be a tag (venv) at the beginning of the line in the terminal, indicating that we are in this virtual environment.
`venv\Scripts\Activate`

### for MacOS or Linux:
```python
>>> source venv/bin/activate
```

### For Windows: 
before using the command `(venv\Scripts\Activate)`, you need to release the security system with the following commands:
```python
>>> Get-ExecutionPolicy 
Restricted
>>> Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
>>>  venv\Scripts\Activate
```

