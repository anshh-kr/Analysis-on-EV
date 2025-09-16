# 🚗📊 Electric Vehicle Analytics Dataset

## 📝 Description

This project provides a comprehensive analysis of an Electric Vehicle (EV) dataset. The dataset includes key attributes such as make, model, year, vehicle type, range, battery capacity, charging speed, energy consumption, and price.

The analysis explores the growth of EV adoption across regions 🌍, compares performance between manufacturers, studies battery efficiency 🔋, and provides insights into consumer choices. This dataset and analysis are valuable for sustainability research, automobile industry forecasting, market trend analysis, and policy planning for green transportation.

### Key Areas of Analysis:

  * 🚀 **Performance Analysis:** Comparing vehicle range, battery size, and efficiency across different models.
  * 💹 **Market Trends:** Tracking adoption rates, pricing trends, and regional popularity of electric vehicles.
  * 🌱 **Sustainability Studies:** Evaluating the environmental impact and energy usage of EVs.

## 💾 Dataset Information

The dataset used for this analysis is `electric_vehicle_analytics.csv`, which contains the following columns:

  * `Vehicle_ID`
  * `Make`
  * `Model`
  * `Year`
  * `Region`
  * `Vehicle_Type`
  * `Battery_Capacity_kWh`
  * `Battery_Health_%`
  * `Range_km`
  * `Charging_Power_kW`
  * `Charging_Time_hr`
  * `Charge_Cycles`
  * `Energy_Consumption_kWh_per_100km`
  * `Mileage_km`
  * `Avg_Speed_kmh`
  * `Max_Speed_kmh`
  * `Acceleration_0_100_kmh_sec`
  * `Temperature_C`
  * `Usage_Type`
  * `CO2_Saved_tons`
  * `Maintenance_Cost_USD`
  * `Insurance_Cost_USD`
  * `Electricity_Cost_USD_per_kWh`
  * `Monthly_Charging_Cost_USD`
  * `Resale_Value_USD`

## 🛠️ Libraries Used

This analysis is performed using Python and the following libraries:

  * **numpy**
  * **pandas**
  * **seaborn**
  * **matplotlib**

## 📈 Analysis and Visualisations

The Jupyter Notebook `DS_python_proj.ipynb` contains a detailed exploratory data analysis (EDA) of the dataset. Key analyses include:

  * **Energy Efficiency:** Calculation and comparison of range per kWh for different EV models.
  * **Charging Cost:** Analysis of monthly charging costs across different regions and vehicle types.
  * **Battery Health:** Correlation analysis between battery health, mileage, and charge cycles.
  * **CO2 Savings:** A look at the total CO2 savings by region and usage type.

The notebook also includes a variety of data visualisations, such as:

  * 🗺️ Distribution of EVs by region.
  * 🏆 Top EV manufacturers by vehicle count.
  * 🔋 A scatter plot of vehicle range vs. battery capacity.
  * 📉 A line chart showing CO2 savings over the years.
  * 💰 Distribution of EV resale values.
  * 🔌 A boxplot of monthly charging costs by region.

## 🚀 How to Run the Project

To run this analysis on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd <project-directory>
    ```
3.  **Install the required libraries:**
    ```bash
    pip install numpy pandas seaborn matplotlib jupyter
    ```
4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
5.  Open the `DS_python_proj.ipynb` file and run the cells.
