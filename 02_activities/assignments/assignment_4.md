# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

### Visualization 1: Line Chart of Average Occupancy and Capacity Over Time
Software Used:
I used Python with Matplotlib for this visualization due to its flexibility and reproducibility in creating detailed, customizable plots.
Intended Audience:
City planners, social service agencies, and policymakers focused on addressing homelessness.
Message:
This visualization highlights trends in average shelter occupancy and capacity over time, emphasizing periods of strain on the system and identifying potential gaps in resources.
Design Principles:
1.	Substantive: The data was aggregated by date to avoid overwhelming the audience with daily fluctuations and emphasize broader trends.
2.	Perceptual: Distinct colors (blue for occupancy and orange for capacity) with a clear legend were used to ensure the audience could easily differentiate the variables.
3.	Aesthetic: A minimalist design was applied, with gridlines for better readability and appropriate labeling of axes to clarify meaning.
Reproducibility:
The Python code is fully reproducible, as it includes all steps from data loading to plot creation. Sharing the script allows others to replicate and customize the visualization.
Accessibility:
The use of colorblind-friendly palettes ensures inclusivity, and providing the script enables compatibility with assistive technologies.
Impact:
This visualization could influence decisions on shelter resource allocation and emergency response planning.
Data Features:
I focused on daily averages for occupancy and capacity, excluding individual shelter-level details to avoid unnecessary complexity.
Underwater Labour:
Data preprocessing, including cleaning invalid entries, calculating daily averages, and converting date formats, was essential to ensure the visualization was meaningful.
________________________________________
Visualization 2: Bar Chart of Average Occupancy Rate by Shelter Type
Software Used:
I created this visualization in Excel because of its simplicity and widespread accessibility among stakeholders.
Intended Audience:
General public and advocacy groups seeking a high-level overview of shelter usage by type.
Message:
The bar chart highlights differences in occupancy rates across various shelter types, such as family shelters and youth shelters, to identify disparities in resource utilization.
Design Principles:
1.	Substantive: The focus was on average occupancy rates rather than raw counts to ensure comparability across shelter types.
2.	Perceptual: Bar heights were scaled proportionally to the occupancy rate, and category labels were clear and concise.
3.	Aesthetic: A clean, uniform color scheme was applied to minimize distractions, with category names rotated for readability.
Reproducibility:
While Excel is less programmatically reproducible than Python, the steps for creating the visualization were documented, and the dataset is publicly available for replication.
Accessibility:
Legible fonts, clear labels, and high-contrast colors were used to ensure readability. Additionally, the data table underlying the chart was included for transparency.
Impact:
This chart could help identify shelter types that require additional funding or policy intervention to address disparities.
Data Features:
Only the shelter type and occupancy rate were included, as these are directly relevant to the audience's needs. Excess metadata was excluded to maintain focus.
Underwater Labour:
I calculated occupancy rates, removed irrelevant columns, and formatted the data for Excel, ensuring consistency across categories.
________________________________________
Conclusion:
Both visualizations serve distinct purposes: the line chart identifies temporal trends, while the bar chart compares shelter performance. Together, they provide a comprehensive overview of shelter usage in Toronto, empowering stakeholders to make informed decisions.



   

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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
