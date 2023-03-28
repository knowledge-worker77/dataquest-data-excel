# The data analysis process

## Asking questions

The first part of the data analysis process starts when someone asks a question. Data analysis projects usually start as **business questions** that reflect a problem or issue that an organization would like to resolve.

For example a company's managers or HR-person could ask these questions:

- What was our rate of employee attrition last year?

- Are there certain times of the year when employees are more likely to leave the company?

- How effective have our bonus policies been at retaining employees?

- What will be the attrition rate next year?

These are all examples of questions that we can answer using data analysis. Good data questions are specific and include guidance on the who, what, when, how much, and/or where of the analysis.

## Getting data

After gathering the questions the data analyst will start to collect data based on these questions.

Using the five-whys technique the  collection process could be divided into five parts.

- **Who:** Who collected the data. Did they changed or tweaked the questions or did they made the answers biased?

- **What**: What data is included? Is the data complete? Does it address the data questions?

- **When**: When was the data collected? Is it current? Is it still relevant?

- **Where**: If the data is from an external source, where did it come from? Is the source reputable? Trustworthy?

- **Why**: Why was the data collected? Can data collected for one purpose be appropriately used for another purpose?

## Preparing data

The process of preparing the data for exploration and analysis generally includes the following:

- **Extracting the data from its source**: This may involve writing SQL queries to extract and transform the data from a database or downloading it from an external source.

- **Transforming/organizing the data**: This involves summarizing the data, joining data from different sources, and putting it into a format that is accessible in the tool you'll use to explore it

- **Cleaning the data**: This involves things like removing duplicate data, correcting inaccurate or missing data, reformatting columns, and dealing with outliers.

# Exploring data

After we have cleaned and prepared the data we need to explore it to find meaningful insights that we can use to answer the questions that we were given.

Exploring the data helps us to understand the data and uncover initial patterns or interesting features in the dataset. This step can also help us determine what we should address later in the data analysis process.

> There are multiple tools that you can use to explore data based on the type of data that you have.

## Data Visualization

Data visualizations display quantitative and qualitative data for quick interpretation. Visuals can help you quickly see the distribution (how concentrated or spread out the values are) or trends in the data.

Data visualizations helps us to see more than just the maximum and minimum values like we can use a pie-chart to divide the data into segments or use a histogram to see the previous trends for that data.

Histograms work great for quantitative variables but not qualitative variables. To see the distribution of qualitative variables, we can use a simple bar chart with the unique values on the X-axis and employee counts on the Y-axis

# Data analyzation

After exploring the data we need to analyze it and extract meaningful insights from it that will help us in making data-driven decisions. There are four levels of data analysis that are most common and they all work together to make the analysis process easier.

**Descriptive analysis** uses past data to answer the question *What happened*? Previously collected data undergoes analysis to answer key questions about past situations or events.

**Diagnostic analysis** seeks reasons or explanations for what has happened, asking and answering the question *Why did this occur*? Because it is often difficult or impossible to prove cause and effect, diagnostic analysis tends to explore correlations and other relationships in data.

**Predictive analysis** uses past data to predict future occurrences or unknown values. It addresses the question *What is likely to happen in the future*? It uses statistical methods and machine learning to identify trends, patterns, and relationships in the data.

Predictive analysis is commonly used to forecast customer behavior, credit card default and fraud, market trends, labor demand, weather events, and other important business and social outcomes of interest.

**Prescriptive analysis** is the most sophisticated of the four levels, using historical data to address the question *What should we do*? It analyzes data and generates advice on possible outcomes for different decisions, helping guide decision-makers toward action. Prescriptive analysis helps to automate future decisions, such as evaluating the credit-worthiness of a borrower.

> Spreadsheet tools are best for performing basic forms of data analysis, but predictive and prescriptive analysis require more advanced tools.

## Communicate the Results

The final phase of the data analysis process is to show the results to stakeholders and the aim here is to share the results of the analysis with stakeholders and interested parties. These results can take many forms, such as reports, dashboards, presentations, visualizations, or even simple things like emails and conversations.

One of the most powerful tools for effective data storytelling is data visualization. Good data visualizations can help your audience quickly grasp the key takeaways from an analysis.

We should remember the following principles when creating data visualizations and communicating results:

1. **Design for an audience**: tailor results and visualizations to the appropriate audience.  This includes using visuals and metrics that the audience will easily understand.

2. **Less is more**: the takeaway from each visual should be clear. Adding too much data or unnecessary design features can distract our audience from the main point. This is called maximizing the data-to-ink ratio.

3. **Clear labels and annotations**: The chart titles, axis titles, legends, etc. should work together so a viewer can read the chart or report and know what the data represents without guessing.

4. **Tell a story with data**: *data storytelling*, which has now become its own sub-field, involves communicating data insights via narratives and visualizations. Using elements from storytelling, such as a hook, a narrative, and a moral of the story, can make our analysis more memorable and engaging.