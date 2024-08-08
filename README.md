# Simple Data Dashboard

This is a simple data dashboard built using Streamlit. It allows users to upload a CSV file, preview the data, filter it, and generate plots based on the filtered data. This app is perfect for quick data exploration and visualization.

## Features

- **Upload CSV Files**: Users can upload CSV files using the file uploader.
- **Data Preview**: Displays a preview of the first few rows of the uploaded data.
- **Data Summary**: Provides a statistical summary of the numerical columns in the data.
- **Filter Data**: Allows users to filter the data based on a selected column and its unique values.
- **Plot Data**: Users can generate a line chart based on the filtered data.

## How to Use

1. **Upload a CSV File**:
   - Click the "Choose a CSV file" button and select a CSV file from your local machine.
   - The app will automatically load and display the data.

2. **Data Preview**:
   - After uploading, the first five rows of the data will be displayed under the "Data Preview" section.

3. **Data Summary**:
   - A statistical summary of the data, including measures like mean, standard deviation, min, and max, will be shown under the "Data Summary" section.

4. **Filter Data**:
   - You can filter the data by selecting a specific column and value. This will display only the rows where the selected column matches the chosen value.
   - To filter:
     - Choose the column you want to filter by from the first dropdown menu.
     - Select the value to filter on from the second dropdown menu.

5. **Plot Data**:
   - You can generate a line plot based on the filtered data.
   - To create a plot:
     - Select the column for the x-axis from the first dropdown menu.
     - Select the column for the y-axis from the second dropdown menu.
     - Click the "Generate Plot" button to display the plot.
   - The plot will display below the button.

## Prerequisites

- Python 3.x
- The following Python libraries must be installed:
  - `streamlit`
  - `pandas`
  - `matplotlib`