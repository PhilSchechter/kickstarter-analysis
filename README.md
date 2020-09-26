# Kickstarting with Excel

## Overview of Project

### Purpose

The client would like to use a Kickstarter campaign to raise funds to put on a play. Armed with historical data on Kickstarter campaigns, we attempt to find strategies that may boost the success of this campaign, by identifying common characteristics of successful campaigns


## Analysis and Challenges

This analysis looked at results relative to launch date and fundraising goal.

Challenges included the variety of projects in the dataset. The analysis presented concentrates on Theatre related projects, and plays in particular, as most directly relevant to this process. A deeper dive into the wider could reveal wider insights that have not been captured in this work.


### Analysis of Outcomes Based on Launch Date

For this analysis, we looked at theatre projects (parent category) with the launch dates grouped by calendar month – this grouping showed the clearest pattern, leading to the observations in the “results” section below. Note that the spreadsheet tab “Outcome Based on Launch Date” allows the user to look at other parent categories by using the drop down list in cell B2; however, the Theater observations had a distinct pattern most likely to be relevant to this project.

### Analysis of Outcomes Based on Goals

We grouped projects into buckets based on goal ranges, and calculated the percentage in each project that were successful, failed, or canceled. We are presenting results for the “plays” subcategory, but the user can extend this to any subcategory using the drop-down menu on cell L3.


### Challenges and Difficulties Encountered
Different types of projects showed different patterns along the dimensions we tested. The spreadsheet provided in this analysis provides the options to choose and view other project types, but we limited our analysis to theatre projects (start month) and plays (amount)

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

[Outcomes Based on Launch Date]( /resources/Theater_Outcomes_vs_Launch.png)

This analysis shows that in the spring, a kickstarter’s mind turns to theatre– May has the highest number of campaigns starting, and (not explicitly shown on the chart, but can derive from the numbers) the best ratio of successful to failed campaigns, closely followed by June. 

Fall and winter are not good times to launch these products.

As a point of interest: this result is specific to theatre – other types of projects did not necessarily follow this pattern.


- What can you conclude about the Outcomes based on Goals?

[Outcomes Based on Goals](/resources/Outcomes_vs_Goals.png)

There is a Talmudic adage: If you have grabbed hold of too much, you haven’t grabbed it. This seems to be borne out by the Kickstarter data pertaining to plays. We see the highest success rate in small projects, under $5000. 

Just looking at success percentages, there is a pleasant spike for projects between $35,000 and $50,000, but the total numbers of projects at that level is small, more in the range of anecdote than data 


- What are some limitations of this dataset?
We are drawing conclusions using some of the information presented in this dataset. There may be other interesting factors that are not included here – for example, there is no information about the age/gender/educational level of the person or entity launching the campaign, and how many of the contributors came in purely from Kickstarter as opposed to having another relationship with the project sponsor (e.g. family, fraternity/sorority affiliations, etc.)

- What are some other possible tables and/or graphs that we could create?
Some other items we could look at: Do long words in the blurb have an impact on results? We could also look at the length of the campaign vs results, whether being a “staff pick” matters, and if there has been a change in success rate over the years in the table.
