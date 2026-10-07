# Vietnam Health Survey Analysis

This project analyzes survey data related to health awareness, healthcare access, and attitudes toward routine medical checkups in Vietnam. The work explores how demographic factors such as age, education, location, and employment status relate to respondents’ health priorities and their willingness to seek care.

## Project Overview

The dataset contains individual-level survey responses about health behaviors, insurance coverage, check-up habits, perceived health status, and attitudes toward medical care. The analysis focuses on patterns such as:

- Which age groups are most likely to attend health clinics
- How education level affects health priorities and trust in care
- Whether location influences attitudes toward checkups
- How people perceive public health and the usefulness of digital health tools
- Whether respondents would respond positively to a healthcare app or reminder system

## Objectives

- Clean and structure the raw survey dataset
- Document the variable definitions and coding scheme
- Explore demographic patterns in health behavior
- Create visualizations to communicate findings clearly
- Summarize insights for public health and health communication decisions

## Repository Structure

- `data/raw/vietnam-health.csv` — original survey dataset
- `data/clean/clean_vietnam-health.csv` — cleaned and prepared dataset used for analysis
- `data/data_dictionary.md` — detailed description of variables and categories
- `notebooks/cleaning_data.ipynb` — data cleaning and preparation steps
- `notebooks/analysis.ipynb` — exploratory analysis and charts
- `notebooks/master.ipynb` — notebook workflow to run the project in sequence
- `README.md` — project overview and usage instructions

## Data Description

The dataset includes survey responses from a health and wellbeing study in Vietnam. It contains demographic information and health-related variables such as:

- Age, sex, job status, marital status, education level
- Height, weight, BMI, and health insurance coverage
- Location and region of residence
- Check-up frequency and time since last medical visit
- Perceived barriers to care (cost, time, fear of diagnosis, distrust in quality)
- Attitudes toward health priorities and public health
- Perceptions of service quality and willingness to use health technology

A complete description of the columns can be found in `data/data_dictionary.md`.

## Tools and Dependencies

This project uses Python and common data-science libraries, including:

- pandas
- matplotlib
- seaborn
- Jupyter Notebook

## Setup

1. Clone the repository.
2. Navigate to the project folder.
3. Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

4. Install the required packages:

```bash
pip install pandas matplotlib seaborn jupyter
```

## How to Run the Analysis

Open the project in Jupyter Notebook and run the notebooks in order:

```bash
jupyter notebook
```

Then open:

- `notebooks/cleaning_data.ipynb` to review the data cleaning process
- `notebooks/analysis.ipynb` to view the analysis and visualizations
- `notebooks/master.ipynb` to run the overall workflow together

## Workflow Summary

1. Load the raw dataset from `data/raw/`
2. Clean and standardize values in `cleaning_data.ipynb`
3. Export the cleaned file to `data/clean/clean_vietnam-health.csv`
4. Explore patterns in health attitudes and access in `analysis.ipynb`
5. Use the output to interpret trends by age, region, education, and health behavior

## Notable Analysis Themes

The notebook analysis focuses on themes such as:

- Age patterns in clinic attendance and healthcare use
- Education level and health-priority perceptions
- Regional differences in attitudes toward health checkups
- Perceptions of public health by age group
- Possible use of healthcare apps and digital tools to encourage preventive care

## Notes

- Some variables are coded using short text labels rather than clear full phrases, so the data dictionary is important for interpretation.
- The cleaned dataset is designed for reproducible analysis and visualization.
- This project is primarily exploratory and descriptive rather than predictive.

## License

This project is for educational and analytical use within the repository context.

## Acknowledgment

The raw survey data used in this project was sourced from the CMU Statistics data repository and adapted for analysis in this project workflow.
