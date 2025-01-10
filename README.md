# Student Performance Index Prediction

This project demonstrates the implementation of multiple variable linear regression from scratch using Python. The goal is to predict a student's performance index based on the following factors:

- **Hours Studied**
- **Previous Scores**
- **Extracurricular Activities**
- **Sleep Hours**
- **Sample Question Papers Practiced**

## Dataset

The dataset used for this project is available on Kaggle: [Student Performance Dataset](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression).

---

## Implementation Overview

### Key Features:

1. **Z-Score Normalization**  
   Standardizes the data to center it around 0 and scale it to unit variance.

2. **Custom Gradient Descent**  
   Performs weight and bias updates iteratively to minimize the Mean Squared Error (MSE).

3. **Cost Function**  
   Evaluates the model's performance using MSE.

4. **Feature Engineering**  
   Adds polynomial features for better model accuracy.

5. **Visualization**  
   Visualizes actual vs. predicted values for better understanding of the model's fit.

6. **R² Score Calculation**  
   Measures the goodness of fit for the regression model.

7. **Custom Predictions**  
   Predicts the performance index for new input data.

---

## Getting Started

### Prerequisites:

- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`

### Installation:

1. Clone this repository.
   ```bash
   git clone https://github.com/KartikAg13/student_performance_prediction.git
   cd student_performance_prediction
   ```

2. Download the dataset from the [Kaggle link](https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression) and place it in the root folder.

---

## How to Use

1. **Run the Notebook**  
   Open the Python notebook file in Jupyter or any compatible environment and execute the cells step-by-step.

2. **Make Predictions**  
   Input new data in the format `[Hours Studied, Previous Scores, Extracurricular Activities, Sleep Hours, Sample Question Papers Practiced]` to predict the Performance Index.

---

## Results

- **Initial Cost**: Evaluates the model's cost before training.  
- **Final Cost**: Reduced cost after applying gradient descent.  
- **R² Score**: Indicates how well the regression model fits the data.  

---

## Project Structure

- **`main.ipynb`**: Main implementation notebook.
- **`README.md`**: Project documentation.

---

## Example Prediction

Input:  
```python
x_predict = np.array([6, 71, 1, 8, 2])
```

Output:  
```bash
Predicted Performance Index: 85.43
```

---

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes. 

---


## Acknowledgments
- [Kaggle](https://www.kaggle.com) for providing the dataset.
- [Coursera](https://www.coursera.org/learn/machine-learning/) for inspiration through the Machine Learning course.
