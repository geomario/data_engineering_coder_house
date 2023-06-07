![CODER HOUSE](entregable_uno/images/Logo_blackbg.png)

# Data Engineering CODER HOUSE Entregables

Coder House Data Engineering Python :snake: deliverables.
By [Geomario](https://github.com/geomario).  
Questions? -> <marm1984@gmail.com>

## Packaging Installation

### Poetry installation

When working with this repo you need Poetry installation since the code is build using Poetry. Poetry is a package manager for managing Python packages. It allows the installation and update packages directly managed by poetry.  
Poetry can be installed either directly from pip or locally.

#### pip installation

```python
pip install poetry
```

#### Local installation

Poetry can be installed directly without pip. For this purpose, give it a read to the documention. Since you need to check which operational system you have. My personal usage was using the official documentation for WSL.

```bsh
curl -sSL https://install.python-poetry.org | python3 -
```

Documentation: [Poetry Installation](https://python-poetry.org/docs/#installing-with-the-official-installer)

## Building Locally

### Activate Virtual environment

Poetry manages virtual environment. For this development, Python 3.10 was used.
For installing different Python versions, you should install PYENV.

```bsh
pyenv install 3.10
pyenv local 3.10  # Activate Python 3.10 for the current project
```

After installing the selected python version, start the environment for poetry.

```bsh
poetry env use python3.10 # Uses the selected Python version
```

Since Poetry has been installed. You should allocate the terminal where the location of the **_pyproject.toml_** and execute the command that will read and bring the modules that match **_poetry.lock_** accordingly.  
For more information read the documention [Poetry installation TOML](https://python-poetry.org/docs/cli/#install)

After installing python3.10 You can activate the virtual environment for Poetry inside the folder that contains the files mentioned above with the command:

```bsh
poetry shell
```

Install the packages to poetry when is activated.

```bsh
poetry install
```

# Special consideration

Remember, when you try to load the notebooks and make them work. You have to create an .env file that allows you to set the credentials you need for the service to work. There is a .env.example file that guides you with the variables you need to create in the .env file.

# Extensions

If you wanto modify the **drawio** and **excaldraw**, please install the next VSCODE extensions such that you can modify them.

Name: vscode-drawio
Id: eightHundreds.vscode-drawio
Description: drawio editor
Version: 1.0.3
Publisher: eightHundreds
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=eightHundreds.vscode-drawio

Name: Excalidraw
Id: pomdtr.excalidraw-editor
Description: Draw schemas in VS Code using Excalidraw
Version: 3.5.1
Publisher: pomdtr
VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=pomdtr.excalidraw-editor

You are set to go

### Happy coding :happy:

# Entregables

Entregables are the homeworks to deliver to the tutor. The folders are created with the names corresponding to the entregable in turn:

[Entregable_uno](/home/marm1984/github/data_engineering_coder_house/entregable_uno)  
[Entregable_dos](/home/marm1984/github/data_engineering_coder_house/entregable_dos)  
[Entregable_tres](/home/marm1984/github/data_engineering_coder_house/entregable_tres)
