# Rainfall Analysis and Planting Advisory

## Project Summary

This project analyses monthly rainfall data from five Kenyan counties: Nairobi, Nakuru, Kisumu, Mombasa and Machakos. Using Python and NumPy, it cleans invalid Machakos rainfall readings, calculates annual rainfall totals and monthly averages, identifies wettest months, counts dry months and determines the best consecutive two-month planting windows. The results are exported into a CSV file to support an NGO in providing practical planting advice to farmers.

## How to Run

1. Open `rainfall_analysis.ipynb` using Google Colab or Jupyter Notebook.
2. Install the required library using `pip install -r requirements.txt`.
3. Run all notebook cells from top to bottom.
4. The notebook generates `rainfall_summary.csv`.

## Planting Advisory

- Nairobi, Nakuru, Kisumu and Mombasa have April-May as their recommended planting window based on the highest combined monthly rainfall.
- Machakos has November-December as its recommended planting window, with 278 mm of combined rainfall.
- Farmers should monitor local weather forecasts and consider soil conditions and water availability because historical rainfall patterns do not guarantee future rainfall.
