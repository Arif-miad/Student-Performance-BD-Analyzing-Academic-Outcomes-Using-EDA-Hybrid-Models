# **                                                                          project overview              **

# **Student Performance-BD: Analyzing Academic Outcomes Using EDA & Hybrid Models**

## **Overview**
This project aims to analyze and predict the academic performance of students from various regions in Bangladesh. Using the **Student Performance-BD** dataset, which includes 24 attributes related to demographics, academic metrics, extracurricular activities, and other factors, we perform **Exploratory Data Analysis (EDA)** and develop a **Hybrid Machine Learning Model** to predict students' academic success.

The insights from this project can be used to identify key factors influencing academic outcomes and help guide students in choosing the most suitable educational path based on their individual profiles.

---

## **Dataset**
The **Student Performance-BD** dataset contains information about students' demographics, academic performance, extracurricular participation, and other relevant factors. Key attributes include:

- **Demographics**: Age, Gender, Residence (Urban/Rural)
- **Educational Background**: Academic level, Group (Science/Commerce), etc.
- **Academic Scores**: English, Math, Science, Social Science, etc.
- **Extracurricular Activities**: Participation in activities like art/culture.
- **Other Factors**: Attendance, Type of school (Private/Govt/Semi-Govt), etc.

### **Dataset Sample**
| Student ID | Name               | Age | Gender | Residence | Group  | Attendance | English | Math | Science | Social Science | Art/Culture | Academic Scores |
|------------|--------------------|-----|--------|-----------|--------|------------|---------|------|---------|----------------|-------------|-----------------|
| 0          | Avi Biswas          | 16  | Male   | Urban     | Science| 95         | 95      | 98   | 92      | 94             | Yes         | 98              |
| 1          | Taslima Sultana     | 18  | Female | Rural     | Commerce| 92         | 65      | 71   | 40      | 78             | No          | 80              |
| 2          | Md Adilur Rahman    | 15  | Male   | Rural     | Commerce| 81         | 64      | 78   | 58      | 86             | Yes         | 74              |
| 3          | Saleh Ahmed         | 16  | Male   | Rural     | Science| 90         | 84      | 90   | 85      | 86             | Yes         | 88              |
| 4          | Din Islam           | 17  | Male   | Urban     | Commerce| 75         | 54      | 70   | 45      | 79             | Yes         | 76              |

---

## **Project Goals**
- Perform **Exploratory Data Analysis (EDA)** to uncover patterns and correlations in the dataset.
- Preprocess the data for machine learning model training.
- Develop a **Hybrid Machine Learning Model** combining multiple algorithms (e.g., Random Forest, Gradient Boosting).
- Predict student academic performance across various subjects.
- Evaluate and visualize model performance using metrics such as **accuracy**, **precision**, **recall**, and **ROC-AUC**.

---

## **Project Structure**
```plaintext
Student_Performance_BD/
├── data/
│   └── student_performance_bd.csv        # Dataset file
├── notebooks/
│   └── EDA_and_Model_Development.ipynb   # Jupyter notebook with EDA and modeling steps
├── src/
│   ├── preprocessing.py                 # Data cleaning and preprocessing scripts
│   ├── models.py                        # Machine learning model implementation
│   └── evaluation.py                    # Model evaluation and performance visualization
├── results/
│   └── plots/                           # Folder for generated plots
├── README.md                            # Project documentation
├── requirements.txt                     # Python dependencies
└── LICENSE                              # Project license
```

---

## **Installation**
Follow the instructions below to set up this project on your local machine.

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Student_Performance_BD.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Student_Performance_BD
   ```

3. **Install dependencies**:
   Use `pip` to install the required packages listed in `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

---

## **Usage**
### **Run the EDA and Modeling Notebook**:
```bash
jupyter notebook notebooks/EDA_and_Model_Development.ipynb
```

### **Data Preprocessing and Model Training**:
Run the preprocessing and model training scripts in Python:
```bash
python src/preprocessing.py
python src/models.py
```

### **Evaluate the Model and Visualize Results**:
Use the evaluation script to visualize model performance:
```bash
python src/evaluation.py
```

---

## **Features**
- **Exploratory Data Analysis (EDA)**:
  - Statistical analysis (mean, median, correlation).
  - Visualizations: Histograms, Box Plots, Pair Plots, Heatmaps.
  
- **Machine Learning Models**:
  - Hybrid model combining **Random Forest** and **Gradient Boosting** for predicting student performance.
  - Model hyperparameter tuning and cross-validation.

- **Model Evaluation**:
  - **Accuracy**, **Precision**, **Recall**, **F1-Score**, and **ROC-AUC** curves.
  - **Learning Curves** and **Confusion Matrices** for evaluating model performance.

---

## **Results**
The hybrid model achieved the following performance metrics on the test data:
- **Accuracy**: `0.9640162507254788`
- **Precision**: `0.9505736244243131`
- **Recall**: ` 0.8347133112725867%`
- **F1-Score**: `0.8813750794053076`
- **ROC-AUC**:  `0.9943288855613831`

### **Key Insights**:
- Students' **attendance**, **extracurricular activity participation**, and **group choice (Science/Commerce)** were significant predictors of academic performance.
- Urban students tend to have better scores in subjects like **English** and **Math** compared to rural students.

---

## **Contributing**
Contributions are welcome! If you’d like to contribute, follow these steps:

1. Fork the repository.
2. Create a new feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   git push origin feature-name
   ```
4. Open a pull request.

---

## **License**
This project is licensed under the **MIT License**. See the `LICENSE` file for more information.

---

## **Contact**
**Author**: Arif Mia  
📧 [arifmiahcse@gmail.com]  
💼 [www.linkedin.com/in/arif-miah-8751bb217]  

Feel free to reach out for collaborations or feedback!

