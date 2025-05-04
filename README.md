# ML-DevSalaryPredictor

Predict developer salaries based on years of experience and their specialization using a simple linear regression model.

## 📌 Project Overview

This is an interactive Python project that uses **Linear Regression** to estimate the salaries of developers based on two factors:

* 🧠 **Years of Experience**
* 💼 **Field of Specialization** (e.g., Web Developer, Data Scientist, etc.)

Users can select a specialization, view the regression plot, and get salary predictions dynamically through terminal input.

## 📊 Tech Stack

* **Language:** Python 🐍
* **Libraries:**

  * `numpy` — Numerical operations
  * `pandas` — Data handling and preprocessing
  * `scikit-learn` — Machine Learning model
  * `matplotlib` — Data visualization

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/ML-DevSalaryPredictor.git
cd ML-DevSalaryPredictor
```

### 2. Install dependencies

```bash
pip install numpy pandas matplotlib scikit-learn
```

### 3. Run the script

```bash
python salary_predictor.py
```

Follow the on-screen prompts to select a field and enter experience to see the predicted salary.

## 📁 Project Structure

```
DevSalaryPredictor/
│
├── SoftComputingProjectEdited.ipynb       # Main interactive script
└── README.md                              # Project documentation
```

## 📊 Example Usage

```bash
Available Fields:
1. Web Developer
2. Data Scientist
...

You selected: Web Developer

Equation of the line: salary = 1998.31 * experience + 5002.14

Enter years of experience to predict salary: 5
Predicted Salary for 5 years of experience: 14993.69
```

## 📂 Dataset

This project uses a **custom-built dataset** generated programmatically to simulate realistic salary trends.

Each field has a base salary and increment per year, plus some random variation to mimic real-world unpredictability. The data is managed entirely using the `pandas` library and is not stored in external files.

## 🔮 Future Improvements

* Export dataset to CSV for reuse
* Add GUI or web interface with Streamlit
* Use more advanced models or compare algorithms
* Include region or education level as additional features

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License.

---

Made with 💻 by **Mohamed Morsi**
