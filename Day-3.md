---

---

--- Before Day-3 ---
I already knew basic Python programming and how to run Python scripts. However, I was not familiar with UV, lockfiles, project initialization using `uv init`, or the differences between traditional virtual environments and UV-managed environments.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Day-3 Checklist

* [x] I can run a Python script using `uv run script.py` without setting up a local virtual environment
* [x] I know where the temporary virtual environment is created when running the `uv add --script script.py pandas` command followed by `uv run script.py`
* [x] I can create a new Python project using `uv init` and understand what `pyproject.toml` is used for
* [x] I can add a dependency (e.g., `requests`) using `uv add` and see it reflected in the lockfile
* [x] I can create a traditional virtual environment using `uv venv` and know when to use it
* [x] I understand why installing packages globally with `pip install` is a bad habit
* [x] I can open a project in VS Code, select the correct Python interpreter, and run code from the integrated terminal
* [x] I know the difference between a `.py` script and a `.ipynb` notebook, and when to use each

--- After Day-3 ---
I learned how UV simplifies Python development by handling environments, dependencies, and project setup in a more structured way. I also learned how lockfiles ensure reproducible environments, how `pyproject.toml` stores project metadata, and how to correctly configure Python interpreters inside VS Code.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

--- Feedback (Suggestions for the TDS Team) ---
The UV demonstration was very helpful because it showed a modern workflow for Python development. The comparison between traditional virtual environments and UV-managed projects made the advantages very clear. More hands-on exercises involving dependency management and lockfiles would be useful for reinforcing the concepts.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

---

---

Personal Notes:

* `uv run` can execute scripts without manually activating a virtual environment.
* `uv init` creates a structured Python project.
* `pyproject.toml` stores project configuration and dependencies.
* `uv add` updates project dependencies and lockfiles.
* VS Code should be configured to use the correct interpreter.
* `.py` files are scripts, while `.ipynb` files are interactive notebooks.
