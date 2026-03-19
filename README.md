# The Correlation Between Democratic Governance and Women's Rights: A Global Analysis of Gender Equality in Democratic and Autocratic Regimes

**Note:** This project was originally developed as the course project of MSML602 - Principles of Data Science during the Spring 2025 semester

## Publication

- [Proposal Definition](./publication/proposal-definition.md)
- [Final Publication](./publication/final-publication.md)
- [Final Publication (IEEE Paper Format)](./publication/final-publication-IEEE.docx)

## Stage 1 - Dataset Extraction, Cleanup, and Research

### Goals

- Transform all the raw datasets from complex Excel or Data files to CSV files.
- Normalize the column names and remove unnecessary columns.
- Shift time series data to have years as rows.
- Document and describe the meaning of each column/predictor.
- Fix empty rows and NaN values.
- Descriptive analysis of the datasets, define scope and properties to analyze.

See [1-dataset-cleanup/README.md](1-dataset-cleanup/README.md) for details and [1-dataset-cleanup/dataset-extraction.ipynb](1-dataset-cleanup/dataset-extraction.ipynb) for the code.

## Stage 2 - EDA and Scope Definition

See [2-eda-scope-definition/README.md](2-eda-scope-definition/README.md) for details.

For the code, see:
- [pca-polity5.ipynb](2-eda-scope-definition/pca-polity5.ipynb)
- [pca-freedom-in-the-world.ipynb](2-eda-scope-definition/pca-freedom-in-the-world.ipynb)
- [pca-lied.ipynb](2-eda-scope-definition/pca-lied.ipynb)
- [pca-global-religious-diversity.ipynb](2-eda-scope-definition/pca-global-religious-diversity.ipynb)
- [pca-national-religion-dataset.ipynb](2-eda-scope-definition/pca-national-religion-dataset.ipynb)
- [pca-georgetown.ipynb](2-eda-scope-definition/pca-georgetown.ipynb)
- [pca-world-bank.ipynb](2-eda-scope-definition/pca-world-bank.ipynb)

## Stage 3 - Merge and Compare Linear Regression

See [3-merge-compare-linear-regression/README.md](3-merge-compare-linear-regression/README.md) for details.

For the code, see:
- [women-rights-and-democracy.ipynb](3-merge-compare-linear-regression/women-rights-and-democracy.ipynb)
- [compare-democracy-indexes.ipynb](3-merge-compare-linear-regression/compare-democracy-indexes.ipynb)

## Stage 4 - SVM and Clustering

For the code, see:
- [svm.ipynb](4-svm-clustering/svm.ipynb)
- [linear-regression-with-religion.ipynb](4-svm-clustering/linear-regression-with-religion.ipynb)
- [continent-enrichment.ipynb](4-svm-clustering/continent-enrichment.ipynb)
- [clustering.ipynb](4-svm-clustering/clustering.ipynb)
- [decision-tree.ipynb](4-svm-clustering/decision-tree.ipynb)