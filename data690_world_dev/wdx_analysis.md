# Does Knowledge Affect Quality of Life?
- Dave Sadovy
- 10/30/2022


## Motivation
Many people believe in knowledge for its own sake.  That is, there is value in learning about the world around us, even if the knowledge gained does not produce any practical results.  Knowledge is not simply a means to an end - it is an end in itself!  Those who embrace this philosophy are often life-long learners.  Pursuing education provides them with both enjoyment and a sense of fulfillment.  But beyond personal satisfaction, does knowledge impact quality of life?

This study will examine possible relationships between knowledge and quality of life.  Specifically, we will try to determine if knowledge is associated with either health or wealth.  The results may inform strategies for improving quality of life.  Knowledge will be approximated by the average years of total schooling a person has attained by age 64.  Quality of life will be represented by two factors.  Life expectancy will serve as a proxy for health, while GPD per capita will stand in for wealth.    

## Data Source and Selected Indicators
The source of the data and accompanying graphs is [The World Development Explorer](https://www.worlddev.xyz).  

Definitions of the indicators used for this study:
1.  **Barro-Lee: Average years of total schooling, age 60-64, total.**  Average years of total schooling, 60-64, total is the average years of education completed among people age 60-64.  
2.  **Life expectancy at birth, total (years).**  Life expectancy at birth indicates the number of years a newborn infant would live if prevailing patterns of mortality at the time of its birth were to stay the same throughout its life.
3.  **GDP per capita, PPP (current international $).**  This indicator provides per capita values for gross domestic product (GDP) expressed in current international dollars converted by purchasing power parity (PPP) conversion factor.   GDP is the sum of gross value added by all resident producers in the country plus any product taxes and minus any subsidies not included in the value of the products. conversion factor is a spatial price deflator and currency converter that controls for price level differences between countries. Total population is a mid-year population based on the de facto definition of population, which counts all residents regardless of legal status or citizenship.

Since the more prosperous countries of the world have the luxury to apply more resources towards the pursuit of knowledge, this study will look specifically at the the G7 nations: Canada, France, Germany, Italy, Japan, the United Kingdom, and the United States.  (Note: An initial examination was done of the G8, which includes Russia along with the G7.  However, Russia proved to be an outlier in several important metrics, so they have been excluded from this investigation.)  This selection of nations has the additional advantage of representing three of the world's seven regions: East Asia & Pacific, Europe & Central Asia, and North America.  Data for the selected indicators for the G7 is available for the period from 1990 to 2010, so the research will be limited to those years.

## Indicators by G7 Nation in 2010
### Average Years of Schooling
![](charts/school_G7_2010_bar.png)
The data ranges from a low of 9.11 years of schooling in Italy to a high of 13.53 years in the United States, with an average of 11.4.  

### Life Expectancy
![](charts/life_expectancy_G7_2010_bar.png)
Life Expectancies range from a low of 78.54 years in the United States to a high of 82.84 years in Japan.  The average across the G7 is 80.96 years.

### GDP Per Capita
![](charts/GDP_per_capita_G7_2010_bar.png)
Italy has the lowest GPD per capita at $35,158, while the United States has the highest at $48,650.  The average is $38,668.

Year	Country Name	Region	Average Years of Total Schooling	GDP Per Capita	Life Expectancy
2010	Canada	North America	12.43	40099.44824	81.24634146
2010	Germany	Europe & Central Asia	12.2	38952.6946	79.98780488
2010	France	Europe & Central Asia	10.01	35902.90311	81.66341463
2010	United Kingdom	Europe & Central Asia	11.3	36576.58654	80.40243902
2010	Italy	Europe & Central Asia	9.11	35158.44184	82.03658537
2010	Japan	East Asia & Pacific	11.22	35335.37351	82.84268293
2010	United States	North America	13.53	48650.64313	78.54146341
			11.4	38668.013	80.96010453
![image](https://user-images.githubusercontent.com/112588261/198912332-f464f164-b4e9-433b-bd2f-304717f1640f.png)


![](charts/school_G7_line.png)

![](charts/life_expectancy_G7_line.png)

![](charts/GPD_per_capita_G7_line.png)

![](charts/school_v_le_scatter.png)

![](charts/school_v_le_regress.png)

![](charts/school_v_gdp_scatter.png)

![](charts/school_v_gdp_regress.png)
