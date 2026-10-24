# Student Performance Analysis

Exploratory analysis of math, reading, and writing scores using Pandas and Matplotlib.

## Analysis

- Inspect the dataset and calculate the mean of three subject scores.
- Compare score distributions across student groups.
- Compare high-score (>80) and low-score (<40) rates.

## Findings

Students with completed test preparation and standard lunch have higher observed high-score rates. Group distributions overlap; these comparisons describe associations and do not establish causes.

## Run locally

```bash
python -m pip install -r requirements.txt
jupyter lab notebooks/student_performance_eda.ipynb
```

Keep `data/student_performance.csv` in the project and run cells from top to bottom.

## Dataset and limitations

Initial EDA complete; group differences describe associations rather than causal effects.

Source: [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) by Kaggle contributor `spscientist`. Download instructions are in [data/README.md](data/README.md). Data is excluded from this repository; consult the source page for its current license and terms. Kaggle revisions may differ from the local snapshot used here.

## Structure

- `notebooks/` — analysis notebooks.
- `data/` — local CSV and data instructions.
- `requirements.txt` — Python dependencies.

Run Jupyter from the project root. See `data/README.md` for the expected dataset filename.

## Validation

All 8 code cells executed successfully from a fresh kernel on October 25, 2026. Saved outputs are included for GitHub preview. The local dataset contains 1,000 student records; no exact duplicate rows were found.
