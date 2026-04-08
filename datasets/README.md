# Datasets

Some notebooks in this repository reference external datasets for demonstration purposes.  Due to size restrictions, most datasets are **not** included directly in this repository.  Instead, you will find links or instructions in the notebooks themselves to download the required data.

If you add a new notebook that depends on a dataset, please follow these guidelines:

* If the dataset is small (less than a few megabytes), you may include it in this `datasets/` directory.  Provide a short description of the dataset and its source in this README.
* If the dataset is large, provide clear instructions in the notebook for downloading it.  Prefer widely available sources (e.g., open‑source repositories, Kaggle, UCI Machine Learning Repository) over proprietary or copyrighted data.
* Do **not** commit sensitive or proprietary data.

To contribute a dataset description here, create a subheading with the dataset name and include the following information:

```markdown
## <Dataset Name>

* **Source:** Where the dataset comes from (URL or citation)
* **Description:** Brief summary of what the dataset contains
* **License:** Licensing terms, if known
* **Included files:** Filenames and sizes
```

Example:

```markdown
## Iris Dataset

* **Source:** https://archive.ics.uci.edu/ml/datasets/iris
* **Description:** Classic dataset of 150 iris flowers with four features (sepal length, sepal width, petal length, petal width) and three species labels.
* **License:** Public domain
* **Included files:** `iris.csv` (5 KB)
```
