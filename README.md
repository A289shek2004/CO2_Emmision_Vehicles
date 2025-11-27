******📊 CO₂ Emissions by Vehicle – Data Visualization & Prediction App******


This Streamlit project analyzes and predicts CO₂ emissions from various vehicle specifications using a real-world dataset. The app provides powerful visual insights into emission trends across brands, fuel types, and engine sizes, along with an ML-based prediction model.

🚀 Features
Interactive Dashboard with visualizations such as:

Car brands and model distributions

CO₂ emissions by fuel type, transmission, engine size, cylinders, etc.

Box plots for outlier detection and removal

Outlier Handling using Z-Score to improve model performance

Predictive Modeling using Random Forest Regressor to estimate CO₂ emissions based on:

Engine Size (L)

Number of Cylinders

Fuel Consumption (L/100 km)

🗂️ Project Structure
bash
Copy
Edit
📁 CO2-Emissions-Vehicle
│
├── app.py                                 # Streamlit application script
├── co2 Emissions.csv                      # Dataset used in the project
├── co2_emission_by_vehicle_project.ipynb  # Data exploration & modeling notebook
├── README.md                              # Project documentation
└── requirements.txt                       # Required installation

📈 Sample Visuals:

Brand-wise vehicle counts

Top 25 most common models

Vehicle class vs CO₂ emissions

Fuel type distribution and impact on emissions

Transmission-based emission comparison

Before/after outlier handling visualizations

🧠 Machine Learning Model:

Model Used: RandomForestRegressor from Scikit-learn

Features Used:

Engine Size (L)

Cylinders

Fuel Consumption (L/100 km)

Target: CO2 Emissions (g/km)

Outliers are removed based on Z-score filtering with a threshold of 1.9 to ensure better model performance.

💻 How to Run
Clone the repository:

bash
Copy
Edit
git clone [https://github.com/A289shek2004/CO2_Emissions_Vehicles.git](https://github.com/A289shek2004/CO2_Emmision_Vehicles/tree/main)
cd CO2-Emissions-Vehicle


**📦 Requirements**
streamlit

pandas

numpy

matplotlib

seaborn

scikit-learn

scipy

**📚 Dataset**
The dataset co2 Emissions.csv contains vehicle data including make, model, engine size, fuel consumption, transmission type, fuel type, and CO₂ emissions.

Source: [Government Vehicle Emissions Data (Canada)]

✅ Future Improvements
Include more ML models for comparison (e.g., Linear Regression, Gradient Boosting)

Add feature for uploading custom CSVs

Improve user interface with modern UI components

Deploy the app via Streamlit Cloud: 
https://co2emmisionvehicles.streamlit.app/

**🧑‍💻 Author**
Abhishek Gupta
Aspiring Data Scientist | Data Analyst |








