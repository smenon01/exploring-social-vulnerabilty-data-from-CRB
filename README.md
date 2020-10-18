# Social Vulnerabilty Data from Climate Ready Boston

## Overview
This project was focused on conducting exploration on a particular dataset week-to-week, in this case the Social Vulnerabilty Dataset available from [Climate Ready Boston](https://www.boston.gov/departments/environment/climate-ready-boston), a city initiative started in 2016 focused on exploring possible impacts of climate change to the city, identifying and quantifying vulnerabilities, and developing solutions and policies to better prepare the city to mitigate potential impact and remain resilient. Every module focuses on conducting analysis on the dataset and/or creating new measures or modifications, as well as providing documentation. 

The Social Vulnerability dataset splits Boston into 180 Census tracts, and contains counts of 7 socially vulnerable groups (such as children, people of color, individuals with disabilities, etc.) within each tract. Social vulnerability is defined by CRB as “the disproportionate susceptibility of some social groups to the impacts of hazards, including death, injury, loss, or disruption of livelihood”. In addition, the dataset has variables related to housing units, tract size, and geographic location (including 2010 Census state and tract identifiers). This dataset can be used to analyze and map concentrations of vulnerable populations within and between neighborhoods in Boston.

### Dataset General Facts
- The neighborhoods in Boston (Name) with the most Census tracts are Roxbury (23), Dorchester (19), and Roslindale (18).
- The tract with the highest percentage of low to no income residents (Low_to_No/POP100_RE) is located in Roxbury (74.4%).
- South Boston contains 4 out of 5 of the tracts with the lowest percentages of people of color (POC2/ POP100_RE), all under 10%. South Boston consists of 7 tracts.
- The overall percentage of people with disabilities (TotDis) in the city of Boston is 11.4%.
- The socially vulnerable groups with the highest counts across the city are: 327,784 people of color; 239,246 residents with limited English proficiency (LEP); and 236,938 residents with medical illnesses (MedIllnes).
- The largest-sized tract is located in East Boston. The tract is 77,303,253.6 square feet (or 1774.6385 acres), yet the corresponding total population is only 389 people.
- The tract with the largest percentage of limited English proficiency residents is in Jamaica Plain (90.5%), but the neighborhood with the largest LEP percentage is actually the Harbor Islands (67.5%).
- Roslindale has a tract with the highest percentage of adults over the age of 65 (OlderAdult), at 66.7%, but also has one of the 5 tracts with 0% older adults.
- The most populated neighborhood in Boston is Roxbury, with 77,812 residents. The least populated neighborhood is the Harbor Islands, with only 535 recorded residents.


## Interesting Visualizations
*Socially Vulnerable Populations across Boston*

Across the city of Boston, people of color are overwhelmingly the largest represented socially vulnerable group, making up over half of the population. In contrast, older adults and residents with disabilities are generally less represented in the city. It may be important to consider overall city percentages when determining how to allocate resources in ways that will result in the most impactful solutions. Below is a plot that shows the composition of the 7 defined socially vulnerable populations within the city.

*Socially Vulnerable Populations by Neighborhood*

Considering the city percentages above, not surprisingly, most neighborhoods within Boston have high percentages of people of color; in particular Roxbury and Mattapan have populations that are almost entirely composed of people of color. Roxbury also has the tract with the highest percentage of low to no income residents (74.4%), so it is understandable that it is the neighborhood with one of the highest percentages as well. Interestingly, the Harbor Islands is the only neighborhood with no representation of children. The plot below illustrates how each neighborhood breaks down by percentage of each socially vulnerable group. We observe that many neighborhoods populations are above and below 100%, which demonstrates that socially vulnerable populations make up large (but not entire) parts of most neighborhoods and that there is a lot of overlap between socially vulnerable groups (i.e. many people that are in one group of probably also represented in other groups); these overlaps are also important considerations when designing effective solutions to climate change.
