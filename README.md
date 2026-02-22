☀️ Solar Plant Analyzer

Solar Power Site Selection & Performance Analysis using NASA POWER Data

📌 Project Overview

The Solar Plant Analyzer is a Python-based analytical and machine learning tool designed to evaluate solar photovoltaic (PV) plant feasibility using NASA POWER daily solar irradiance datasets.

It computes solar potential, energy yield, land requirements, and capacity factor, ranks candidate sites, and applies machine learning models to predict solar irradiance for new locations.

This project is suitable for renewable energy planning, smart infrastructure development, and AI-driven environmental analysis.

🚀 Key Features

📊 Automated parsing of NASA POWER daily CSV datasets

🌍 Location-wise solar irradiance analysis (Latitude & Longitude based)

⚡ Energy yield estimation using 320W solar panels (23% efficiency)

🧮 Capacity factor & land requirement calculation

🏆 Multi-criteria site ranking using a composite solar score

🤖 Machine Learning–based irradiance prediction (Random Forest & Linear Regression)

📈 Advanced data visualizations (heatmaps, distributions, comparisons)

📄 Automated CSV report generation

🛠️ Tech Stack

Programming Language: Python

Libraries Used:

1. pandas, numpy – Data processing

2. matplotlib, seaborn – Visualization

3. scikit-learn – Machine Learning

4. scipy – Interpolation & numerical utilities

📂 Dataset

Source: NASA POWER (Prediction Of Worldwide Energy Resources)

Data Type: Daily solar irradiance

Key Parameter Used:

ALLSKY_SFC_SW_DWN – All-sky surface shortwave downward irradiance (MJ/m²/day)

⚙️ Solar Panel Specifications Used
Parameter	Value
Panel Rating	320 W
Panel Efficiency	23%
Panel Area	2.0 m²
Land per Panel (with spacing)	4 m²
📐 Methodology
1. Data Cleaning & Preprocessing

Removal of missing values (-999)

Conversion of DOY to actual calendar dates

2. Site-Level Metrics Calculation

Average, peak, minimum, and variability of irradiance

Conversion from MJ/m²/day → kWh/m²/day

3. Solar Potential Estimation

Daily & annual energy output per panel

Panels required for 1 MW nameplate capacity

Land requirement estimation (hectares)

Capacity factor calculation

4. Site Ranking

Composite solar score based on:

Average irradiance

Capacity factor

Peak irradiance

Irradiance stability

5. Machine Learning Prediction

Predict solar irradiance using Latitude & Longitude

Models supported:

Random Forest Regressor

Linear Regression

📊 Visualizations Included

1.Geographic irradiance distribution

2.Top-ranked solar sites

3.Capacity factor histogram

4.Solar output vs latitude

5.Land requirement vs irradiance

6.Daily energy yield per MW comparison
