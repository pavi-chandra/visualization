# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 


    > What software did you use to create your data visualization?
    
    I used Python and Excel. I hope you can access the Excel document in the Assignment folde. In case you cannot, you can use this link: https://utoronto-my.sharepoint.com/:x:/g/personal/pavi_chandrasegaram_utoronto_ca/IQChudlOg316RpLhWZ3XeBLxASa8uNeTQKbpoT3Ld-Y6bPQ?e=JjvTnk.  

    > Who is your intended audience? 
    
    For both visualizations, the intended audience are individuals working in EDI-related initiatives or labour market analysts. The graphs illustrate the wage gap by either gender or by immigration status.  While the visualizations do not capture the full complexity of the issues, they highlight that overall wage disparities have not improved in recent years. 

    > What information or message are you trying to convey with your visualization? 
    
    Python: This visualization focuses on the wage gap between men and women who are employed full-time. 
    
    Excel:  This visualization examines wage discrepancies based on length of time in Canada among different immigrant groups.  Fo some consistency, I limited the dataset to individuals who are employed full-time, possess a university education and are over the age of 25. 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
    
    Python:   Visually, this graph clearly highlights the average wages men and women and the resulting wage gap.  By using a relative stacked bar chart, the contrast between the pink and blue segment is easy to see at a glance.  The accompanying line graph reinforcement the gap and how it has changed over time.  I initially selected traditional gender-associated colours (pink for women and blue for men) to make the comparison immediately intuitive for viewers. 
    
    Excel:  The line graph shows that the wage gap among the three groups - Canadian born, established immigrants, and recent immigrants - has persisted over time.  It also highlights that a longer duration in Canada is correlated with higher wages, although this relationship should not be interpreted as causal without further analysis. 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    Python: I set a seed to support reproducibility and included detailed comments throughout the code to ensure that the visualization can be recreated. 
    
    Excel: To support the reproducibility of the visualization, I created a cover sheet to provide a high-level, step-by-step instructions. 
    
    > How did you ensure that your data visualization is accessible? 
    
    Python:  I verified the colour choices provided enough contrast for individual with various forms of colour blindness.  To ensure this, I used the Coblis Colour-blindness Simulator.  I also incorporated clear titles, and axis labels to enhance readability and support accessible interpretation.  In addition, I used sans-serif font and kept the font the same across all labels. 
    
    Excel:  I applied similar strategies as those used in the Python visualization.  I selected colours and saturation levels that provided distinct contrast to ensure the visualization was still accessible to individuals with colour-blindness.  In addition, the titles and labels offer clear guidance on the information being presented. 
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    
    Python: I would characterize this as a rational appeal within the three elements of persuasion.  The wage gap reinforces the understanding that women are underpaid compared to men.  Pay equity is both a federal and provincial mandate in Canada, requiring employers to provide equal pay for work of equal value.  The gap narrowed briefly between 2018-2020 - a period when pay equity was at the forefront of public narrative as it was going the legislative process at the Federal level. It widened again during the COVID-19 pandemic, when women disproportionately assumed carrying and household responsivities (Source: https://canadianwomen.org/blog/gendered-impacts-of-coronavirus/).  This visualization underscores the ongoing need for systemic action to achieve pay equity. 
    
    Excel: Given the current political climate around immigration and labour, this visualization shows that immigrants experience wage disparity compared to Canadian-born.  I'd describe this as more of a moral (to almost emotional given the current sensitives surrounding immigrants) appeal of persuasion.  There is a narrative suggesting that immigrants are "taking jobs" but this visualization shows that even after many years in Canada and becoming assimilated, immigrants are not earning the same wages as their Canadian-born colleagues.   
    
    I want to reiterate that in both examples, it's important to note that this dataset by itself cannot give us any firm conclusions. We need a lot more detailed information to do proper and fair comparison.  For example, we don't know what type of jobs the people in each category are doing. 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    Python: Given the number of variables available in the dataset, it would have been possible to do analysis with multiple dimensions. However, for the purposes of this visualization, I chose to focus exclusively on individuals in full-time employment to maintain paint an overall picture. Although I am interested in exploration how immigration and education level may influence wage gaps between women and men, I am not yet sufficiently skilled in Python to conduct this level of complex data processing. 
    
    Excel: Since I’m a bit more comfortable working in Excel and I performed extra data manipulation in this version. I filtered the dataset by age (25+), education (have university degree or higher) and collapsed the relevant immigrant categories into the three groups (Canadian-born, Established Immigrants, Recent Immigrants). As I wanted to focus specifically on university educated , I didn’t include any data from the age category 15+ but instead only selected to look at 25+. 
  
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    Building a visualization from scratch in Python was a challenge for me as I was just introduced to writing Python code in this program.  I relied a lot on the resources provided in this program and on examples I found online to experiment on the code until I settled on what I was happy with.  Although I wasn’t able to attend office hours, the class lecture notes were incredibly helpful.  On a personal level, I leaned heavily on my sibling to provide caregiver support while I focussed on getting this assignment done.  

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
* Submission Due Date: `23:59 - 02/23/2026`
* The branch name for your repo should be: `assignment-3`
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
