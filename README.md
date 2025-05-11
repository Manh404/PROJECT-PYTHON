# PROJECT-AIRLINE
In this section I will use data analytics projects briefly describing the technology stack used to solve cases.

Goal: to conduct a comprehensive statistical analysis of the dataset to gaininsights into passenger demographics, travel patterns, and peak travel times.

Description: Our dataset comprises nearly 100,000 records of flight information, including details about passengers, their demographics, travel patterns, and arrival dates.

## Part 1: DESCRIPTIVE STATISTICS:
<img width="556" alt="Image" src="https://github.com/user-attachments/assets/bc703b01-8d90-4fa4-82e2-27c7761259d1" />

* Summarize passenger demographics: Calculate age distribution, gender
proportions, and frequency of different nationalities.

* Understand travel patterns: Describe most frequent airports, continents of
departure and arrival, and common routes.

 * Identify peak travel times: Explore date of arrival patterns to reveal busiest
periods.

### Move to gender proportions

<img width="503" alt="Image" src="https://github.com/user-attachments/assets/353fd06a-a4f4-476c-8168-0035ac508596" />

* Nearly 50% in both sexes, shows that the rate of plane use in men and women is
almost equal

### top 20 frequencies countries
<img width="566" alt="Image" src="https://github.com/user-attachments/assets/06899084-fb69-48a1-b8f5-42f279ae212c" />

As China accounts for the largest share.

##  Part 2: VISUALIZATION:

* I decide to compare travel patterns between genders or age groups: Test for differences in
the proportion of cancelled flights between countries using Chi-squares test and using t-test to
determine whether differences in mean ages between Japan and China.

<img width="452" alt="Image" src="https://github.com/user-attachments/assets/8922ceca-b821-4cc5-9bc2-9d733d6d19fc" />

* The results show that although there are nearly 100,000 flights, the most used
airport is only 46 times, so it can be concluded that flyers come from as many places
around the world as there are diverse airports.

* Finally in this part I look for the time of year when people travel most often
<img width="437" alt="Image" src="https://github.com/user-attachments/assets/2ee5cedc-9a50-4d04-b69c-97e18034c0f1" />

* The results show that the months of May, July, August have the most flights and
February has the fewest flights

* Create histograms of age and passenger counts by airport or continent.

<img width="433" alt="Image" src="https://github.com/user-attachments/assets/9406b939-cc22-41bc-88f7-08b786e2956c" />

* Knowing the age of passengers can affect the marketing strategy as well as the
audience that airlines target and care about.
* As shown in the chart above, the majority of passengers are between the ages of 40
and 60.

<img width="455" alt="Image" src="https://github.com/user-attachments/assets/7f86a0c8-6984-42bc-b82a-0e24163e1bad" />

* As with the above section, understanding the number of passengers from different areas helps airlines adjust appropriate diets and use appropriate language.

* Based on the data divided between men and women, we can create some tables to
better understand the data as well as the distribution.
<img width="475" alt="Image" src="https://github.com/user-attachments/assets/88aee797-fbe7-424c-a7cd-812a7ba198e1" />

*Synthesizing from three different values can produce a chart shown above, thereby helping data analysts better understand the value they are working on as well as see the distribution of data to get results. can be visualized later.
<img width="461" alt="Ảnh màn hình 2025-05-11 lúc 10 58 33" src="https://github.com/user-attachments/assets/37a0ef97-d93d-4d15-b3c2-c67fd31cdbf6" />

* The chart above applies some basic functions to better visualize the data such aszooming, and hovering over columns of values for display. That helps some people who are not too familiar with data to understand more easily.
<img width="441" alt="Image" src="https://github.com/user-attachments/assets/2edbf2be-d0c0-4741-a8a5-fb5801369351" />

* Finally, an example of displaying values on a scatter plot to see the distribution of values, while displaying more values and applying utility functions for observing and
understanding data.

<img width="485" alt="Image" src="https://github.com/user-attachments/assets/b8e8c24f-c45c-43cc-9523-fa7b4813b21d" />

## Part 3 : Hypothesis Testing

* Compare travel patterns between genders or age groups:
** Test for differences in the proportion of cancelled flights between countries using chi-squares
test
** Using t-test to determine whether difference in mean ages between Japan
and China with alpha = 0.5,0.1,0.25

<img width="428" alt="Image" src="https://github.com/user-attachments/assets/92fd4ea0-a501-48d7-9749-743cb0bf4c70" />

* From there, the box plot is given as below. Because the data is quite perfect, there are no outliers

* Use chi-square statistics to predict and draw conclusions about accepting or rejecting the hypothesis

<img width="429" alt="Image" src="https://github.com/user-attachments/assets/0c957689-8454-4a22-97fb-9af3a98649af" />

