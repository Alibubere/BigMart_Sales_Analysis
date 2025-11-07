# BigMart Sales Analysis 📊

![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=flat&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=flat&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/seaborn-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)
![Contributions](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)
![Issues](https://img.shields.io/github/issues/yourusername/BigMart_Sales_Analysis)
![Forks](https://img.shields.io/github/forks/yourusername/BigMart_Sales_Analysis)
![Stars](https://img.shields.io/github/stars/yourusername/BigMart_Sales_Analysis)

A comprehensive data analysis project exploring BigMart sales data to uncover insights about product performance, outlet characteristics, and sales patterns.

## 📋 Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Highlights](#analysis-highlights)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## 🎯 Overview

This project analyzes BigMart sales data to understand factors affecting product sales across different outlets. The analysis includes data exploration, visualization, and insights generation to help understand sales patterns and outlet performance.

## 📊 Dataset

The dataset contains sales data for 1559 products across 10 stores in different cities. The data includes:

- **8,523 records** with 12 features
- Product attributes (weight, fat content, visibility, type, MRP)
- Outlet characteristics (size, location type, establishment year, type)
- Target variable: Item_Outlet_Sales

### Key Features:
- `Item_Identifier`: Unique product ID
- `Item_Weight`: Weight of product
- `Item_Fat_Content`: Fat content category
- `Item_Visibility`: Product visibility in store
- `Item_Type`: Product category
- `Item_MRP`: Maximum Retail Price
- `Outlet_Identifier`: Unique store ID
- `Outlet_Establishment_Year`: Store establishment year
- `Outlet_Size`: Store size category
- `Outlet_Location_Type`: Store location tier
- `Outlet_Type`: Store type
- `Item_Outlet_Sales`: Sales amount (target variable)

## ✨ Features

- 📈 **Exploratory Data Analysis**: Comprehensive data exploration and statistical analysis
- 🔍 **Data Quality Assessment**: Missing value analysis and data cleaning
- 📊 **Visualization**: Interactive plots and charts using matplotlib and seaborn
- 🎯 **Sales Insights**: Product and outlet performance analysis
- 📋 **Statistical Summary**: Descriptive statistics and correlation analysis

## 🚀 Installation

1. **Clone the repository**
```bash
git clone https://github.com/Alibubere/BigMart_Sales_Analysis.git
cd BigMart_Sales_Analysis
```

2. **Install required packages**
```bash
pip install pandas numpy seaborn matplotlib jupyter
```

3. **Launch Jupyter Notebook**
```bash
jupyter notebook BigMart_Sales_Analysis.ipynb
```

## 💻 Usage

1. Open the Jupyter notebook `BigMart_Sales_Analysis.ipynb`
2. Run cells sequentially to perform the analysis
3. Explore the visualizations and insights generated
4. Modify parameters or add new analysis as needed

## 🔍 Analysis Highlights

- **Data Quality**: Identified missing values in Item_Weight (1,463 missing) and Outlet_Size (2,410 missing)
- **Dataset Size**: 8,523 records across 12 features
- **Product Categories**: Multiple item types including Dairy, Soft Drinks, Meat, Fruits & Vegetables, Household items
- **Outlet Types**: Supermarket Type1, Type2, Type3, and Grocery Stores
- **Location Tiers**: Tier 1, 2, and 3 locations analyzed

## 🛠️ Technologies Used

- **Python 3.8+**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib**: Static plotting and visualization
- **Seaborn**: Statistical data visualization
- **Jupyter Notebook**: Interactive development environment

## 📁 Project Structure

```
BigMart_Sales_Analysis/
│
├── README.md                      # Project documentation
├── BigMart_Sales_Analysis.ipynb   # Main analysis notebook
├── Big_Mart_Sales.csv            # Dataset
└── .gitignore                    # Git ignore file
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Mohammad Ali Bubere**
- 📧 Email: alibubere989@gmail
- 🐙 GitHub: [Ali Bubere](https://github.com/Alibubere)
- 💼 LinkedIn: [Mohammad Ali Bubere](https://www.linkedin.com/in/mohammad-ali-bubere-a6b830384/)


---

⭐ **If you found this project helpful, please give it a star!** ⭐

![Footer](https://img.shields.io/badge/Made%20with-❤️-red.svg)
![Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)