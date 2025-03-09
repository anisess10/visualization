# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      For this assignmnet , i selected an interactive dashboard as a form of visualization that is widely in use to convey data driven insights  to  end user.
      Good visualization: https://public.tableau.com/app/profile/ayodeji.omokehinde.eseohe/viz/E_Commerce_Admin/Overview

        1. Intended Purpose :
           >> High-Level Overview: The dashboard is designed to give a snapshot of eCommerce performance—key metrics like total profit, distinct customers, average price, etc., are surfaced at a glance.
           >> Quick Decision Making: By placing the most critical KPIs (e.g., total profit, cost of goods) in a central positions, the dashboard aligns with the goal of supporting quick, data-driven decisions.

        2. Audience:
            >> The design caters to a varierty of  audiences (Business Stakeholders & Managers, Operational Teams), it uses straightforward language, large numeric displays, and clear statuses (e.g., “Completed,” “Canceled,” “Returned”).

        3. Cognitive Load
            >> Minimal Visual Clutter: The design avoids overwhelming the viewer with too many charts or competing colors. White space around cards and charts helps seperate each element 
            >> Clear Labeling: Each section has concise labels (e.g., “Last Transaction,” “Locations,” “Shipped Product”) that reduce guesswork about the data being presented.
            >> Highlighting key Metrics: Important metrics are in bold or larger text, so users can process them quickly.
            These features collectively reduce cognitive load,  the viewer can scan and understand key insights with minimal effort.
        
        4. Descriptive vs. Prescriptive Insights
            >> Descriptive: The dashboard describes current and historical performance 
            >> Prescriptive: By highlighting returns, cancellations, and pending orders, it implicitly encourages the user to take action (e.g., investigate reasons for returns, follow up on pending orders). This can guide business decisions (e.g., “We need to reduce cancellations” or “We should focus on high-profit products”).
        
        5. Gestalt Principles

            >> Proximity:Related metrics (e.g., total profit and cost of goods) are grouped close together. Transaction details are placed together in a single table.
            >> Similarity:  Consistent use of color (green for profits,  red for returns or canceled items) creates immediate recognition of statuses.


    Example of Bad visualization: https://public.tableau.com/app/profile/nouer.uz.zaman/viz/RMinterview/RMDashboard

        1. Inconsistent Layout and Formatting: Multiple chart types and styles appear randomly placed. This lack of uniformity makes it harder to replicate or scale the dashboard in a systematic way.
        2. No Clear Framework: There does not appear to be a consistent design system (color palette,  spacing) that can be easily extended for new data or new metrics.
        3. Intended Purpose Is Unclear: The dashboard has several disparate charts without a central goal, making it hard to identify what is most important.
        4. Audience Considerations
            >> Mixed Level of Detail
            >> Hard-to-Read Text and Labels: Some labels and axis titles appear small or truncated, which can be frustrating for users who need a quick scan. 
        5. Cognitive Load
            >> Too Many Visual Elements : Several small charts, each with different dimensions, create visual noise. 
            >> Lack of Clear Labels: Some bar charts use abbreviations or truncated text; others have legends far from the chart. 
            >> Unnecessary Complexity: The treemap, horizontal bar charts, vertical bar charts, and tables are all competing for attention,  obscuring the main message.



      ```
    - How could this data visualization have been improved?  
      ```
        We could improve this dashboard by doing the following: 
            1. Define a Clear Purpose and Audience: Decide if the dashboard is for high-level executives who need key KPIs or for operational teams who need detailed breakdowns. That will guide the level of detail and which charts to include.
            2. Establish a Visual Hierarchy: Identify a number of key metrics (e.g., total bookings, YOY growth, top routes) and place them prominently at the top. Use larger text, bold numbers, and a consistent color scheme to draw attention.
                Group related charts together. 

            3. Eliminate redundant or low-value visualizations. Combine charts if they are showing similar dimensions. Simplify the layout to avoid overwhelming the viewer.
            4. Use Consistent Design Elements: Standardize the color palette so that certain categories always appear in the same color.
            5. Use uniform chart types for related metrics (e.g., all bar charts for spending comparisons).
            6.Improve Labeling and Readability: Increase font size for titles, labels, and legends.
            In a tool like Tableau or PBI, add filters or interactive elements so users can drill down by region, service type, or time period.







      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 02/03/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
