# DATA622
Data 622 Machine Learning


You can run this using a python venv environment. Below are some commands that should create the environment for you.

```
python -m venv data622-python-venv
source data622-python-venv/bin/activate
pip install -r requirements.txt
```

To add any other packages, all you need to do is:
1. install it like regular using `pip install ...`
2. overwrite the `requirements.txt` file by running:

```
pip freeze > requirements.txt
```