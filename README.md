# Indian Roads Accident Data Analysis

A data science project analyzing road accident patterns, safety trends, and key contributing factors using public Kaggle data. This repository contains the complete exploratory data analysis (EDA) pipeline alongside an interactive HTML dashboard.

## Project Overview

* **Data Analysis:** Performed in-depth EDA using Python (`pandas`, `matplotlib`, `seaborn`) to identify high-risk zones, temporal accident patterns, and major causal factors.
* **Interactive Summary Dashboard:** A custom-built web page presenting executive summaries, key statistical findings, and embedded graph visualizations for quick insights.
* **Open Dataset:** Based on publicly available historical traffic and road accident records.

## Tech Stack & Tools

* **Analysis:** Python, Jupyter Notebook
* **Data Handling:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Web Dashboard:** HTML5, CSS3
* **Deployment:** Vercel / GitHub Pages

## Project Structure

```text
├── index.html                  
├── style.css        
├── accidents.ipynb             
├── dataset/                    
├── images/                     
├── .ipynb_checkpoints/         
└── README.md                   
```
``

## How to Run Locally

### 1. View the Web Dashboard

Open `index.html` in any web browser to view the visual summaries and charts locally.

### 2. Run the Notebook Analysis

Clone this repository:

```bash
git clone https://github.com/rishithagoud25/Road-Accidents-Analysis.git
```

Navigate into the project directory and install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Launch the Jupyter Notebook:

```bash
jupyter notebook accidents.ipynb
```

## Live Demo

View the live dashboard hosted on Vercel:

Live website: https://road-accidents-analysis.vercel.app/

## License & Acknowledgments

* **Data Source:** Dataset sourced publicly from Kaggle.
* **License:** Open-source under the MIT License.
