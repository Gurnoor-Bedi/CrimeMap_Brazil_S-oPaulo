# CrimeMap_Brazil_S-oPaulo
# São Paulo Crime Data Visualization

This project focuses on analyzing and visualizing crime data in São Paulo, Brazil. The goal is to clean the data and create interactive Choropleth maps to visualize crime occurrences and losses in different areas over time.

## Project Goal

- Clean and analyze crime data from São Paulo.
- Visualize the data using interactive maps, showing crime occurrences and financial losses.

## Problem Statement

The dataset contains detailed information about crime incidents in São Paulo, including the victim's perspective and the objects lost. The task involves cleaning the data and visualizing it using Choropleth maps to represent crimes in various neighborhoods over different dates.

## Dataset Description

The dataset includes the following columns:

- `id`: Unique ID for each occurrence.
- `bairro`: São Paulo neighborhood.
- `created_at`: Date of report creation.
- Other columns include detailed information about the incident and the items stolen.

## Activities

### Activity 1: Import Modules and Read Data

- Import necessary Python modules: `pandas`, `numpy`.
- Read the data into a Pandas DataFrame and perform initial data exploration.

### Activity 2: Data Cleaning

- Create a new DataFrame with selected columns.
- Handle missing values and clean the data for analysis.

### Activity 3: Visualizing Crime Rates and Losses

- Convert the `time` column to datetime and extract the year.
- Visualize the Brazilian Real (BRL) loss and the total number of items stolen in different locations using `plotly`'s `density_mapbox`.

## Tools and Libraries Used

- Python
- Pandas
- Numpy
- Plotly

## Visualization

The project uses `plotly.express` to create interactive density maps that show the concentration of crimes, financial losses, and the number of items stolen in different neighborhoods of São Paulo. The maps are animated over the years to show trends over time.

## How to Run the Project

1. Ensure you have Python installed along with the required libraries.
2. Clone the repository or download the source code.
3. Run the script to perform data analysis and visualization.

## Contributing

Feel free to fork the repository, make improvements or add new features, and submit pull requests.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

This README provides an overview of your project, outlining its objectives, dataset description, activities involved, and instructions on how to run and contribute to the project. You can adjust it according to the specifics of your project and additional features or instructions.
