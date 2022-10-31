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

## Indicators by G7 Nations in 2010
![image](https://user-images.githubusercontent.com/112588261/198913177-d4891389-e8b8-42ea-bbee-6779c182528d.png)

### Average Years of Schooling
![](charts/school_G7_2010_bar.png)

The data ranges from a low of 9.11 years of schooling in Italy to a high of 13.53 years in the United States, with an average of 11.4.  This range of over 4 years is relatively large.  Note also that the top two nations are in North America.

### Life Expectancy
![](charts/life_expectancy_G7_2010_bar.png)

Life Expectancies range from a low of 78.54 years in the United States to a high of 82.84 years in Japan.  The average across the G7 is 80.96 years.  Life expectancies are fairly consistent, with a range of 4.3 years, slightly less than the range in schooling years.

### GDP Per Capita
![](charts/GDP_per_capita_G7_2010_bar.png)

Italy has the lowest GPD per capita at $35,158, while the United States has the highest at $48,650.  The average is $38,668.  Once again the top two are the North American nations.  The United States' GDP per capita is nearly $10,000 above the G7 average.

Examining these three bar graphs, it is interesting to note that France, Italy, and Japan are the bottom three in both Average Years of Schooling and GDP Per Capita, while they are the top three in Life Expectancy.  

## Indicators by G7 Nations from 1990-2010

### Average Years of Schooling
![](charts/school_G7_line.png)

Here we see that the United States has maintained a significant advantage over the entire period, while France and Italy have remained at the bottom. The slopes of each line are relatively constant with a few notable exceptions.  Italy's numbers declined from 1990 to 1995 before beginning a steady rise.  The only other decrease is schooling was in the United Kingdom from 1995 to 2000, which was also followed by a steady rise.  

### Life Expectancy
![](charts/life_expectancy_G7_line.png)

Japan's life expectancy has exceeded the rest of the G7 for the entire time period under study.  The United States has consistently held the bottom spot, with the gap widening.  

### GDP Per Capita
![](charts/GPD_per_capita_G7_line.png)

The United States has held a strong lead in GDP per capita for the entirety of these two decades.  All seven nations seem to be steadily increasing at roughly the same pace, with the notable exception of the Global Financial Crisis of 2008.  

## Knowledge vs. Quality of Life
![](charts/school_v_le_scatter.png)

This scatter plot comparing average years of total schooling with life expectancy for all nations (not just the G7) in 2010 seems to suggest that people with more education live longer, though the correlation does not seem very strong.

![](charts/school_v_le_regress.png)

This regression shows the correlation between average years of total schooling and life expectancy.  A very rough estimate is that life expectancy increases about 5 years for every additional 3 years of schooling, though there is a great deal of variation.  

![](charts/school_v_gdp_scatter.png)

Again looking at all nations, this scatter plot shows a relationship between schooling and GDP per capita.  More educated nations tend to be wealthier.

![](charts/school_v_gdp_regress.png)

It appears that 1 year of schooling is associated with $3,000 in GPD.  There is much less variation in this scatter plot.

## Future Study
It would be interesting to investigate possible causes of these drops in schooling years.  
