
# 🚲 Bike-Share Analysis with R

This project analyzes bike-share trip data using R. The analysis includes cleaning, summarizing, and visualizing ride data to identify usage patterns by customer type and time of week.

---

## 📦 Project Contents

- `analyse_bicycle.Rmd` — Main R Markdown file containing the full analysis
- `analyse_bicycle.html` — Rendered HTML report for easy viewing
- `csv_data/` — (Empty) Folder where you should place downloaded CSV files
- `summary_df.csv` — Exported summary data frame (e.g., ride counts and durations)
- `Bike-share-Analysis.Rproj` — RStudio project file for reproducibility

---

## 📥 Download the Data

You can download the original monthly Divvy bike trip data from the official source:

🔗 [Divvy Trip Data Portal](https://divvy-tripdata.s3.amazonaws.com/index.html)

After downloading, place the `.csv` files into the `data/` folder inside this project directory.
> 🧪 The results in the project are for the time period April 2024 to May 2025.

---

## 📊 Features

- Import and combine multiple monthly trip CSV files
- Clean and filter invalid records
- Calculate ride durations and flag anomalies
- Summarize usage by member type and day of week
- Visualize trends using `ggplot2`
- Export final summary as CSV

---

## 🛠️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/RebinRaj/bike-share-analysis.git
   cd bike-share-analysis
   ```

2. Open `Bike-share-Analysis.Rproj` in **RStudio**

3. Knit `analyse_bicycle.Rmd` to HTML or view results inline

   > 🧪 Make sure required packages like `dplyr`, `ggplot2`, `lubridate`, and `readr` are installed. 

---

## 📬 Contact

📧 [rebinraj.k@gmail.com](mailto:rebinraj.k@gmail.com)  
🔗 GitHub: [github.com/RebinRaj](https://github.com/RebinRaj)

---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
