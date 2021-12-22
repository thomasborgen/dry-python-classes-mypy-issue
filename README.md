# Classes issue:

```sh
git clone git@github.com:thomasborgen/dry-python-classes-mypy-issue.git
cd dry-python-classes-mypy-issue
poetry install

poetry run mypy .
```

output is:

```sh
setup.cfg:2: error: Error importing plugin "classes.contrib.mypy.classes_plugin": cannot import name 'TypeVarDef' from 'mypy.types' (/home/thomas/opensource/classes-mypy-problem/.venv/lib/python3.9/site-packages/mypy/types.cpython-39-x86_64-linux-gnu.so)
Found 1 error in 1 file (errors prevented further checking)
```
