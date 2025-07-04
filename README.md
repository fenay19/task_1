# Task 1 - Population Data Visualization (2023)

This notebook visualizes global population data from a CSV dataset using bar plots and pie charts. It helps identify countries with the highest populations in 2023 and provides engaging, aesthetic visual insights using Python’s data visualization libraries.

---

## 📌 Objective

To perform exploratory data analysis (EDA) on the population data and visualize the top 20 most populous countries in 2023 using:
- Bar charts (horizontal)
- Donut (pie) charts

---

## 🧾 Dataset

- **Source**: World Bank formatted CSV (assumed to be `bank_dataset.csv`)
- **Columns Used**:
  - `Country Name`
  - `Country Code`
  - `Indicator Name`
  - `2023` (Population)

---

## 📁 Repository Structure

```
task_1/
├── task_1.ipynb         # Main Jupyter notebook
├── README.md            # Project documentation
├── requirements.txt     # Python dependencies
├── bank_dataset.csv     # (Optional) Dataset file to be placed here
```

---

## 📊 Visualizations

- **Bar Plot**:
  - Shows Top 20 countries by population in 2023
  - Includes exact population annotations on each bar

- **Donut Chart**:
  - Visualizes the top 10 countries + "Others" as a pie chart
  - Uses a pastel color palette and clean labels

---

## 📦 Requirements

You can install the required Python libraries using:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/task_1.git
cd task_1
```

2. (Optional) Set up a virtual environment:
```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Launch the notebook:
```bash
jupyter notebook task_1.ipynb
```

---

## ✅ Conclusion

This project demonstrates how to transform raw population data into interactive and interpretable insights through charts. Ideal for learners practicing EDA and visual storytelling using Python.

---

## 📜 License

This project is licensed under the MIT License.
