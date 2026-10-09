# UCSB PSY221A teaching dataset

This is a **doctored dataset prepared for educational use in UCSB PSY221A**. Use it only for course learning projects. **Do not use this version for research, publication, or any other purpose.**

## Original study and materials

Kowal, M., Sorokowski, P., Gjoneska, B., et al. (2025). *Cross-cultural data on romantic love and mate preferences from 117,293 participants across 175 countries.* Scientific Data, 12, 1103. [https://doi.org/10.1038/s41597-025-05365-2](https://doi.org/10.1038/s41597-025-05365-2).

The original study surveyed romantic love, mate preferences, relationship evaluations, and related attitudes. This teaching adaptation starts from a local copy of the authors’ processed dataset, not from the original raw survey exports.

Original data, codebook, survey materials, and processing code are available from the [authors’ OSF repository](https://osf.io/k54fx/), repository DOI [10.17605/OSF.IO/K54FX](https://doi.org/10.17605/OSF.IO/K54FX). The [original codebook is also available directly on OSF](https://osf.io/4e5nr/). The course changes below were made for teaching and should not be attributed to the original authors.

## Files and structure

- `data/raw/data_doctored.csv`: the course input file, with **117,294 rows and 273 columns**.
- `data/raw/country_lookup.csv`: 196 unique course country codes and their names.
- `Codebook.xlsx`: **Variables** describes the columns actually present; **Scoring** explains how to compute composite scores; **Country lookup** repeats the CSV mapping for reference.

The data contain 117,293 original respondent records and one artificial empty-country record. Each original row represents one respondent’s survey record.

The `raw` folder means input to your course project; it does not mean that this file contains the authors’ untouched raw data.

