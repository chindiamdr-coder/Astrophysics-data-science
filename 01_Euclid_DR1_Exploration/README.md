# Project 01 – Euclid DR1: Galaxy Data Exploration

## 1. Research Objective

The main objective of this project is to explore and analyse real astronomical data from the European Space Agency's Euclid mission (Data Release 1).

Using Python and statistical methods, this project investigates the observational properties of galaxies and their distribution across different photometric redshifts.

The project aims to develop practical skills in astronomical data processing, exploratory data analysis and scientific visualization.

## 2. Scientific Questions

This project addresses the following research questions:

1. How are galaxies distributed across photometric redshift?
2. What is the relationship between galaxy colours and redshift?
3. How do observed photometric properties vary across the galaxy sample?
4. What spatial patterns can be identified in the selected region of the sky?
5. Can the available catalogue measurements help identify potential low surface brightness galaxy candidates?

## 3. Dataset

**Primary dataset:** ESA Euclid Data Release 1 (DR1).

The analysis will focus on the following catalogues:

- MER: Source detection and photometric measurements.
- PHZ: Photometric redshift estimates.
- SPE: Spectroscopic information, where available.

Data access:
- [ESA Euclid Archive](https://euclid.esac.esa.int/dr/dr1/)
- [NASA/IPAC Infrared Science Archive (IRSA)](https://irsa.ipac.caltech.edu/)

## 4. Methodology

The project follows a reproducible scientific data analysis workflow:

### 4.1 Data Acquisition
- Accessing astronomical catalogues.
- Querying data using ADQL.
- Retrieving galaxy properties through Python.

### 4.2 Data Preprocessing
- Data cleaning and validation.
- Handling missing values.
- Checking data quality and selection criteria.

### 4.3 Exploratory Data Analysis
- Statistical description of galaxy populations.
- Analysis of photometric properties.
- Investigation of redshift distributions.

### 4.4 Scientific Visualization
- Redshift histograms.
- Galaxy colour distributions.
- Colour-redshift relationships.
- Spatial distribution of galaxies.

### 4.5 Further Analysis
- Investigation of morphological parameters.
- Galaxy size and surface brightness analysis.
- Exploration of potential low surface brightness galaxy candidates.

## 5. Technologies and Tools

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- SciPy
- Astropy
- Astroquery
- ADQL

## 6. Project Structure

```text
01_Euclid_DR1_Exploration/
│
├── notebooks/
│   └── 01_euclid_exploration.ipynb
│
├── data/
│
├── figures/
│
├── results.md
│
└── README.md
```

## 7. Expected Outcomes

- A reproducible workflow for accessing Euclid DR1 data.
- An exploratory analysis of a real galaxy sample.
- Statistical and graphical characterization of galaxy populations.
- Initial investigation of galaxy colours and photometric redshifts.
- A foundation for further research into low surface brightness and ultra-diffuse galaxies.

## 8. Scientific References

- European Space Agency (ESA) – Euclid Mission.
- Euclid Data Release 1 – Explanatory Supplement.
- NASA/IPAC Infrared Science Archive – Euclid Tutorials.

## 9. Project Status

**In progress.**

This project is part of a personal scientific portfolio focused on astronomical data science, galaxy evolution and computational astrophysics.

---

*Exploring galaxy populations through Python and observational data.*
