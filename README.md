# Żabka Store Location Analysis & Clustering

This project analyzes the location of **Żabka** stores in **Warsaw, Poland**, to identify patterns and recommend potential locations for new stores. By examining surrounding venues, calculating distances, and using clustering, the project provides insights that can help in making informed decisions for expansion.

---

## 📚 Table of Contents

1. [Overview](#overview)
2. [Features](#features)
3. [Setup](#setup)


---

## 📖 Overview

**Żabka** is a leading convenience store chain in Poland. This project uses data analysis and machine learning to:
- Analyze **Żabka** store locations
- Explore nearby venues
- Identify optimal areas for future store openings

The analysis includes clustering the stores, calculating distances to competitors, and examining neighborhood characteristics.

---

## ⚙️ Features

- **Data Cleaning & Processing**: Structures and cleans data on Żabka stores and nearby venues.
- **Venue Categorization**: Simplifies venue categories into broader groups such as:
  - Supermarkets
  - Retail
  - Restaurants
- **Clustering**: Uses **K-Means clustering** to group stores based on proximity and venue types.
- **Distance Analysis**: Measures the distance between Żabka stores and surrounding venues (e.g., supermarkets, retail stores).
- **District Identification**: Identifies the district (neighborhood) of each store based on geographic coordinates.
- **Visualization**: Provides interactive maps and visual representations of the findings.

---

## 🛠️ Setup

### Prerequisites

To get started with this project, make sure you have the following:

- **Python 3.x** (preferably 3.7 or higher)
- **Jupyter Notebook** (for running the analysis in an interactive environment)

### Step 1: Install Required Libraries

To install the necessary Python libraries, run the following command:

```bash
pip install pandas matplotlib seaborn folium geopy sklearn requests tqdm ipywidgets
