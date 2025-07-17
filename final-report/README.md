 📊 Data Analysis of Rape Cases in India (2020–2022)

This project analyzes rape cases reported in India between 2020 and 2022. Using data from the "National Crime Records Bureau (NCRB)" and population data from the 2011 Census, it calculates the rate of rape cases per 1,00,000 women for each state and union territory. The goal is to provide a clearer, normalized view of the data to understand regional variations more accurately.

🔍 Objective

To perform a statistical and visual analysis of rape case data across Indian states and UTs, identify high-risk regions, and normalize results using population data to compute "rape cases per lakh women".


 🧰 Tools & Technologies Used

- 🐍 Python
- 📊 Pandas, NumPy
- 📉 Matplotlib, Seaborn
- 📓 Jupyter Notebook
- 📄 NCRB Crime Data (2020–2022)
- 👩 Census 2011 Female Population Data



🛠️ Project Workflow: Step-by-Step

 1. 📥 Data Collection
- Downloaded rape case data for 2020, 2021, and 2022 from NCRB.
- Collected state-wise female population data from the 2011 Census of India.

2. 🧹 Data Cleaning & Preparation
- Loaded datasets into Pandas DataFrames.
- Cleaned and standardized:
  - Column names
  - State/UT names
  - Handled missing/null values
- Merged annual rape case data into a single dataset.
- Joined with population data using state names.

3. ➕ Feature Engineering
- Calculated total rape cases (2020–2022) per state.
- Computed **rape cases per lakh women** using the formula:


4. 📊 Data Visualization
- Created:
- Bar plots of top/bottom 10 states by rape rate
- Heatmaps of state-wise distribution
- Trend lines over time (if needed)

5. 📈 Analysis & Insights
- Identified states with:
- Highest rape rates (e.g., Rajasthan, Sikkim)
- Lowest rape rates (e.g., Gujarat, Tamil Nadu)
- Discussed potential reasons and limitations.
- Provided interpretation and context using markdown.
 6. 📁 Finalization & Documentation
- Structured project into folders:
- `notebooks/` for Jupyter Notebook
- `data/` for raw and cleaned datasets
- Added clear markdown comments and visuals in the notebook
- Wrote this `README.md` file with full project details
7. 🚀 Future Improvements
- Add 2023 crime data when available
- Use projected female population post-2011
- Explore district-level data (if accessible)
- Deploy as an interactive dashboard (e.g., Streamlit)

 📁 Project Structure
 ├── 📁 data/
│ ├── ncrb_2020.csv
│ ├── ncrb_2021.csv
│ ├── ncrb_2022.csv
│ └── census_2011_female_population.csv
├── 📁 notebooks/
│ └── analysis.ipynb
├── 📁 images/
│ └── barplot_top10.png
│ └── heatmap_states.png
├── README.md
└── requirements.txt


## 📌 Key Findings

- Rajasthan, Sikkim, and Haryana showed the highest rape case rates per lakh women.
- Gujarat, Tamil Nadu, and West Bengal had the lowest reported rates.
- Population normalization provided more meaningful comparison than raw case counts.

---

## 🔗 Links

- 📚 [NCRB Crime Data](https://ncrb.gov.in/en/crime-india)
- 📊 [Census 2011 Population Data](https://censusindia.gov.in/)
- 💻 [Project Notebook (Jupyter)](notebooks/analysis.ipynb)

🤝 Acknowledgements

Special thanks to my internship mentors and peers who guided me during this project. This analysis was completed as part of my "final internship project".


📬 Contact

If you'd like to discuss the project or suggest improvements, feel free to connect:

- 📧 Email: your.email@example.com  
- 🔗 LinkedIn: https://www.linkedin.com/in/sabiha-sumbul-khan-31887326a/
- 🐙 GitHub: https://github.com/Sasa-ctrl/dataintern/new/main/final-report

⭐ Show Your 

If you found this project insightful, please ⭐ star the repo and share your feedback!



