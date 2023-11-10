# dsa-notebook

Learn Data Structures and Algorithms in an interactive Jupyter Notebook!

Language(s): Python 3

<br>

## Local Deployment

#### Requirements

- Python 3
- pip

<br>

### Setup

(replace `python`/`pip` with `python3`/`pip3` for Ubuntu-based Linux distrobutions if needed). 

<br>

1. Clone the github repository

```bash
git clone https://github.com/kylecurtis/dsa-notebook.git
```

<br>

2. Change into directory

```bash
cd path/to/dsa-notebook
```

<br>

3. Create and source a Python virtual environment

```bash
python -m venv venv/
```

<br>

4. Activate venv

| Platform | Shell       | Command to activate virtual environment           |
|----------|-------------|---------------------------------------------------|
| POSIX    | bash/zsh    | `$ source venv/bin/activate`                    |
|          | fish        | `$ source venv/bin/activate.fish`               |
|          | csh/tcsh    | `$ source venv/bin/activate.csh`                |
|          | PowerShell  | `$ venv/bin/Activate.ps1`                       |
| Windows  | cmd.exe     | `C:\> venv\Scripts\activate.bat`                |
|          | PowerShell  | `PS C:\> venv\Scripts\Activate.ps1`             |


<br>

5. Install the required dependencies

```bash
pip install -r requirements.txt
```

<br>

`requirements.txt` is in the root directory of the repository.

<br>

5. Run the notebook

After completing each of the previous steps successfully, you can now run the notebook.

You can run the notebook in your choice of IDE (VSCode, PyCharm, etc.), or you can run it in the browser by running the following command in your terminal (assuming venv is still active):

```bash
jupyter lab
```

