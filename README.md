# Carrot Transform Jupyter

Run Carrot Transform in Jupyter notebooks.

## Setup

Start with a fresh repo and set up the environment:

```bash
uv add notebook
uv run jupyter notebook
```

This starts Jupyter and opens it in your browser. You now have a notebook environment managed by `uv`.

## Install Carrot Transform

In a notebook cell, install carrot-transform:

```python
%pip install carrot-transform
```

Now you can use the `carrot-transform` CLI command in your notebook.

## Running the Notebook

Open `carrot_transform.ipynb` and run the cells (Shift+Enter or click Run). The notebook uses `subprocess` to call the `carrot-transform` CLI command.

## Output

The output files are written to `carrottransform/examples/test/test_output/` (or whatever you set in `--output-dir`). The notebook will list the generated TSV files after running.

## Clearing Outputs

To clear old cell outputs:
- **All outputs**: Cell → All Output → Clear
- **One cell**: Click cell → Cell → Current Outputs → Clear

Or just re-run the cells - new output replaces the old.

## More Info

See the [Carrot Transform docs](https://carrot.ac.uk/transform/quickstart) for all the command options.

