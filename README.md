# Aviation Accident Analysis

This project analyzes aviation accident data from 1983 to 2023 to help identify which aircraft makes and models are the safest for insurers and stakeholders. The goal is to highlight planes with low destruction rates and low chances of serious or fatal injuries during accidents.

## What I Did

- Cleaned and organized the raw accident dataset using Pandas
- Focused only on aircraft models still possibly in use (last 40 years)
- Split the analysis between **small planes (≤ 20 passengers)** and **large planes**
- Used visualizations and summary stats to compare injury rates and aircraft damage
- Explored other factors like **weather conditions** and **flight phase** to understand their impact on safety

## Key Takeaways

- **Large planes**: McDonnell Douglas and Boeing models (like the MD-80 and 737-322) showed the lowest injury rates
- **Small planes**: Maule models (MX-7-235, M-7-235B) performed best; Boeing E75 also stood out
- Poor weather (IMC) was clearly linked to more injuries and higher destruction rates
- Accidents were most severe during **approach** ,**maneuvering** and **initial climb** phases

## Tools

- Python, Pandas, NumPy
- Seaborn, Matplotlib
- Git, GitHub

## Files

- `Aviation_Accidents_Cleaning.ipynb`: Cleaning and prepping the data
- `Aviation_Accidents_Data_Analysis.ipynb`: Exploratory analysis, visuals, and recommendations

