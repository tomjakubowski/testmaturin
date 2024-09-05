```bash
python -m venv .venv
pip install build
python -m build
# builds wheel with data from testmaturin.data, the default non-configured svalue
pip install dist/testmaturin*.whl
ls .venv/
cat .venv/a.txt
```

See pyproject.toml for more info about the other data directories
