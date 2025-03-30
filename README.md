# My Jupyter Project

This project is designed to demonstrate the use of Jupyter Labs for interactive Python development, utilizing the `ollama` library for AI interactions and `uv` for package management.

## Setup

To set up the project, follow these steps:

1. **Install `uv`**:
   ```
   pip install uv
   ```

2. **Install Dependencies**:
   Use `uv` to install the project dependencies listed in `pyproject.toml`:
   ```
   uv pip install -r requirements.txt
   ```

3. **Run Jupyter Labs**:
   Start Jupyter Labs with the following command:
   ```
   jupyter lab
   ```

4. **Configure VSCode Extension**:
   To use the Jupyter server with VSCode, follow these steps:
   - Open VSCode and install the "Jupyter" extension if not already installed.
   - Open the Command Palette in VSCode (`Ctrl+Shift+P` or `Cmd+Shift+P` on Mac).
   - Type "Jupyter: Specify Jupyter server for connections" and select it.
   - Enter the URL of your Jupyter server, typically `http://localhost:8888`.

## Usage

Once set up, you can open the `hello_world.ipynb` notebook in Jupyter Labs to see examples of Python code execution and interaction with the `ollama` library.

Happy coding!
