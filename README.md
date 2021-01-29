# Tableau-challenge

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Bonus Part](#bonus_part)

## 🧐 About <a name = "about"></a>
Congratulations on your new job! As the new lead analyst for the New York Citi Bike Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the Citi Bike Data webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.


## 💻 Getting Started <a name = "getting_started"></a>

**D3 Dabbler:** <br>

![Bar Chart](https://github.com/parastoorazavi/D3-challenge/blob/main/Images/4-scatter.jpg)

You need to create a scatter plot between two of the data variables such as Healthcare vs. Poverty or Smokers vs. Age.

Using the D3 techniques we taught you in class, create a scatter plot that represents each state with circle elements. You'll code this graphic in the app.js file of your homework directory—make sure you pull in the data from data.csv by using the d3.csv function. Your scatter plot should ultimately appear like the image at the top of this section.

•	Include state abbreviations in the circles. 

•	Create and situate your axes and labels to the left and bottom of the chart.

•	Note: You'll need to use python -m http.server to run the visualization. This will host the page at localhost:8000 in your web browser.


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
