# Carrot Transform Jupyter

A simple setup for running Jupyter notebooks with `carrot-transform` using `uv`.

## Quick Start

1. Install dependencies:
   ```bash
   uv add notebook
   ```

2. Start Jupyter:
   ```bash
   uv run jupyter notebook
   ```

3. In your notebook, install and use carrot-transform:
   ```python
   %pip install carrot-transform
   from carrot_transform import cli  # adjust import as needed
   ```

That's it. The notebook environment is managed by `uv`, and you can install `carrot-transform` directly in your notebook cells.

