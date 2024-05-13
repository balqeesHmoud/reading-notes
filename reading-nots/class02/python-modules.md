

### Python Modules
- **Definition**: Modules are files containing Python code that can be imported into other Python programs.
- **Types of Modules**:
  - Python modules (written in Python)
  - Built-in modules (part of Python's standard library)
  - Extension modules (written in C and dynamically loaded)

- **Importing Modules**:
  - Use the `import` statement (`import mod`) to import a module.
  - Access module contents using dot notation (`mod.s`, `mod.foo()`).

- **Module Search Path**:
  - Python searches for modules in directories specified by `sys.path`.
  - Includes the current directory, directories in `PYTHONPATH`, and installation-specific directories.

- **Import Variations**:
  - `import mod`
  - `from mod import s, foo`
  - `from mod import *`
  - `import mod as my_module`

### Python Packages
- **Definition**: Packages are directories containing modules and an `__init__.py` file.
- **Hierarchical Structure**: Packages can have subpackages, organized using dot notation.

- **Package Initialization**:
  - `__init__.py` is executed when a package is imported.
  - Initialization code (e.g., setting up package-level data) can go in `__init__.py`.

- **Importing Packages**:
  - Use dot notation to import modules from packages (`import pkg.mod1`).
  - `__init__.py` can define `__all__` to specify what gets imported with `from pkg import *`.

- **Subpackages**:
  - Packages can have nested subpackages to organize code further.
  - Use dot notation for importing from subpackages (`import pkg.sub_pkg1.mod1`).

### Best Practices and Tips
- Avoid using `from module import *` for large-scale production code.
- Use `__init__.py` to set up package-level initialization and control what's imported.
- Use absolute or relative imports (`from ..sub_pkg1.mod1 import foo`) for accessing modules within packages.

