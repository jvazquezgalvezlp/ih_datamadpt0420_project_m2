# ih_datamadpt0420_project_m2
## Module 2 Project: Exploratory Data Visualization

This project deals with a txt (csv) file with specific documentation about diamonds that make its price vary.

It includes:

Summary statistics including descriptive statistics (max, min, mean, standard deviation, percentiles, correlations, etc.) and data types (integer, float, boolean, string, etc.).

Data visualizations charts in order to capture a large amount of data all at once in a clear and concise manner (Box Plots, Histograms, Bar Plots, Scatter Plots, Correlation Matrix, etc.).

Let´s explain what each column means:

- carat: The unit of measurement for the physical weight of diamonds. One carat equals 0.200 grams.
- cut: The way it has been shaped and how it reflects light because of that. I´ve changed the original measure to a numerical 
        metric ranging from 1 to 5, where 5 is Ideal and 1 is Fair. ("Ideal": "5", "Premium": "4", "Very Good": "3", "Good": "2", "Fair": "1")
- color: It measures how colorless a diamond is. For a better understand, I´ve changed the original measure to a numerical 
        metric from 1 to 7, where 7 is the whitest and 1 the yellowest. ("J": "7", "H": "5", "G": "4", "D": "1", "F": "3", "E": "2", "I": "6")
- clarity: Refers to the Absence of Inclusions and Blemishes. I´ve grouped it´s categories and then made a different way to measure them based on a number
        from 1 to 5, where 5 is perfect and 1 imperfect ("IF": "5", "VVS1": "4", "VVS2": "4", "VS1": "3", "VS2": "3", "SI1": "2", "SI2": "2", "I1": "1")
- depth: Refers to its measurement from top to bottom
- table: The flat facet on its surface 
- price: self explanatory
- x: dimension measurement
- y: dimension measurement
- z: dimension measurement
- volume: This column has been added. It takes all 3 dimension and multiplies them. Wrongly assuming that all diamonds are cubes.


In the data_analysis report you will see how basic conclusions are drawn based on their correlations and some self explanatory graphs.
If you are reading this, you may use this jupyter to draw your own conclusions about diamonds and their prices.