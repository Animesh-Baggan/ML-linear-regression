# ML-linear-regression

# Machine Learning Regression Analysis Project

This project contains Jupyter notebooks demonstrating various machine learning regression techniques using Python. The project includes both simple linear regression and multiple regression analysis with data visualization.

## 📁 Project Structure

```
Test/
├── ML Multiple Regresion.ipynb     # Multiple regression analysis with synthetic data
├── Projects/
│   └── ML Linear Agg.ipynb         # Linear regression with real placement data
├── README.md                       # This file
└── [other Python files]
```

## 🎯 Project Overview

### 1. Multiple Regression Analysis (`ML Multiple Regresion.ipynb`)
- **Purpose**: Demonstrates multiple regression using synthetic data
- **Features**: 
  - Uses `sklearn.datasets.make_regression` to generate synthetic data
  - Creates 3D visualizations using Plotly
  - Implements multiple regression with 2 features
  - Includes model evaluation metrics

### 2. Linear Regression Analysis (`Projects/ML Linear Agg.ipynb`)
- **Purpose**: Real-world linear regression analysis
- **Dataset**: Placement data (CGPA vs Package/Salary)
- **Features**:
  - Data preprocessing and exploration
  - Train-test splitting
  - Linear regression model training
  - Model evaluation and visualization
  - Comprehensive comments explaining each step

## 🛠️ Technologies Used

- **Python 3.12**
- **Jupyter Lab/Notebook**
- **Key Libraries**:
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computing
  - `scikit-learn` - Machine learning algorithms
  - `plotly` - Interactive data visualization
  - `matplotlib` - Static plotting

## 📦 Installation & Setup

### Prerequisites
- Python 3.12 or higher
- Anaconda or Miniconda (recommended)

### Installation Steps

1. **Clone or download this repository**
   ```bash
   cd /path/to/your/project
   ```

2. **Install required packages**
   ```bash
   # Using conda (recommended)
   conda install pandas numpy scikit-learn plotly matplotlib jupyter
   
   # Or using pip
   pip install pandas numpy scikit-learn plotly matplotlib jupyter
   ```

3. **Start Jupyter Lab**
   ```bash
   jupyter lab
   ```

4. **Open the notebooks**
   - Navigate to the notebook files in Jupyter Lab
   - Make sure to select the correct kernel (Python 3)
   - Run cells sequentially

## 🚀 Usage

### Running the Multiple Regression Notebook
1. Open `ML Multiple Regresion.ipynb`
2. Run all cells in order
3. The notebook will:
   - Generate synthetic regression data
   - Create a 3D scatter plot visualization
   - Perform multiple regression analysis

### Running the Linear Regression Notebook
1. Open `Projects/ML Linear Agg.ipynb`
2. Ensure you have the placement dataset (`placement.csv`)
3. Run cells sequentially to:
   - Load and explore the data
   - Split data into training and test sets
   - Train a linear regression model
   - Evaluate model performance

## 📊 Key Features

### Data Visualization
- **3D Scatter Plots**: Interactive visualizations using Plotly
- **2D Scatter Plots**: Traditional matplotlib visualizations
- **Model Performance Metrics**: R² score, Mean Absolute Error, Mean Squared Error

### Machine Learning Techniques
- **Linear Regression**: Simple linear relationship modeling
- **Multiple Regression**: Multi-feature regression analysis
- **Train-Test Splitting**: Proper model validation approach
- **Model Evaluation**: Comprehensive performance metrics

## 🔧 Troubleshooting

### Common Issues

1. **ModuleNotFoundError for plotly**
   ```bash
   pip install plotly --upgrade
   # Then restart Jupyter kernel
   ```

2. **Kernel Issues**
   - Restart the Jupyter kernel (Kernel → Restart & Clear Output)
   - Ensure you're using the correct Python environment

3. **Data File Not Found**
   - For the linear regression notebook, ensure `placement.csv` is in the correct location
   - Update the file path in the notebook if needed

## 📈 Learning Outcomes

This project demonstrates:
- **Data Science Workflow**: From data loading to model evaluation
- **Regression Analysis**: Both simple and multiple regression techniques
- **Data Visualization**: Creating meaningful plots for analysis
- **Model Validation**: Proper train-test splitting and evaluation
- **Python Programming**: Best practices for ML projects

## 🤝 Contributing

Feel free to:
- Add more regression techniques
- Improve visualizations
- Add more datasets
- Enhance documentation

## 📝 License

This project is open source and available under the MIT License.

## 📞 Support

If you encounter any issues:
1. Check the troubleshooting section above
2. Ensure all dependencies are properly installed
3. Verify you're using the correct Python environment

---

**Happy Learning! 🎓**
