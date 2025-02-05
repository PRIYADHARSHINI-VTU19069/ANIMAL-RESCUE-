# Animal Rescue Dataset

This dataset contains information about various animals, their age, weight, and health-related symptoms such as fever, cough, rash, vomiting, diarrhea, and whether they are healthy. This data can be useful for animal rescue and health assessment projects.

## Dataset Overview

The dataset consists of the following columns:

| Column Name | Description                                        |
|-------------|----------------------------------------------------|
| `animal_id` | Unique identifier for each animal.                |
| `age`       | Age of the animal in years.                       |
| `weight`    | Weight of the animal in kg.                       |
| `fever`     | Indicator if the animal has fever (1 = Yes, 0 = No). |
| `cough`     | Indicator if the animal has a cough (1 = Yes, 0 = No). |
| `rash`      | Indicator if the animal has a rash (1 = Yes, 0 = No). |
| `vomiting`  | Indicator if the animal is vomiting (1 = Yes, 0 = No). |
| `diarrhea`  | Indicator if the animal has diarrhea (1 = Yes, 0 = No). |
| `healthy`   | Indicator if the animal is healthy (1 = Yes, 0 = No). |

## Sample Data

Here is a small sample of the dataset:

| animal_id | age | weight | fever | cough | rash | vomiting | diarrhea | healthy |
|-----------|-----|--------|-------|-------|------|----------|----------|---------|
| 1         | 3   | 1400   | 0     | 1     | 0    | 0        | 1        | 0       |
| 2         | 5   | 20     | 1     | 1     | 0    | 0        | 0        | 1       |
| 3         | 6   | 1100   | 1     | 1     | 0    | 0        | 0        | 0       |

## Usage

This dataset can be used for training machine learning models, analyzing animal health conditions, or other relevant research in animal welfare.

### Example Code (Python)

```python
import pandas as pd

# Load dataset
df = pd.read_csv('dataset.csv')

# Display first few rows
print(df.head())

