# A DIY Project
Using an AirBnB dataset for data analysis


# Airbnb Data Analysis

This repository contains Jupyter Notebooks and resources for analyzing Airbnb Open Data. The project includes steps for data cleaning, exploratory data analysis (EDA), and insights generation for Airbnb property listings.

## Project Structure

- `CSV_AirBnB_Analysis.ipynb`: Main notebook for data cleaning and initial analysis.
- (Add other notebooks as you expand: e.g., `eda.ipynb`, `modeling.ipynb`)
- (Optional) `data/`: Folder for data files (not included in repo, see Data section)
- (Optional) `requirements.txt`: Python dependencies

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Dakshina-Murthy-Student/VOIS_AICTE_Oct2025_VenkataSubrahmanyaDakshinaMurthyVemuri.git
```

### 2. Install Dependencies

Recommended to use a virtual environment.

```bash
pip install -r requirements.txt
```

**Typical dependencies:**  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- plotly

### 3. Add Data

Place the Airbnb dataset (e.g., `Airbnb_Open_Data.csv`) in the appropriate location.  
**Note:** The actual data file is not included due to size/licensing.

## Usage

Open the main notebook in Jupyter or Google Colab:

```
CSV_AirBnB_Analysis.ipynb
```

Follow the notebook to see data cleaning steps, preprocessing, and initial exploration.

## Data Dictionary

Some key columns in the Airbnb dataset:

- `id`: Listing ID
- `NAME`: Listing name/title
- `host id`: Host identifier
- `neighbourhood group`: Main area (e.g., Manhattan, Brooklyn)
- `price_$`: Price per night (USD)
- `service fee_$`: Service fee per booking (USD)
- `minimum nights`: Minimum nights required
- `last review`: Last review date
- `reviews per month`: Average reviews per month
- `availability 365`: Days available per year

## Contributing

Contributions are welcome! Suggestions for better cleaning, analysis, or new insights are appreciated.  
Please open an issue or submit a pull request.

## License

(Add a license here, e.g., MIT License.)

## Author

Dakshina Murthy Student
