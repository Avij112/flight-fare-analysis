flight-fare-analysis
A multi-year analysis of domestic airfare trends in India (2016–2024), comparing pricing patterns across major airlines, routes, and directions. This project includes data cleaning, fare interpolation, and route-wise airline comparisons.

📌 Project Overview
This repository explores how domestic flight fares in India evolved between 2016 and 2024. Since granular fare data was only available for 2022 and 2023, data for the remaining years was interpolated using IATA's real average airfare index (2011=100). The project focuses on major airlines and metro routes, offering a data-driven look into how pricing trends varied across time, direction, and competition.

🛫 Airlines Covered
IndiGo

Air India

Vistara

SpiceJet

AirAsia India

Akasa Air
(Airline presence adjusted based on operational years)

📍 Routes Analyzed
Delhi ↔ Mumbai

Delhi ↔ Bangalore

Delhi ↔ Hyderabad

Mumbai ↔ Bangalore

Mumbai ↔ Hyderabad

Bangalore ↔ Hyderabad

Each route is split into two directions to account for price asymmetry.

📊 What This Project Includes
✅ Cleaned and aggregated fare data for 2022 & 2023

🔁 Interpolated fares for 2016–2021 & 2024 using IATA’s airfare trend index

📈 Airline-wise and route-wise fare comparisons

🔄 Directional asymmetries (e.g., Delhi → Mumbai vs Mumbai → Delhi)

📉 Year-over-year price fluctuations

📊 Pivot table-ready output for further analysis

| File / Folder             | Description                                                               |
| ------------------------- | ------------------------------------------------------------------------- |
| `complete_fare_data.xls`  | Final output: complete dataset (2016–2024) with real + interpolated fares |
| `full_fare.csv`           | Cleaned and averaged fares from 2022 and 2023 (base dataset)              |
| `flights.ipynb`           | Notebook for cleaning, filtering, and aggregating raw fare data           |
| `interpolated_data.ipynb` | Notebook for generating interpolated prices using IATA index              |
| `datasets.zip`            | Raw data sources used in the project (2022 & 2023 scraped fares)          |

Tools Used
Python (Pandas, NumPy, Matplotlib)

Jupyter Notebooks

Google Sheets (Pivot Table exploration)

IATA fare indices for interpolation reference

Future Scope
This repository sets the groundwork for more advanced analysis, including:

✳️ Time series modeling

🤖 Machine learning-based fare prediction

📉 Seasonal pricing trends
