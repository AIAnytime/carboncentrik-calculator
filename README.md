# Personal Carbon Calculator App 🌍

This Streamlit app allows users to estimate their carbon footprint based on key factors such as transportation, electricity consumption, diet, and waste generation. The app provides a user-friendly interface where individuals can input their daily activities, and the tool calculates the corresponding carbon emissions.

## Requirements

The following Python libraries are necessary to run this code:

- [Streamlit](https://streamlit.io/): Install it using `pip install streamlit`.

## Running the App

- To run the app, execute the following command in your terminal or command prompt:

#### streamlit run path/CO2-Emmission-Calculator/app.py [ARGUMENTS]

## Key Factors and Emission Factors

This Streamlit app allows users to estimate their carbon footprint based on key factors such as transportation, electricity consumption, diet, and waste generation. The app provides a user-friendly interface where individuals can input their daily activities, and the tool calculates the corresponding carbon emissions.

## Key Factors and Emission Factors

### Key Factors:

1. **Transportation:** Daily commute distance in kilometers.
2. **Electricity Consumption:** Monthly electricity consumption in kilowatt-hours (kWh).
3. **Diet:** Number of meals per day.
4. **Waste Generation:** Amount of waste generated per week in kilograms.

### Emission Factors:

The emission factors, representing the amount of carbon dioxide (CO2) emitted per unit of each activity, are pre-defined for different countries:

- **Transportation:** kgCO2 per kilometer (km) or mile.
- **Electricity:** kgCO2 per kilowatt-hour (kWh).
- **Diet:** kgCO2 per meal and kgCO2 per kilogram (kg) of food.
- **Waste:** kgCO2 per kilogram (kg) of waste.

## How to Use

1. Select your country from the dropdown menu.
2. Input your daily commute distance, monthly electricity consumption, waste generation, and the number of meals per day.
3. Click the "Calculate CO2 Emissions" button to see the results.

## Results

The app provides a breakdown of carbon emissions by category (transportation, electricity, diet, and waste) and displays the total carbon footprint in tonnes of CO2 per year.

## Additional Information

The app includes a warning message specific to the selected country, offering additional context or tips related to carbon emissions. Users are encouraged to interpret the results in the context of their individual activities and consider adopting more sustainable practices.
