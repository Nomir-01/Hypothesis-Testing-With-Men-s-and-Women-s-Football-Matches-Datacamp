# Hypothesis Testing with Men's and Women's Football Matches

A statistical analysis comparing scoring patterns in men's and women's international football matches. The notebook filters the source data, evaluates distribution assumptions, selects an appropriate hypothesis test, and reports the resulting significance measure.

## Workflow

1. Load and filter the men's and women's match datasets.
2. Inspect the score distributions and test normality assumptions.
3. Reshape the data for comparison.
4. Run the selected statistical test.
5. Interpret the p-value in the context of the hypothesis.

## Tools

- Python and pandas
- SciPy and Pingouin for statistical testing
- Matplotlib and Seaborn for distribution inspection
- Jupyter Notebook

## Repository contents

- `notebook.ipynb` — complete hypothesis-testing workflow
- `men_results.csv` and `women_results.csv` — match results
- `soccer-pitch.jpg` — project cover image
- `requirements.txt` — Python dependencies

## Run locally

```bash
python -m venv .venv
python -m pip install -r requirements.txt
jupyter lab notebook.ipynb
```

## Project context

This is a personal learning project completed as guided DataCamp coursework. It demonstrates hypothesis formulation, assumption checking, data reshaping, statistical testing, and evidence-based interpretation.
