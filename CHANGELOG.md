# Changelog

All notable changes to this project will be documented in this file.

## [1.0.0] - 2021-01-27

### Added

- ***Data preparation***

- ***Visualisation.*** Pretty bar plot of A/B conversion rates

- ***Statistical test.***. Z-test comparing two conversion rates as proportions in Binomial distributions. We assume that variances are equal

- ***Important values to report.***. P-value, z-statistic and confidence intervals for true conversion rates

### Removed

- "EDA.ipynb" was renamed into "Analysis.ipynb"

### TODO

- Use information about time. Build time series graph for days of week or other periods. Check if conversion rates increse (or decrease) in some period (for example, holidays). If it's true, split data by period and perform tests on each period.
