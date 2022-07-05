# Modules
To manage the self-written functions - see 
[official docs](https://docs.python.org/3/tutorial/modules.html#packages) &
[examples](https://realpython.com/python-import/#import-internals)

## The Module Search Path - PYTHONPATH
Say we import `mymodule`, python would<br>
1. search for a built-in module with that name. <br>
2. search in  in a list of directories given by the variable *sys.path* which is initialized from these locations: <br>
   - The directory containing the input script
   - **PYTHONPATH** (a list of directory names, with the same syntax as the shell variable PATH).
   - The installation-dependent default.

## Packages
Here is a template structure to maintain a growing collection of modules. 
```python
sound/                          #Top-level package
      __init__.py               #Initialize the sound package
      formats/                  #Subpackage for file format conversions
              __init__.py
              wavread.py
              wavwrite.py
              aiffread.py
              aiffwrite.py
              auread.py
              auwrite.py
              ...
      effects/                  #Subpackage for sound effects
              __init__.py
              echo.py
              surround.py
              reverse.py
              ...
      filters/                  #Subpackage for filters
              __init__.py
              equalizer.py
              vocoder.py
              karaoke.py
              ...
```

## Reloading Modules
```python
import mypy
import importlib
importlib.reload(mypy)
```


