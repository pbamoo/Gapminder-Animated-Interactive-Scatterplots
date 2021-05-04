# Week 1/12 The Gapminder Project
   
### Background problem / Goal:
The challenge of this project was to analyze and visualize statistics from the [Gapminder datasets](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/tree/main/Week1_Visual_Data_Analysis/Data) and create an animated scatterplot like the one by [Hans Rosling](https://www.youtube.com/watch?v=jbkSRLYSojo) to illustrate the correlation between life expectancy and fertility of the world’s countries over time.
![Gapminder](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/blob/main/Week1_Visual_Data_Analysis/Images/Gapminder.gif)

### Tools/Libraries Used: 
Python, Pandas, Matplotlib, Seaborn, Imageio, Plotly 

### Workflow:
1. Data Acquisition: 
The [datasets(3)](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/tree/main/Week1_Visual_Data_Analysis/Data) were obtained from http://www.gapminder.org/data website. 
   * Metrics Considered
      - Life expectancy : defined as the average number of years a person is expected to live in given a certain social context. 
      - Fertility rate : defined as the average number of children per woman.
      - Total population : defined as the total number of people in a region at a given time.

2. Preprocessing:
In order to understand and prepare the data for analysis, some data inspection and preprocessing was done which can be found [here](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/blob/main/Week1_Visual_Data_Analysis/Code/1_utils.ipynb) and eventually written into [functions](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/blob/main/Week1_Visual_Data_Analysis/Code/utils.ipynb) for easabiliy in coding and scripting.

3. Exploratory Data Analysis(EDA):
A glimpse of data and its context, as well as insights captured using descriptive statistics and visualization techniques can be found [here.](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/blob/main/Week1_Visual_Data_Analysis/Code/3_EDA.ipynb)

4. [Result & Outlook:]
![Animated Scatter Plot](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/blob/main/Week1_Visual_Data_Analysis/Images/4_EDA_px3.gif)

   * The main goal for the project, which was to reproduce the Hans Rosling animation scatterplot was [achieved.](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/tree/main/Week1_Visual_Data_Analysis/Images) 
   * From the [EDA](https://github.com/pbamoo/Data-Science-Bootcamp-Projects/blob/main/Week1_Visual_Data_Analysis/Code/3_EDA.ipynb), the population and life_expectancy shows an incremental trend while fertility rate is on the decline generally. Also, life expectancy seems to show a strong negative correlation to fertility rate with the rest metrics showing very weak to almost no correlation at all to each other.
   * This trend indicates that a person with a longer life expectancy tends to have a smaller number of children, might be explained by the school of thought that such persons are able to give a greater importance to their own integral self-care, and thus get more personal time to carry out projects that are very important for them, in other words, he/she gives greater importance to their own quality of life, since having a children represents a significant cost.(http://vox.lacea.org/?q=blog/life_expectancy_fertility)
   * However, this explanation may not paint the complete picture since other factors might be at play, therefore, bigger (and more difficult) datasets with additional metrics like GDP Per Capita, Literacy Rate, Employment Rate, Child MortalityRegions, etc. needs to be incorporated into the data analysis project to get more insights to this question and to other important ones like:
      - Which region of the world has been changing relatively quickly compared to others in terms of GDP, life expectancy, and other indices?
      - How have income, population, child mortality, and children born per woman decide the life expectancy of a certain country?
