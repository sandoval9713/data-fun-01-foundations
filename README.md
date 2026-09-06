# Penguin Data Analysis

[![Workflow Guide](https://img.shields.io/badge/Pro--Guide-pro--analytics--02-green)](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
[![Python 3.14](https://img.shields.io/badge/python-3.14%2B-blue?logo=python)](./pyproject.toml)
[![uv managed](https://img.shields.io/badge/uv-managed-DE5FE9)](https://docs.astral.sh/uv/)
[![ty type checked](https://img.shields.io/badge/ty-type_checked-2F80ED)](https://docs.astral.sh/ty/)
[![Zensical docs](https://img.shields.io/badge/Zensical-docs-purple)](https://zensical.org/)
[![MIT](https://img.shields.io/badge/license-see%20LICENSE-yellow.svg)](./LICENSE)

> Professional Python project: inspect data and plan experiments.

## Project Overview
This project analyze the Palmer penguins dataset using Python and pandas. I explored relationships between numeric measurements and created scatterplot to better understand patterns in the data. For my final analysis, I compared bill depth and bill length to see whether penguins with deeper bills also tend to have longer bills.

## Initial Results
The scatterplot shows that bill depth and bill length do not have a simple straight-line relationship. The data appear in distinct groups, which suggets that other characteristics of the penguins may also influence the relationship between bill depth and bill length.

![Scatter plot of bill depth and bill length](docs.images/feature-target-scatter.png)

## Documentation

- [Documentation](https://sandoval9713.github.io/datafun-01-foundations/)

## Data Card

- [Palmer Penguins Data Card](./docs/data-card.md)

## Annotations

- [.annotations/annotations.md](./.annotations/annotations.md)

## Citation

- [CITATION.cff](./CITATION.cff)

## License

This project is licensed under the [MIT License](./LICENSE).

## My Technical Modification
For my final analysis, I changed the target to 'bill_length_mm` and the feature to 'bill_depth_mm`. I chose these measurements because both describe the size and shape of a penguin's bill, and I wanted to see whether penguins with deper bills also tend to have longer bills.
After running the project, the scatterplot showed that the relationship was not as simple as I expected. The data formed different groups, suggesting that other characteristics of the penguins may also influence the relationship between bill depth and bill length.
