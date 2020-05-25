## How to setup and run python codes in Microsoft VScode

1. install python (2/3)

$ sudo yum install epel-release
$ sudo yum install python

2. install pip

$ sudo yum install python-pip

3. upgrade pip

$ sudo pip install --upgrade pip

4. install virtualenv

$ sudo pip install virtualenv

5. Create Virtual env in new project

$ mkdir testProject
$ cd testProject
- Python 2: $ virtualenv .venv              # or any name
- Python 3: $ python3 -m venv .venv

6. Activate venv

$ source .venv/bin/activate

7. install any package you like

$ pip install PySide2

8. Deactivate venv

$ deactivate

9. Running python codes in VSCode

- read `tasks.json` and `settings.json` in `.vscode` folder