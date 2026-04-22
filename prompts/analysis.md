# Prompt templates for data analysis

This first template uses a number of techniques including being explicit about which columns and calculations to use, attaching a glossary and methodology, and giving 'permission to fail/be uncertain'.

```
Attached is data on the gender pay gap at every company in the UK.

Also attached is a glossary explaining what the columns mean, and the methodology.

Calculate the mean pay gap using the DiffMeanHourlyPercent column. 

Show me the code you used, with comments explaining each step as if to a 15-year-old with no coding experience.

Before running any code, flag any assumptions you are making about the data or my question.

Warn me if the question does not contain enough information to answer accurately, or if the result could be misleading without additional context. 

Tell me how many rows contain missing or null values in the column and explain how you handled them.

After calculating, run a sanity check: show the total number of rows in the dataset and the number used in the calculation.
```

## Step by step prompt template

This second template describes a process step by step, which is useful to ensure that you have thought through the steps required to arrive at an accurate result. 

You will need to perform the calculation yourself to identify the best steps, and any potential pitfalls to address (in this case, negative numbers)

```
Calculate the ten companies with the biggest pay gaps in the latest data using the DiffMeanHourlyPercent column.
Do this by following these steps:
Convert negative and positive pay gaps so that they can be compared directly (e.g. -100% is the same as a 100% difference, but favouring a different gender)
Sort to identify the companies with the biggest values
Classify to identify whether the gap favours women or men

```
