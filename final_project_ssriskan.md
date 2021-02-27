
# Part 1 Outline

**Topic: How health disaprities in New York City is hindering COVID-19 recovery**

New York City was the epicenter of the COVID-19 pandemic in March 2020, resulting in the entire region expereiecing a lot of trauma. Even though the COVID situation in NYC is much more manageable, there are still some issues in some neighorbhoods that are affecting certain races due to the pandemic.

(Note: I originally wanted to do food scarcity in New York City but I decided to expand to health disaprities since it all ties in together and there was more to show)

**Call to Action**

The purpose of this story is to share what has been going on and who is currently at risk. That way, I can provide recommendations and share resources in order to donate food/money, take action, work with local organizations and educate low-income neighorbhoods, call a representative, and/or just be knowledgeable. 


# Data

**COVID DATA**

Datasource 1: John Hopkins University github
Link: https://github.com/CSSEGISandData/COVID-19

Datasource 2: COVID tracking project 
Link: https://covidtracking.com/

Datasource 3: Data USA
Link: https://datausa.io/profile/geo/new-york-ny#:~:text=The%205%20largest%20ethnic%20groups,and%2084.3%25%20are%20U.S.%20citizens.


I chose these three datasets because they are all data collected from the pandemic. Data source 1 and 2 are primary souce data that is being used for most of the visualizations in the US so I think they are reliable. Datasource 3 also contains COVID data that comes from Datasource 2 but also comes in pre-aggregated form that could be easier for the visualization. 

This is a data that measures food insecurity at the tract level. I picked these three because I think that this can be used to show how bad the pandemic got and in real time. I intend on using this data to map out how badly the pandemic is spreading across New York City. I think I might need multiple datasets because sometimes I might need a combination of information so I can merge them on Python/R. This would be the data that I can use to measure how severe it is. I imagine the data being used in 2 ways:

1. A graph of some sort to show how COVID cases are changing over time (i.e a bar graph)
2. A heat map to see where neighborhoods are getting more cases than others. Ideally this would be broken down based on neighborhood

**HEALTH DISAPARITY DATA**

Datasource 1: US Census Food Insecurity 
Link: https://www.census.gov/data/datasets/time-series/demo/cps/cps-supp_cps-repwgt/cps-food-security.html

Datasource 2: NYC Gov
Link: https://www1.nyc.gov/site/doh/covid/covid-19-data.page

Datasource 3: National Equity Atlas
Link: https://nationalequityatlas.org/

This is a data that measures food insecurity at the tract level. Can be used to better visualize the specific boroughs/areas that are experiecing health disaprities (i.e food insecurity, vaccine distribution, health hospitalization, etc..). I also added National Equity Atlas in case I need data from there to map out the differences in equiality if that is difficult to do from NYC Gov


# Sketches
I thought using Shorthand would be good to show how the pandemic played out in COVID-19 and how inequality was apparent throughout all of it. I was going to break up the story into two parts. First part would be about the rise of the pandemic in NYC,its impact while it is the epicenter, and illsutrate why certain neighborhoods are hit harder. The second part would be after restrictions were put into place and the road to herd immunity to show that even recovery is still not consistent throughout. 

**Tale of 2 cities: How Inequalities are Worsening COVID-19 in New York City**

**Part 1 1: The rise of the pandemic in New York City** 
Basic overview: New York City was considered the epicenter of the pandemic. The number of cases grew rapidly, which I can use by visualizing the graph that was for New York City

(line graph of COVID cases)

"This virus is the great equalizer" -Andrew Cuomo, Governor of New York State (said 03/21/2020)

While Cuomo was insisting that virus doesn't consider factors such as race, religion, economic class, and gender, certain races were getting more infected than others. 

(bar graph of % of race infected or a line graph of new infections broken down by race) 

Why is this happening? 

Income and COVID cases are associated with one another
(2 heat meap of New York City side by side. The left one would have based on income and the right one would be based on concentration of cases) 

Worstly impacted neighborhoods are low income and non-white
(bubble graph of the top 5 worstly affected neighborhoods to show that it's predominated brown/black communities) 

PoC are less likely to have a car --> meaning that they are commuting around NYC compared to their white counterparts 
(line graph showing the %) 

**Part 2: June 2021 - Present: The road to herd immunity is shaky** 

Despite cases dropping, there are still barriers faced by minorities (who are still the most impacted) 

Minorities are uninsured (and typically don't know that testing is covered) 
(multiple bar graph showing the race) 

Whites are more likely to to be vaccinated than any other race even though they are not impacted the most
(insert infographic) 

Which is almost contradictory as PoC are considered front line workers and cannot stay at home
(insert infograph)

**Recommendation** 

- Volunteer for local community outreach to raise awareness of resources low-income areas can use


# Method and Medium

The medium I will likely be using for this project is Shorthand. Since what I have in mind is a timeline of the pandemic from March 2020 - present day and how differents areas were impacted, the idea of the viewer able to scroll down and see it as pandemic progresses. Based on the outline stated above, I will likely first build the visuals to see how they look and make sure they look how I imagine using Flourish and Tableau. At this point, I will see if the visualizations best represent the data the way I imagine them too. If they do not and there is a better way to make it flow, I may switch up the visualization. 

After the visualizations, I will search for photos and backgrounds for the visualizations. Only after I manage to gather the appropiate media, then I will start building it on shorthand and adding the final touches. 


