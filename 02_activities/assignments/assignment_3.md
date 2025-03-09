# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
    > The dataset i selected is the Toronto Island Ferry Ticket Counts, This dataset provides near real-time information about Toronto Island ferry ticket sales and ticket redemptions.
    > Link to the Dataset: https://open.toronto.ca/dataset/toronto-island-ferry-ticket-counts/


- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
![alt text](<Python 2.png>) ![alt text](python3.png) ![alt text](<Python 1.png>) ![alt text](<PBI Viz.png>)
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
        + For this assignment i used Python and Power BI as my visualization softwares
    > Who is your intended audience? 
        + Ferry Operations Managers and Transit Planners: Those responsible for managing and optimizing the Toronto Island Ferry service.
        + City Officials and Policy Makers: Interested in transit performance, public transportation usage, and infrastructure planning.
        + Advocay Groups or Analysts and Researchers: Focused on  interested in traffic safety, environmental impacts, and availability  of transportation options to Toronto isalnd.

    > What information or message are you trying to convey with your visualization? 
        + Usage Trends: Showing  ticket sales  to highlight peak periods and operational trends.
        + Seasonal Patterns: Illustrating seasonal, monthly, or hourly variations in ferry usage to support decision-making for scheduling and resource allocation.

    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
        + Substantive:
                Focused on key metrics—ticket sales  directly address service performance.
                Excluded less relevant details (like transaction IDs or redemptions) to keep the message clear.
        +Perceptual:
                Applied clear color gradients in the heatmap to differentiate high and low activity periods.
                Used grouped bars in the bar chart to facilitate side-by-side comparisons of different time periods.
        +Aesthetic:
                I Chose a clean, minimal layout with legible fonts and consistent color schemes.
                Ensured that titles, labels, and legends are clear, reducing visual clutter and enhancing readability.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
        + I used Python with libraries like pandas, matplotlib, and seaborn. Documented the code steps, so anyone with the same dataset and code can reproduce the visualizations.
        + In the case of PBI viz where the visualization is not reproducible , it would make it difficult for others to vet my work or build on what i have already done, thus, limiting transparency and relaibility 

    > How did you ensure that your data visualization is accessible?  
        + Through pushing to Github for vetting and validation by support staff or DSI participants
        + Color Choices: Selected color-blind friendly legends.
        + Clear Labeling

    
    > Who are the individuals and communities who might be impacted by your visualization?  
        + Ferry Riders and Commuters: Understanding service patterns can affect travel decisions and satisfaction.
        + Local Residents and Tourists: Insights into ferry usage may influence local business hours, transit planning, and tourist information.
        + City and Transit Planners: Data-driven insights can guide operational improvements, budget allocations, and future infrastructure development decisions.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
        + I included the most important features like date/timestamp and sales count so i can drive trend analysis in ticket sales 
        + I didn't use any Metadata like transaction ID as it does not contribute to understanding the overall ferry usage trends 
    
    > What ‘underwater labour’ contributed to your final data visualization product?
        + Data Transformation: Extracting relevant time components (like day, month, and hour) from the timestamp to aggregate data appropriately.
        redemption counts are correctly parsed.
        + Iterative Design: Experimenting with multiple chart types (e.g., bar charts, heatmaps, line charts) and adjusting layouts, color schemes, and annotations to find the most effective way to communicate the insights.
        + Making sure my code is reproducible by documenting and annotating each step 


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
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
