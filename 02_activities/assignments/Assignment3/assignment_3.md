# Data Visualization

## Assignment 3: Final Project

### Requirements:
We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data.

Choose a dataset of interest from the City of Toronto’s Open Data Portal or Ontario’s Open Data Catalogue.

Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.

For each visualization, describe and justify:
>
>LINK
>https://open.toronto.ca/dataset/permanent-bicycle-counters/

About Permanent Bicycle Counters

This dataset tracks the number of bicycles that pass by permanent sensors on Toronto streets and multi-use paths.
The City uses this data to understand how many people are cycling and to see how bicycle lane use changes with the seasons. 
More counting stations are being added, and the data will be updated once it’s checked for accuracy.

Main datasets and includes:

1.	Detector Locations (cycling_permanent_counts_locations): Shows where each detector is located, along with other details.
2.	Daily Counts (cycling_permanent_counts_daily): Shows the total number of bicycles counted each day by location and direction.
The dataset I am using is number 2, which contains daily counts.

Main Limitations regarding this data set:

•	The total counts include bicycles and small vehicles like e-bikes, scooters, and e-scooters.
•	Riders on sidewalks, in motor vehicle lanes, or in buffer zones are not included.

This dataset was collected from 1994 to 2025. Before 2023, only a few locations had sensors for data collection.
That’s why the graph shows only a small number of locations—they were the only sources of daily count data. 
After 2023, sensors were added to more new locations in both directions.

The visualization (Graph 1994-1995) shows how the number of daily counts increased over time.
The different colors in the bars represent new sensors added to new locations. You can also see a sharp drop in daily 
counts during the pandemic. After the pandemic, there was a dramatic increase in daily counts, which may be partly due 
to the addition of new sensors in more locations. The issue here is that older locations were retired around 2003,
and it is impossible to know whether traffic in those locations increased or decreased by 2025.
For my two visualizations, I decided to use only the daily counts from 2024. This focuses on locations that 
are currently active and highlights which ones have the most activity throughout the year.

Graph1-Python: Visualization 1

For this visualization, I used Python to create a line chart. It shows the monthly total count for each station.
The graph reveals which locations have been the most active during the year and which months see the highest activity. 
Some locations show a steady level of activity throughout the year, while one station stands out as the busiest. 
The curve also shows that activity increases during the summer months.

What software did you use to create your data visualization?
I used Python.

Who is your intended audience?
My audience includes transit planners, city officials, and bike riders interested in station activity trends over time. 

What information or message are you trying to convey with your visualization?
This visualization highlights the monthly total counts for each station, showing which locations have been the most active throughout the year. 
It also reveals seasonal trends, indicating that activity increases during the summer months. Some stations maintain consistent activity levels,
while others show more variation.

What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? 
How did you apply these principles? With what elements of your plots?
I ensured the visualization accurately represents the data by selecting monthly counts and choosing a line chart to emphasize trends over time.I used distinct colors for different stations to make comparisons easier. The design is clean and uncluttered. The chart includes a legend to help users quickly interpret different station trends.

How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible,
how will this impact your data visualization?
The data visualization is reproducible because I documented the steps in Python, including data filtering and preprocessing.
I provided notes within the code to explain each step.

How did you ensure that your data visualization is accessible?
I used clear labels, line thickness and markers made the trends easy to distinguish. 

Who are the individuals and communities who might be impacted by your visualization?
Transit users, city planners, and policymakers could benefit from insights on station activity levels. 

How did you choose which features of your chosen dataset to include or exclude from your visualization?
I focused on monthly total counts for each station to emphasize trends over time. I excluded daily fluctuations
to keep the visualization clear and focused on trends.

What ‘underwater labour’ contributed to your final data visualization product?
Before creating the visualization, I performed data cleaning, and filtering. I also tested different visualization styles. Additionally,
I wrote comments in the code to facilitate reproducibility.

Graph2-Tableau: Visualization 1
For this visualization, I used a bar chart. The chart shows the total yearly usage count for each location. Each bar is divided into two colors,
representing the proportion of usage by direction. Each bar represents one location.
From the bar chart, it is clear which station has the highest activity per year, and which one has the least.
The chart also shows that the usage in both directions is almost equal, meaning the bike lanes are used similarly in both directions.

What software did you use to create your data visualization?
I used Tableau.

Who is your intended audience?
My audience includes city planners and bike riders interested in bike lane usage patterns. 

What information or message are you trying to convey with your visualization?
It shows the total yearly usage count for each location. It emphasizes which locations have the highest and lowest bike activity. 
it reveals the proportion of usage in each direction.

What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? 
How did you apply these principles? With what elements of your plots?
A bar chart to effectively display yearly totals for each location, making it easy to compare usage across locations. 
I used distinct colors to separate usage by direction. The bars are clearly labeled. 
The layout ensures that comparisons between locations are straightforward.

How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, 
how will this impact your data visualization?
I used Tableau, which allows for data filtering and updating without altering the original dataset. I documented the steps taken to create the chart, ensuring others can replicate it with the same dataset or apply it to a new one.

How did you ensure that your data visualization is accessible?
I used clear labels and contrasting colors. The bar sizes make it easy to compare locations 

Who are the individuals and communities who might be impacted by your visualization?
Bike commuters, transportation planners. It could help for infrastructure improvements, bike lane expansions.

How did you choose which features of your chosen dataset to include or exclude from your visualization?
I focused on total yearly usage counts and directional proportions to provide an outline of bike activity. 

What ‘underwater labour’ contributed to your final data visualization product?
Before creating the visualization, I cleaned and structured the data to ensure accuracy. I tested different chart. 
Additionally, I adjusted colour labels for clarity 

   >End Of Assignment
   >

This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice!

Total word count should not exceed (as a maximum) 1000 words

### Why am I doing this assignment?:
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09/03/2025`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
