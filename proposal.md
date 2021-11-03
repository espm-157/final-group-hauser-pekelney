# Final project proposal: Examining Changes in Wildfire Burn Severity over time
Rachel Pekelney & Joshua Hauser

We are interested in examining wildfire burn severity in California. In recent years, the state has experienced increasingly intense and destructive fire seasons. Often, news coverage focuses on the area burned as a metric for describing and communicating the damage done by major fires. While areal extent is a critical metric to consider when assessing the destructiveness of fires, an additional major concern with these fires is burn severity. Burn severity affects an ecosystem's ability to recover post-fire. In the past several fire seasons, there have been examples of fires (such as the August Complex fire) that leave behind large patches of continuous high severity, which reduces a forest's ability to regenerate since seeds must travel extreme distances from surviving patches of forest. Continuous high severity patches may experience type conversion, meaning the forest will be permanently lost. 

We have obtained a dataset on vegetation burn severity for fires in California. Here is some of the metadata describing the dataset:

"This polygon feature class represents vegetation burn severity calibrated to the Composite Burn Index (CBI) for selected fires in California.
These data were created by the USDA Forest Service fire and fuels monitoring project to support monitoring of wildland fire and fire regimes. These data will allow better understanding of current fire regimes, improve the accuracy of fire perimeter data, and add spatial data on fire severity and complexity.
These data are derived from Landsat Thematic Mapper imagery. The pre-fire and post-fire subscenes were used to create a Relative Differenced Normalized Burn Ratio (RdNBR). The RdNBR is correlated to the variation of burn severity within a fire. The RdNBR data are calibrated with the Composite Burn Index (CBI). The severity ratings provided by the derived products listed below are based on the severity to vegetation."

Some questions/analysis tasks we hope to explore:
1. How big are average high severity patches in recent fires in California?
2. Is there a correlation between fire perimeter size and fire severity?
3. How does severity vary within fire perimeters? 


## Project Guidelines

### Project questions must illustrate all of the following tasks:

- Some form of data access / reading into R
- Data tidying preparation
- Initial data visualization
- Use of GitHub
- Reproducible execution with use of Travis
- RMarkdown writeup, with final submission as a nicely formatted PDF document that includes code and results.
- Overall clean and clear presentation of repository, code, and explanations.

### and at least three of the following skills (this list may be modified/extended):

- Use of at least 5 `dplyr` verbs / functions
- Writing / working with custom R functions
- Creating an R package for functions used in the analysis
- Interaction with an API
- Use of regular expressions
- Use of an external relational database
- Preparing processed data for archiving / publication
- Parsing extensible data formats (JSON, XML)
- Use of spatial vector data (`sf` package) and visualization of spatial data
- Creation of an R package
- Expansion of ggplot functions (to include more than default characteristics)
- Making layout and presentation into secondary output (e.g. .pdf, website) - should enhance presentaiton
- use lintr to clean code (checks adherence to a given style, syntax errors and possible semantic issues)

# Final Rubric 30 pts total

 - 5pts Proposal, turned in on time and with team member names, background, dataset, and 3 potential questions.

 - 10pts Polished github repository, including:
	 -  3pt updated readme with functional travis badge 
	 -  2pt passing travis build 
	 -  2pt clean and well formatted output document (html, pdf, or md with associated files). 
	 -  3pt enough supporting text that we can easily understand the project undertaken.
	 
 - 15 pts Project Substance: Objectives, Code, Visualization. Do you meet all of the required project objectives and at least 3 of the supplementary objectives.
	 - 15pts: exceptional
	 - 13pts: adequate and complete
	 - 11pts: adequate 2 questions, meeting 3 supplementary objectives
	 - 9pts: adequate 2 q, meeting 1-2 supplementary objectives
	 - 7pts: adequate 1 q, meeting 3 supplementary objectives
	 - 5pts: adequate 1q, meeting 1-2 supplementary objectives
