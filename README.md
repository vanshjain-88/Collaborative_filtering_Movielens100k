```markdown
# 🎬 Collaborative Filtering on MovieLens 100K

This project implements a **Collaborative Filtering (CF)** based recommendation system using the MovieLens 100K dataset.

The objective is to predict user ratings for movies by leveraging patterns in historical user–item interactions.


## 📌 Project Overview

Collaborative Filtering is a recommendation technique that predicts a user's preference based on the preferences of similar users or items.

In this project:

- The MovieLens 100K dataset is used.
- A user–item interaction matrix is constructed.
- Missing ratings are predicted using collaborative filtering.
- Model performance is evaluated.

---

## 📂 Repository Structure

```

.
├── 2023578_CF_A1.ipynb        # Main implementation notebook
├── 2023578_CF_A1_Report.pdf   # Detailed project report
├── ml-100k/                   # MovieLens 100K dataset
└── README.md

````

---

## 📊 Dataset Details

**Dataset:** MovieLens 100K  
**Users:** 943  
**Movies:** 1,682  
**Ratings:** 100,000  
**Rating Scale:** 1–5  

The dataset is included inside the `ml-100k/` folder.

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/vanshjain-88/Collaborative_filtering_Movielens100k.git
cd Collaborative_filtering_Movielens100k
````

---

### 2️⃣ Install Dependencies

Make sure Python is installed. Then run:

```bash
pip install numpy pandas matplotlib
```

Install any additional libraries if required by the notebook.

---

### 3️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook:

```
2023578_CF_A1.ipynb
```

Run all cells sequentially.

---

## 🧠 Implementation Workflow

1. Load MovieLens dataset
2. Preprocess user and item data
3. Construct user–item rating matrix
4. Apply collaborative filtering algorithm
5. Predict missing ratings
6. Evaluate model performance

---

## 📈 Output

The model generates predicted ratings and evaluates the quality of recommendations using appropriate evaluation metrics.

---

## 📄 Report

A detailed explanation of:

* Problem statement
* Methodology
* Mathematical formulation
* Implementation details
* Results and analysis

is provided in:

```
2023578_CF_A1_Report.pdf
```

---

## 🛠 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook

---

## 📌 Notes

* Keep the `ml-100k` folder in the same directory as the notebook.
* Do not rename dataset files.
* Run notebook cells in order to avoid execution errors.


