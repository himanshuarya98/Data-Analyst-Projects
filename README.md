 # World Population Data Analysis Using Tableau

### Project Aim 
To provide a comprehensive analysis of global population trends, focusing on the most populous countries, population densities, annual changes, growth rates, and the relationship between population density and country area.

## Data Source
I have taken World Population Dataset from Kaggle that contains single text file("world_population_by_country.csv").

## Objective 

1. Identifying the Most Populous Countries in 2024
2. Assessing Population Density by Country
3. Comparing Year-on-Year Population Statistics (2023 vs. 2024)
4. Analyzing Population Growth Rates
5. Exploring the Correlation Between Population Density and Country Area
6. Visualizing the Top 5 Countries Holding the Majority of the World's Population

## Data Cleaning/Preparation

We have performed the following steps which were necessary to clean and prepare our final data:
- Data loading and inspected the data
- Ensured all the columns data type should be accurate
- Created a new calculated column (Area KM) by replacing 'M' with 1000000 & 'K' with 1000
- Changed country column data type to "Geographical Role" earlier it was in "Text/String" form to create accurate Map visualisations

## Key Insights

1. India is the most populous country with population of 1,441,719,852 followed by china which has 1,425,178,782.
2. Bangladesh has the highest population density, meaning many people live in a small area. India and Pakistan also have high population densities, which can create challenges for city planning and managing resources.
3. India shows a noticeable increase in population, while China's population has seen a slight decline. Other countries have maintained relatively stable population numbers.
4. Ethiopia and Nigeria exhibit the highest growth rates, indicating rapid population increases. Conversely, countries like Russia show a negative growth rate, suggesting a population decline.
5. Smaller countries like Bangladesh have high population densities. Larger countries like Russia have low population densities despite having large areas. There is an inverse relationship between country size and population density, with smaller countries experiencing higher densities.
6. India(18.01%) and China(17.80%) alone account for a significant portion of the world's population, highlighting their demographic dominance.

