# 📊 Youth Tobacco Use Dataset – YTS Survey

This repository contains a dataset collected from the **Youth Tobacco Survey (YTS)**, focusing on tobacco use among young individuals. The dataset provides valuable insights into smoking habits, demographic factors, and survey-based measurements.

## 📁 Dataset Overview

- **Source**: Youth Tobacco Survey (YTS)
- **Total Records**: 10,600
- **Columns**: 31
- **Format**: CSV / Parquet
- **Topics Covered**:
  - Cigarette and smokeless tobacco use
  - Demographic stratification (age, gender, race, education)
  - Geolocation of surveyed individuals
  - Confidence intervals and error margins
  - Data measurement types and standard errors

## 🏗️ Data Structure

The dataset includes the following key columns:

- `YEAR`: Year of data collection
- `LocationAbbr`: State abbreviation
- `LocationDesc`: Full state name
- `TopicType`: Type of topic (e.g., Tobacco Use)
- `TopicDesc`: Detailed topic description
- `MeasureDesc`: Measurement description (e.g., Smoking Status)
- `DataSource`: Data source identifier
- `Response`: Survey response type (e.g., Ever Smoked, Frequent User)
- `Data_Value`: Percentage or numerical value of response
- `Gender`, `Race`, `Age`, `Education`: Demographic attributes
- `GeoLocation`: Latitude and longitude of survey response
- `StratificationID*`: Various stratification identifiers

## 🚀 Usage

This dataset can be used for:
- **Machine Learning Models**: Predicting tobacco usage trends.
- **Public Health Analysis**: Understanding patterns of youth smoking.
- **Policy Making**: Assisting policymakers in tobacco control strategies.
- **Visualization & Reports**: Creating data visualizations and statistical reports.

## 🔗 Access

The dataset is available on:
- **Hugging Face**: [https://huggingface.co/datasets/PTKares/Youth_Tobacco_Survey__YTS__Data](#)
- **GitHub**: Clone or download from this repository.

## 📜 License

This dataset is released under the **MIT License**. You are free to use, modify, and distribute it, provided that appropriate credit is given to the original authors.

---

For any questions or collaboration inquiries, feel free to open an issue or reach out!

