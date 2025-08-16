EcoRoute Optimize
EcoRoute Optimize is an end-to-end system designed to track, calculate, and optimize the carbon footprint of transportation logistics, particularly focusing on taxi trip data. It processes raw trip data, calculates CO2 emissions using different methods, generates summary reports, and provides route optimization capabilities to minimize environmental impact.

Features
Data Download & Processing: Handles downloading and processing of public datasets like NYC and Chicago taxi data.
Emission Calculation: Calculates CO2 emissions using both tonne-kilometer and fuel consumption estimation methods.
Comprehensive Reporting: Generates a detailed summary report including total emissions, distance, weight, and a breakdown by transport mode and distance ranges.
Route Optimization: Implements Vehicle Routing Problem (VRP) algorithms (using ortools if available, with fallbacks to clustering and nearest neighbor) to find optimized routes that minimize distance and potential CO2 emissions.
Modular Design: Code is organized into functions for data handling, calculations, optimization, and reporting
