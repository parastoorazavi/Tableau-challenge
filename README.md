# Tableau-challenge

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Bonus Part](#bonus_part)

## 🧐 About <a name = "about"></a>
Congratulations on your new job! As the new lead analyst for the New York Citi Bike(https://en.wikipedia.org/wiki/Citi_Bike) Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the Citi Bike Data (https://www.citibikenyc.com/system-data) webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.

![Bar Chart](https://github.com/parastoorazavi/Tableau-challenge/blob/main/citi-bike-station-bikes.jpg)


## 💻 Getting Started <a name = "getting_started"></a>

**Task:** <br>

Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

Design 2-5 visualizations for each discovered phenomena (4-10 total). You may work with a timespan of your choosing. Optionally, you may merge multiple datasets from different periods.

The following are some questions you may wish to tackle. Do not limit yourself to these questions; they are suggestions for a starting point. Be creative!

•	How many trips have been recorded total during the chosen period?

•	By what percentage has total ridership grown?

•	How has the proportion of short-term customers and annual subscribers changed?

•	What are the peak hours in which bikes are used during summer months?

•	What are the peak hours in which bikes are used during winter months?

•	Today, what are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesize these are the top locations?)

•	Today, what are the top 10 stations in the city for ending a journey? (Based on data, why?)

•	Today, what are the bottom 10 stations in the city for starting a journey? (Based on data, why?)

•	Today, what are the bottom 10 stations in the city for ending a journey (Based on data, why?)

•	Today, what is the gender breakdown of active participants (Male v. Female)?

•	How effective has gender outreach been in increasing female ridership over the timespan?

•	How does the average trip duration change by age?

•	What is the average distance in miles that a bike is ridden?

•	Which bikes (by ID) are most likely due for repair or inspection in the timespan?

•	How variable is the utilization by bike ID?



## ⏱Bonus Part -	Impress the Boss. <a name = "bonus_part"></a>

Why make a static graphic when D3 lets you interact with your data?

![Bar Chart](https://github.com/parastoorazavi/D3-challenge/blob/main/Images/7-animated-scatter.gif)

**More Data, More Dynamics:** <br>
You're going to include more demographics and more risk factors. Place additional labels in your scatter plot and give them click events so that your users can decide which data to display. Animate the transitions for your circles' locations as well as the range of your axes. Do this for two risk factors for each axis. Or, for an extreme challenge, create three for each axis.

•	Hint: Try binding all of the CSV data to your circles. This will let you easily determine their x or y values when you click the labels. 

**Incorporate d3-tip:** <br>

While the ticks on the axes allow us to infer approximate values for each circle, it's impossible to determine the true value without adding another layer of data. Enter tooltips: developers can implement these in their D3 graphics to reveal a specific element's data when the user hovers their cursor over the element. Add tooltips to your circles and display each tooltip with the data that the user has selected. Use the d3-tip.js plugin developed by Justin Palmer—we've already included this plugin in your assignment directory.

![Bar Chart](https://github.com/parastoorazavi/D3-challenge/blob/main/Images/8-tooltip.gif)

•	Check out David Gotz's example to see how you should implement tooltips with d3-tip.
