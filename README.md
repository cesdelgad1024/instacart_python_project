# Instacart — Large-Scale Data Wrangling (3M+ orders, 32M+ rows)

A Python data pipeline over the **Instacart** grocery dataset (**3M+ orders, 32M+ rows**), built
across an 11-notebook workflow: data-quality validation, multi-table merges, derived
feature creation, and grouped aggregation with pandas and Jupyter.

## Pipeline (notebooks, in order)

| Notebook | Step |
|---|---|
| `1_data_types.ipynb` | Data types and efficient loading |
| `2_pandas.ipynb` | Core pandas manipulation |
| `3_data_wrangling_and_subsetting.ipynb` | Cleaning and subsetting |
| `4_data_consistency_checks.ipynb` | **Data-quality checks** — missing values, duplicates, mixed types |
| `5_combining_and_exporting_data_part1/2.ipynb` | **Multi-table merges** and exporting cleaned data |
| `6_deriving_new_variables.ipynb` | **Feature engineering** — derived flags and labels |
| `7_grouping_data_and_aggregating_variables.ipynb` | **Grouped aggregation** and profiling |
| `8_data_visualization_part1/2.ipynb` | Visualizing trends and patterns |
| `9_coding etiquette.ipynb` | Clean, reproducible-code practices |

## What it demonstrates
- **Working at scale** — an 11-notebook pipeline over a 3M+ order (32M+ row) dataset
- **Data-quality engineering** — consistency checks, missing/duplicate handling, type validation
- **Transformation pipeline** — merges → derived features → grouped aggregation → export
- **Stack** — Python · pandas · numpy · matplotlib / seaborn · Jupyter

## Viewing the notebooks
The notebooks render directly on GitHub with every output saved, so no setup is needed to read them.
The raw Instacart data (3M+ orders, 32M+ rows) is too large to commit and is not included in the repo.

---
*Large-scale data-wrangling foundation on my path into cloud data engineering — see
also **[Verity](https://github.com/cesdelgad1024/verity)**, a fully local agentic
RAG system.*
