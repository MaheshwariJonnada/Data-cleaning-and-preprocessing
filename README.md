# Data-cleaning-and-preprocessing 
# 📊 Task 1: Data Cleaning and Preprocessing

## 📝 Objective
Clean and prepare a raw dataset by handling:
- Missing values
- Duplicates
- Inconsistent text and formats
- Date and datatype issues

## 🧰 Tools Used
- Python 🐍
- Pandas 🐼

Dataset: **Netflix Movies and TV Shows** from Kaggle  
[Original Dataset on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)

---

## 🧼 Step-by-Step Cleaning Process

### 1. Load the Dataset
```python
df = pd.read_csv("netflix_titles.csv")
