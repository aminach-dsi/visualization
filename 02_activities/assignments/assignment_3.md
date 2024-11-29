# Data Visualization

## Assignment 3: Data Visualization Ethics

### Requirements:
- Let’s return to the data visualizations we evaluated for Assignment 2.  
- For each visualization: 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 
```
Good visualization : Energy Consumption vs. GDP Dashboard
Source : https://public.tableau.com/app/profile/energyforgrowthhub/viz/final_ConsumptionvsGDP/Sheet1

This visualization is accessible because it uses a scatter plot, a standard and universally understood chart type. The clear labeling of axes, the inclusion of tooltips for additional context, and the subtle color scheme make the visualization user-friendly for a diverse audience, including those with visual impairments or cognitive challenges. The interactivity enhances accessibility by allowing users to explore dimensions of interest.  

Reproducibility is high because the visualization is hosted on Tableau Public, ensuring transparency and easy access to the underlying dataset and visualization structure. The use of standard charting practices further ensures that others can replicate this work using similar tools or software.  

Equity is maintained as the data is presented without bias, offering an unbiased comparison of energy consumption and GDP across countries. The design avoids emphasizing specific regions or economic statuses, ensuring that insights are presented objectively to all users.  

Bad visualization : Radial Stacked Bar Charts by Ryan Rowland
Source : https://public.tableau.com/app/profile/ryan.rowland/viz/RadialStackedBarCharts/RadialStackBarCharts

This visualization is not accessible due to its radial design, which complicates the interpretation of segment sizes and comparisons. The lack of clear labels and inadequate contrast in the color palette further impedes comprehension, especially for individuals with visual impairments.  

Reproducibility is limited as the unconventional chart type (radial stacked bars) is not intuitive and requires specific design knowledge. Without documentation or access to the dataset, recreating this visualization is challenging.  

Equity is undermined as the cluttered design and unclear labeling make it difficult for all audiences, particularly those with limited technical or analytical expertise, to derive meaningful insights. The design also risks marginalizing viewers who may lack familiarity with radial visualizations.
```
    How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)?  
```
The good visualization could be improved by incorporating explicit annotations to highlight critical trends or outliers. Additionally, reproducibility could be further improved by including a link to download the raw dataset and providing detailed documentation on the methodology used to process and visualize the data.  
For equity, adding a contextual narrative about energy and GDP disparities (e.g., historical, regional factors) could provide a more inclusive understanding. Offering data for underrepresented or smaller economies, would ensure all regions are equitably represented.

The bad visualization could be improved by adopting a more conventional chart type (e.g., bar or line chart), which facilitate easier comparisons and trend identification. Clear labeling and a high-contrast color scheme would make the chart more user-friendly and inclusive.  
To enhance reproducibility, the creator should share the dataset and provide documentation explaining the methodology used to aggregate and visualize the data. This would allow others to replicate or validate the results using accessible chart types.  
Equity could be addressed by reducing the number of categories displayed, focusing on key insights rather than overwhelming the viewer with excessive detail.
```

 - Word count should not exceed (as a maximum) 300 words for each visualization. 

### Why am I doing this assignment?:
- This ongoing assignment ensures active participation in the course, and assesses learning outcomes 2 and 3:  
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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * This markdown file (assignment_3.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
