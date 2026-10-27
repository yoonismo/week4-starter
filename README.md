# Week 4 starter

Practice repository for **Week 4: The Propensity Score, Weighting and Doubly Robust Estimation**.
Full instructions: <https://yoonismo.github.io/causal-computing/week4.html>

## What is in here

| File | Purpose |
|---|---|
| `week4.ipynb` | The code from the Week 4 page, in the same order |
| `requirements.txt` | The packages the automatic check installs |
| `.github/workflows/ci.yml` | The automatic check: runs the notebook on GitHub's computer after every push |

## Before you start

Week 4 also uses `scipy` and `matplotlib`. Activate the course environment and install the packages (this works from any folder; the ones you already have are skipped):

```bash
source ~/ECON481/.venv/bin/activate      # macOS
~\ECON481\.venv\Scripts\activate          # Windows (PowerShell)
uv pip install pandas causaldata statsmodels scipy matplotlib
```

Run only the `activate` line for your system.

The notebook downloads its data from the internet, so you need a connection.

## Steps

1. Click **Use this template** → **Create a new repository**, then clone your copy to your computer, as in Week 1 Lab 3.
2. Run `week4.ipynb` in order along with the Week 4 page, and answer the questions in it. In Lab 6, paste the code from your AI assistant into the `# TODO` cell; the check cell right after it compares the numbers with yours.
3. Clear all outputs, then `git add`, `git commit` and `git push`. The **Actions** tab should turn green.
