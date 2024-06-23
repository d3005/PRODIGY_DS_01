# PRODIGY_DS_01
Here's the task-01:
Create a bar chart or histogram to visualize the distribution of a categorical or continuous variable, such as the distribution of ages or genders in a population.
Let me provide a brief description of the code shared:
1. **Data Loading:**
   - The code starts by loading a dataset from an Excel file located at `"C:\Users\DANIEL\Downloads\Population_1.xlsx"`.
   - The dataset likely contains information related to population data for different countries.
2. **Visualization:**
   - The goal of this code is to create a horizontal bar chart (barh plot) to visualize the distribution of population across various countries.
   - The x-axis represents the population, and the y-axis represents the country names.
   - The `plt.barh(df['Country'], df['Population in 2020'])` line creates the horizontal bars, where `df['Country']` provides the country names, and `df['Population in 2020']` provides the corresponding population values.
   - The `plt.xlabel('Distribution of population')` and `plt.ylabel('Country')` lines set the labels for the x-axis and y-axis, respectively.
   - The `plt.title('Population of Countries')` line sets the title of the plot.
   - Finally, `plt.show()` displays the plot.
