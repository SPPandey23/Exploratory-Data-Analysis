<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
<body>

<h1>Exploratory Data Analysis (EDA) Repository</h1>

<div class="section">
    <p>
        This repository contains a collection of end-to-end Exploratory Data Analysis (EDA)
        and regression-based machine learning projects across multiple domains. It demonstrates
        professional workflows for data loading, cleaning, visualization, feature engineering,
        model development, and evaluation using Python and Jupyter Notebooks.
    </p>
    <p>
        The repository is designed to be scalable, reproducible, and portfolio-ready,
        aligning with modern data science and analytics best practices.
    </p>
</div>

<div class="section">
    <h2>Repository Structure</h2>
    <pre>
Exploratory-Data-Analysis/
│
├── Cars/
│   ├── Data Loading.ipynb
│   ├── Data Wrangling.ipynb
│
├── Laptop/
│   ├── Laptop Data Wrangling.ipynb
│   ├── Model Development Laptops.ipynb
│   ├── Model Evaluation Laptop.ipynb
│
├── House_sales/
│   ├── EDA and regression notebooks for King County housing data
│
├── requirements.txt
├── README.md
└── .gitignore
    </pre>
</div>

<div class="section">
    <h2>Domain Overview</h2>

    Cars
    
        Focuses on data ingestion, schema validation, handling missing values,
        data cleaning, and exploratory visualization to extract insights from
        automobile datasets.
    

    Laptop
    
        Covers a complete data science pipeline including preprocessing,
        feature scaling, regression model development (Linear and Polynomial),
        and model evaluation using R² and GridSearchCV for hyperparameter tuning.
    
    House Sales (King County, USA)
    
        Analyzes housing market data through visualization, correlation analysis,
        and predictive modeling using Linear Regression and Ridge Regression.
    
<h2>🛠️ Technology Stack</h2>
<ul>
  <li><strong>Python</strong> 3.8+</li>
  <li><strong>Data Processing:</strong> pandas, numpy</li>
  <li><strong>Visualization:</strong> matplotlib, seaborn</li>
  <li><strong>Machine Learning:</strong> scikit-learn</li>
  <li><strong>Development Environment:</strong> Jupyter Notebook</li>
</ul>

<hr />

<h2>⚙️ Installation &amp; Setup</h2>

<h3>1️⃣ Clone the Repository</h3>
<pre><code>git clone https://github.com/your-username/exploratory-data-analysis.git
cd exploratory-data-analysis</code></pre>

<h3>2️⃣ Create and Activate a Virtual Environment</h3>

<p><strong>macOS / Linux</strong></p>
<pre><code>python3 -m venv venv
source venv/bin/activate</code></pre>

<p><strong>Windows</strong></p>
<pre><code>python -m venv venv
venv\Scripts\activate</code></pre>

<h3>3️⃣ Install Dependencies</h3>
<pre><code>pip install --upgrade pip
pip install -r requirements.txt</code></pre>

<p><em>If <code>requirements.txt</code> is missing:</em></p>
<pre><code>pip freeze &gt; requirements.txt</code></pre>

<hr />

<h2>▶️ Running the Project</h2>
<pre><code>jupyter notebook</code></pre>

<p>
Navigate to any domain folder:
</p>
<ul>
  <li><code>Cars</code></li>
  <li><code>Laptop</code></li>
  <li><code>House_sales</code></li>
</ul>

<p>
Run the notebooks sequentially from top to bottom.  
Each notebook is fully self-contained.
</p>

<div class="section">
    <h2>Key Features</h2>
    <ul>
        <li>Structured exploratory data analysis workflows</li>
        <li>Data preprocessing and feature engineering</li>
        <li>Regression modeling (Linear, Polynomial, Ridge)</li>
        <li>Model evaluation and hyperparameter tuning</li>
        <li>Reproducible Python environment</li>
        <li>Well-documented Jupyter Notebooks</li>
    </ul>
</div>

<div class="section">
    <h2>Best Practices Followed</h2>
    <ul>
        <li>Modular folder-based organization</li>
        <li>Reproducible setup using virtual environments</li>
        <li>Industry-standard evaluation metrics</li>
        <li>Emphasis on interpretability and data storytelling</li>
    </ul>
</div>

<div class="section">
    <h2>Use Cases</h2>
    <ul>
        <li>Learning and practicing EDA techniques</li>
        <li>Regression modeling reference</li>
        <li>Data science portfolio projects</li>
        <li>Template for structured analytics workflows</li>
    </ul>
</div>

<div class="section">
    <h2>License</h2>
    <p>
        This project is intended for educational and demonstrative purposes.
        You are free to fork, modify, and extend it.
    </p>
</div>


</body>
</html>
