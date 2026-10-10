# Optimal Residential Energy System Sizing

This project develops and evaluates a data-driven method to size a residential **PV + battery** system for maximum economic value.

## Project Highlights
- Built a full workflow from raw time-series data to final system sizing decisions.
- Modeled:
  - PV power generation from irradiance and temperature data.
  - Battery energy storage behavior (state of charge, charge/discharge limits, efficiency).
  - Economic performance using net present value (NPV).
- Performed weather and demand interpolation to generate 1-minute full-year datasets.
- Compared candidate system sizes and selected the best configuration.

## Best Result (Group B)
- **PV capacity:** 1.059 kW  
- **Battery capacity:** 2.588 kWh  
- **NPV:** 708.62

## Repository Structure
- `/Data` – input demand, weather, and parameter files.
- `/exports` – generated full-year 1-minute demand and weather datasets.
- `weather_and_demand_interpolation.ipynb` – high-resolution data generation.
- `stage1.ipynb`, `Stage 2.ipynb` – PV, battery, and techno-economic model development.
- `data_exploration.ipynb` – exploratory analysis and validation plots.
- `/Figures` – exported visual results.

## Tools
Python, Jupyter notebooks, and scientific/data analysis workflows for energy-system modeling and optimization.
