## Objective
The objective of the project was to determine the cause of returns at Superstore. I prepared an analysis for the CEO of the Superstore to help them understand what is causing customers to return their orders and how to reduce the volume of returned orders.

## Overview
What is Causing Returns?

1. Make the Returned field into a calculated field where the null values are 0 and the Yes values are 1.
    - Note that the average of this field is the return rate, while the total returns are the count or sum of returns.
3. Now, let’s try to find some root causes for returned orders. Build at least one worksheet for each of the following:
    - A scatterplot showing the correlation between total sales and total returns. Aggregate by product subcategory. Do sales always correlate positively with returns?
    - A bar chart showing the return rate by product category
    - The return rate by customer. To find customers who are more prone to making returns, add a filter to remove customers with only 1 order.
    - A map showing the return rate by some geographic measure (state, city, etc.) to see if there is a geographic concentration to returned orders
    - The return rate by some measure of time (month, week, etc.) to see if there is a seasonal effect to returned orders
    - Two different kinds of composite charts showing the return rate for a mix of multiple factors (date/geography/product category/etc.)
4. In the next section, you will be making a dashboard showing your findings. Document the requirements for the design of a dashboard to get the salient features you found in this analysis.

Building a Dashboard for Monitoring Returns
In this section, 
1. Create a low fidelity mock up of your dashboard. 
    - Make a pen and paper sketch of the dashboard you want to make.
    - Create at least 3 variations, then either scan them or take photos to submit.
    - Choose the one you like the most as the one you’ll be making in Tableau.
2. Create a template for Dashboard using empty containers to match your mock ups
    - Submit a screenshot of the template with empty containers along with the project files when submitting your project.
3. Add your worksheets to the Dashboard template
    - Finalize the dashboards with relevant markers, images, and titles as needed. Submit your mock up, template, and finalized dashboard.

Presenting Your Analysis and Dashboard
1. Construct your story arc for your presentation 1. Create a draft of your story using only captions for each Story Point. Create a duplicate of your draft story (captions only) to submit. The draft Story should include:
    - A summary of your analysis of returns
        - How should returns be measured? Is the return rate, the total cost of returns or the total number of returns a better measure? When is one better than the other?
        - What are the key root causes of returns?
    - An overview of each component of your Dashboard
        - Explain what is contained in each chart and how the chart should be interpreted
    - A demonstration of how the Dashboard should be used
        - Demonstrate how to interpret the Dashboard and how to use filters to identify root causes
        - Describe actions that can be taken after using the Dashboard to identify the root causes
    - A conclusion with proposed next steps (e.g., implementation of Dashboard)
2. Add content to your Story Points
    - Use the worksheets you already created and create new worksheets you might need to support your Story Arc
    - Construct Dashboards to create presentation style slides
    - Save a version of your completed Tableau Story

## Link to Project
https://public.tableau.com/views/Sprint4Project-Revised/LargestProfitLossCenters?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link
## Project Preview
![Sample Image](https://github.com/erikacarlier/TripleTen-Projects/blob/9a8449b42df979d853c3de4fb3454ee28b039a6c/Superstore%20-%20Storytelling%20with%20Data/Photos/Returns%20vs.%20Sales%20by%20Subcategory.png)

![Sample Image](https://github.com/erikacarlier/TripleTen-Projects/blob/9a8449b42df979d853c3de4fb3454ee28b039a6c/Superstore%20-%20Storytelling%20with%20Data/Photos/Return%20Rate%20by%20State.png)

![Sample Image](https://github.com/erikacarlier/TripleTen-Projects/blob/9a8449b42df979d853c3de4fb3454ee28b039a6c/Superstore%20-%20Storytelling%20with%20Data/Photos/Orders%20vs%20Return%20of%20Category.png)

![Sample Image](https://github.com/erikacarlier/TripleTen-Projects/blob/9a8449b42df979d853c3de4fb3454ee28b039a6c/Superstore%20-%20Storytelling%20with%20Data/Photos/Profit%20vs%20Return%20by%20State.png)
