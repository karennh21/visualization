# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    
      I used python to create the data visualization for influenza trends in Toronto from 2023 to 2025.  

    > Who is your intended audience? 

     My intended audience is healthcare organizations and stakeholders such as public health units, epidemiologists, physicians, health promoters, and policy makers. This audience monitors influenza activity and rely on clear, accessible visualizations which help support decision‑making around surveillance, resource allocation, and vaccination campaigns.

    > What information or message are you trying to convey with your visualization? 
    
      The data visualization tries to communicate the monthly influenza trends in Toronto from 2023 to 2025. The primary goal is to compare how the influenza cases fluctuate throughout the year and compare seasonal trends from year to year. The trends are pretty consistent throughout 2023 to 2025 with more influenza cases being reported from January to May and then picking back up in November to December. While influenza case counts alone cannot determine vaccine effectiveness, the visualization provides context for understanding how influenza behaves during and after vaccination campaigns. Each year, the flu vaccine uses a different strain in hopes of matching the strain that will be transmitted throughout the flu season. Observing the seasonal pattern of cases can help identify whether certain years experienced higher or lower influenza activity. In 2023 to 2025, we can see that the highest number of cases were mostly in 2025. So, there could be a relationship between the effectiveness of the flu vaccine strain compared to the number of reported cases. The visualization therefore supports exploratory thinking about vaccine performance, but does not claim to measure vaccine effectiveness directly. 

    > What aspects of design did you consider when making your visualization? How did you apply them?

    I considered several design aspects when making my visualization. I wanted to ensure the data visualization required low cognitive load, had aesthetic, substantive, and perceptual qualities. 

    By using a grouped bar chart with multiple distinct colours, it easily displays and compares the monthly data from 2023 to 2025. The bar chart is a familiar chart type and the distinct simple colours are aesthetic. I used a colourblind safe palette (#332288, #88CCEE, #44AA99) to ensure that viewers with colour‑vision deficiencies can distinguish the bars for each year. 

    To ensure the visualization was accurate, concise, and substantative, I used plotly to make it an interactive data visualization to display the number of influenza cases each month from 2023 to 2025. I explicitly defined font families, sizes, and colours for the title and axis labels to maintain consistency and improve readability.
    I used a tight layout with controlled margins to reduce visual clutter and keep the focus on the data. The legend was centered to improve balance and visual hierarchy. As well, I added a source annotation at the bottom of the figure to provide transparency about the dataset without distracting from the main content.
    
    Furthermore, to ensure the visualization is percetual and explanatory, each bar trace includes a descriptive legend name (e.g., “2023 Monthly Influenza Cases”) to support interpretation and screen‑reader accessibility.As well, I added an annotation to explain the purpose of the data visualization. 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    I ensured reproducibility by clearly defining all colours rather than relying on default or randomly generated palettes. As well, I specified fonts, layout dimensions, and margins so the figure renders consistently across environments. I used fixed trace order to ensure the bars appear in the same sequence every time. As a result, I am not introducing randomness into the functions. Since the data visualization uses Plotly, it is deterministic when styling choices are explicitly defined. 

    If a visualization tool were not reproducible, it could lead to inconsistent colours, layouts, or ordering across runs. As a result, it may not reproduce the same results which could affect how the audience interprets the influenza trends. This would affect perceived perceptual basis and undermine the accuracy of the data visualziation. As well, it could complicate peer reviews and make it difficult for others to replicate the visualization to confirm the validity of the analysis. 
    
    > How did you ensure that your data visualization is accessible?  
    
    I incorporated several accessibility practices such as using a colourblind safe palette. I used the Okabe-Ito palette which distinguishes across colour-vision deficiencies. By using these colours and having a white background, it provides high contrast for the data and improves visibility for low-vision audience members. I also differentiated the font for the labels to ensure that they were clear and easy to read. The font size is larger for the title of the graph compared to the axis labels and legend labels. I made smaller tick labels and re-positioned the legend and annotation so it would not obstruct the data. As well, I was descriptive and concise with the legend labels to reduce ambiguity for the audience members. Lastly, I included a metadata annotation to summarize the purpose of the data visualization. 

    
    > Who are the individuals and communities who might be impacted by your visualization?  

    This visualization impacts groups connected to influenza surveillance and seasonal health planning. Healthcare organizations and public health units may rely on these trends to anticipate seasonal surges, allocate resources, and plan vaccination campaigns. Clinicians, nurses, and hospital administrators could use the information to prepare for increased patient volumes and adjust staffing or infection‑control measures. Policy makers and health promoters may draw on these trends to inform decisions about vaccine distribution, public health messaging, and vaccination campaigns. Researchers and epidemiologists may use the visualization as a starting point for deeper analysis of influenza seasonality or strain circulation. Although not the primary audience, community members indirectly benefit from improved planning and communication informed by these trends, particularly vulnerable populations affected by respiratory illnesses such as older adults, young children, immunocompromised individuals, and those with limited healthcare access. By presenting the data clearly and accessibly, the visualization supports informed decision‑making that ultimately affects community health outcomes.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

    I selected features that directly supported the goal of illustrating seasonal influenza trends across 2023–2025. Monthly influenza case counts were included because they clearly show how influenza activity rises and falls throughout each year, and using three consecutive years allows for meaningful year‑to‑year comparison. I chose to display months on the x‑axis to make the seasonal pattern intuitive and easy to interpret. At the same time, I intentionally excluded features that would distract from this central narrative. These included other communicable diseases, demographic breakdowns, geographic sub‑regions, and vaccination coverage data, as they would increase cognitive load by having too many factors displayed in the visualization or not available in the dataset. I also excluded daily or weekly case counts to avoid unnecessary noise and maintain a clear, high‑level view of seasonal trends. These decisions ensured that the visualization remained focused, interpretable, and aligned with the message I intended to communicate.
    
    > What ‘underwater labour’ contributed to your final data visualization product?

     Underwater labour included locating and verifying the correct influenza dataset from Toronto Open Data, cleaning and restructuring the data so that months were properly ordered and only influenza cases from 2023–2025 were included. The formatting was different in each file, so I had to condense the formatting to ensure it would work in python. As well, I made design decisions to ensure accessibility such using an interactive bar graph, selecting a colourblind safe palette, defining consistent fonts, and adjusting margins and layout for clarity. I also spent time testing annotation placement, refining legend labels, and ensuring that all styling choices were explicitly defined to support reproducibility. Furthermore, to increase accessibility for the audience, I included descriptive metadata and iteratively re‑running the visualization to confirm that it rendered consistently. Together, these steps ensured that the final product was accurate, accessible, reproducible for effective public health communication. 

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
