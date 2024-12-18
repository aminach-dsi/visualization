# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    > 
    Visualization 1: Python ==> See "Visual_by_python.ipynb" file
    Visualization 2: PowerBI ==> See "Visual_by_PowerBi.pdf" file
    I used data from Ontario’s Open Data Catalogue: https://data.ontario.ca/dataset/national-occupation-classification-noc-skill-level/resource/310484f5-fe9c-4ba6-aa76-7422899dfd71
    The CSV file is in this folder and called "Unemployement_rate.csv"
  
    > Who is your intended audience?
    > 
    My audiences are Data analysts, executives and non-technical decision-makers.
  
    > What information or message are you trying to convey with your visualization?
    > 
    Highlight trends or correlations in unemployment rates over time for specific occupations in Ontario
  
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
    > 
    I Used clear labeling and a horizontal bar chart for readability (perceptual), consistent color schemes (aesthetic), and accurate representation of data points (substantive).
  
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
    > 
My Python visualization is reproducible, as it is built with clear, well-documented code, version control, and detailed documentation of data cleaning and processing steps.

My PowerBI visualization ensures reproducibility through saved project files that preserve the dataset, transformations, and visualization settings, enabling consistent results when reopened or shared.

    > How did you ensure that your data visualization is accessible?  
    
For Accessibility, I used clear and concise labels, color schemes that are accessible to colorblind individuals.
In addition, for the PowerBI visualization, I Implemented tooltips and drill-down capabilities to allow users to explore data in more detail.
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    
Employers, policymakers addressing labor market inequalities, and the IRCC (Immigration Refugees and Citizenship Canada) to help them make informed decisions about immigration policies.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
I focused on the unemployment rates for specific occupations in Ontario, as this is the most relevant information for my target.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    
For Python's visual : Data cleaning, filtering, and debugging visualization code.
    
For PowerBI's visual : Data transformation, data modeling, and data visualization design.

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
