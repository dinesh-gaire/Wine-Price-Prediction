# 🍷 Wine Quality Prediction: End-to-End Machine Learning Project

## 🌟 Project Overview

Unlock the science behind wine quality with our advanced machine learning pipeline! This project leverages cutting-edge data science techniques to predict wine quality based on intricate physicochemical properties.

## ✨ Key Features

- 🔬 Complete end-to-end machine learning workflow
- 📊 Advanced data preprocessing and validation
- 🤖 ElasticNet regression for precise predictions
- 🌐 Interactive Flask web application
- 📈 Comprehensive model evaluation

## 🛠 Technology Stack

- **Machine Learning**: Scikit-learn
- **Model**: ElasticNet Regression
- **Web Framework**: Flask
- **Data Handling**: Pandas
- **Language**: Python 3.x

## 🚀 Quick Start Guide

### Prerequisites

Before you begin, ensure you have:
- Python 3.x
- pip (Python package manager)

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/dinesh-gaire/Wine-Quality-Prediction-End-to-end-ML-Project.git
   cd Wine-Quality-Prediction-End-to-end-ML-Project
   ```

2. **Create Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   # For Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Project**
   Update configuration files:
   - `config/config.yaml`: Project settings
   - `config/params.yaml`: Model hyperparameters
   - `config/schema.yaml`: Dataset schema

## 🔍 Project Workflow

### Data Science Pipeline

1. 📥 **Data Ingestion**
   - Load raw wine quality data
   - Validate dataset integrity

2. 🧹 **Data Transformation**
   - Feature scaling
   - Encoding categorical variables
   - Prepare data for model training

3. 🏋️ **Model Training**
   - ElasticNet regression
   - Hyperparameter tuning
   - Model serialization

4. 📊 **Model Evaluation**
   - Calculate performance metrics
   - Generate comprehensive reports

5. 🌐 **Web Prediction**
   - Flask-based prediction interface
   - Real-time wine quality estimation

## 💻 Running the Project

### Train the Model
```bash
python main.py
```

### Start Web Application
```bash
python app.py
```

### Web Application Routes
- `/`: Input wine features
- `/train`: Initiate model training
- `/predict`: Get wine quality prediction

## 📊 Model Performance Metrics

Our ElasticNet model is evaluated using:
- **RMSE**: Root Mean Squared Error
- **MAE**: Mean Absolute Error
- **R²**: Model explanatory power

Metrics are automatically saved in `artifacts/model_evaluation/`

## 🧪 ElasticNet Model Details

### Hyperparameters
- **Alpha**: Regularization strength
- **L1 Ratio**: Lasso and Ridge regularization balance

Configured in `config/params.yaml`

## 🤝 Contribution Guidelines

1. Fork the repository
2. Create a feature branch
3. Implement your changes
4. Write comprehensive tests
5. Submit a pull request

### Code of Conduct
- Follow PEP 8 style guidelines
- Include documentation
- Maintain code quality

## 📄 License

MIT License - See `LICENSE` file for details

## 🌈 Future Roadmap
- Implement advanced feature engineering
- Explore ensemble modeling techniques
- Enhance web interface
- Add more comprehensive visualizations

## 🙏 Acknowledgements

Special thanks to the open-source libraries that made this project possible:
- Scikit-learn
- Flask
- Pandas
- Joblib
- Matplotlib/Seaborn

---

**Disclaimer**: This is a data science project and should not replace professional wine quality assessments.

## 📞 Support

Encountered an issue? [Open an Issue](https://github.com/dinesh-gaire/Wine-Quality-Prediction-End-to-end-ML-Project/issues)
