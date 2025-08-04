# ✈️ Flight Data Analysis

This repository contains a comprehensive analysis and visualization of airline flight data from the United States in 2015. The project aims to uncover patterns in flight delays, cancellations, airline efficiencies, seasonal effects, airport traffic, and more.

## 📊 Objective

- Analyze airline performance by examining various metrics including flight delays, distances, arrivals, and cancellations.
- Understand the impact of factors such as seasonality, airline operations, and airport hubs on flight reliability and efficiency.
- Present insights through clear, compelling visualizations for improved decision-making and travel planning.

## 📂 Project Structure

- **airlineproject.py**: Main analysis and visualization script, including all preprocessing, transformations, and plots.
- **flight_data_analysis.pptx**: Slide deck summarizing objectives, methodology, insights, and conclusions.
- **airlines.csv, airports.csv, flightsnew.csv**: Required datasets (ensure these are added/local if not present).
- **README.md**: Project overview, setup, results, and contribution guidelines.

## 🔍 Key Features

- Data preprocessing and cleansing for accurate analysis.
- Multiple levels of feature engineering (date handling, code normalization).
- Visualization of:
    - Departure/arrival delays, average by airline and month
    - Cancellation rates for each airline
    - Busiest origin and destination airports
    - Flight volume trends by season/month
    - Distance vs. air time relationship
    - Longest flights, on-time performance, and more
    - Geographic flight paths (Plotly/Geo visualizations)
    - Top routes and Sankey flow for origin-destination pairs
- Actionable summary in PowerPoint for easy sharing

## 📦 Installation & Usage

1. **Clone the repository**
    ```
    git clone https://github.com/yourusername/flight-data-analysis.git
    cd flight-data-analysis
    ```

2. **Install dependencies**
    ```
    pip install pandas numpy matplotlib seaborn
    pip install notebook
    ```

3. **Add datasets**
    - Place `airlines.csv`, `airports.csv`, and `flightsnew.csv` in the project root.

4. **Run the analysis**
    ```
    python airlineproject.py
    ```

5. **Convert script to Jupyter Notebook (optional)**
    ```
    jupyter nbconvert --to notebook --execute airlineproject.py --output airlineproject.ipynb
    ```

6. **View Presentation**
    - Open `flight_data_analysis.pptx` for core insights and visual storytelling.

## 📈 Insights

- Spirit Air Lines had the highest cancellation and departure delay rates, while Hawaiian Airlines was the most reliable for both on-time and limited cancellations.
- Summer months and December saw increased delays (holiday and weather effects).
- Hartsfield-Jackson Atlanta is the busiest airport both in departures and arrivals.
- The number and pattern of flights display clear seasonality and hub-and-spoke airline models.
- Longer flights are concentrated among a few airlines; delay correlations and causality are explored.
- Detailed visualizations (bar, line, pie charts, scatterplots, Sankey, and geoplots) support all insights.

## ✅ Results & Conclusion

Our study reveals that US airline performance is shaped by operational strategy, seasonality, and the airport network's underlying structure. Proactive management of peak-season operations and targeted improvements in high-delay airlines can meaningfully improve system reliability for travelers. See the `flight_data_analysis.pptx` for additional details and recommendations.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to open an issue or pull request to discuss new visualizations, datasets, or analytic questions.

---

## 👤 Authors

- Gaurav Khanolkar
- Mayur Patil

---

## 💡 Questions?

Open an issue in this repository or contact the authors via LinkedIn/email.
