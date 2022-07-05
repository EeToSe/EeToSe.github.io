# Virtual environments

[virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/index.html): organizes all of your virtual environments in one place

In order to keep your environment consistent: `freeze` the current state of the environment packages. 
```bash
pip freeze > requirements.txt
```

Re-create the environment: `install` the same packages using the same versions.
```bash
pip install -r requirements.txt
```