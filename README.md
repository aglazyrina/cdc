# CDC - SVI. Anna Glazyrina, McLeod Brown, Nils Menz

## Final product

Link to the interactive Tableau Dashboard

https://public.tableau.com/app/profile/anna.glazyrina/viz/CDCSVI-AnnaG_McLeodB_NilsMenz_/Countyview?publish=yes

## Inspiration

 

**Social vulnerability** refers to the potential negative effects on communities caused by external stresses on human health. A number of factors, including poverty, lack of access to transportation, and crowded housing may weaken a community's ability to prevent human suffering and financial loss in a disaster. We wanted to use the Centers for Disease Control and Prevention's Social Vulnerability Index to gauge how different tracts in North Carolina have changed from 2014 to 2018 in regards to how prepared they are for hazardous, potentially-catastrophic events.

 

## What it does

 

Our dashboard shows the change in different tracts of land in North Carolina in regards to their preparedness for a hazardous event, such as tornadoes, disease outbreaks, or other harmful occurences.

 

## How we built it

 

We first combined all of the Social Vulnerability Index (SVI) data from 2014, 2016, and 2018. We then calculated the difference in the four summary theme ranking variables (along with the overall tract summary ranking. These specific variables are:

 

RPL_THEME1 (Socioeconomic trends)

RPL_THEME2 (Housing Composition and Disability)

RPL_THEME3 (Minority Status & Language)

RPL_THEME4 (Housing & Transportation)

Overall tract summary ranking variable (RPL_THEMES)

 

We then plotted these variables on a map of North Carolina where we were then able to show how a tract's SVI changed from 2014 to 2018. This is intended to show how a tract's vulnerability rankings may be improving or worsening over the years. This could be used to identify more at-risk tracts and could give local leaders and environmental advocates reason to target these tracts for action.
We also calculated differences for percentage estimates for all vulnerability factors. This allows the user to further explore the reasons for changes in SVI over time.


## Challenges we ran into

 

Challenges we ran into were mainly focused around Tableau and familiarizing ourself with the tool. While it became easier to use with practice as most things tend to be, it was more difficult to get started with the tool as it is not _as_ open-sourced as R and Python.

 

## Accomplishments that we're proud of

 

We're proud of the idea we came up after a bit of initial debate. Additionally, we're proud of how we've become more adept at working with Tableau, including creating custom tool tips, time-lapses, and identifying overall trends using Tableau. Moving forward, we all will be using Tableau more frequently in our day-to-day work.

 

## What we learned

                                                       

We learned certain tracts in North Carolina are more prepared for potential social disasters than others! But we also learned how we can use Tableau to drill down macro-level data to a micro-level. Building out an interactive map where the user can choose which data they want to view and when, allowing them to take away their own insights in the process, was very rewarding.

 

## What's next for SVI exploration

 

Moving forward, we would like to build a similar project out for the entire United States along with a ranking component where those tracts most and least at-risk for a social disaster are identified.
