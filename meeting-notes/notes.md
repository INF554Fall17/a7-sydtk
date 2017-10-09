# INF 554 project idea

## Global energy statistic
The data is from BP company and contains all energy type from 1950 to 2016.
Here is the statistic resource:
http://www.bp.com/en/global/corporate/energy-economics/statistical-review-of-world-energy/downloads.html

Also, it could combine the data to the country’s population in order to find how much energy each person consumes.
About the country’s population, we could look at the UNdata.org
http://data.un.org/Data.aspx?q=population&d=PopDiv&f=variableID%3a12

***

### Note on 09.16 Discussion Summary

Preparation before next discussion (09/23)

1. collect related index datasets (on UNdata?)
2. brain strom: what data attributes/ visualizations are suitable for us.



![image](https://github.com/INF554Fall17/a7-sydtk/blob/master/meeting-notes/draft.jpg)

---

### Note on 09.24 Discussion Summary

#### Parts still up in the air:
1. How to present comparison among countrues(facet? visualization?)
2. How to present the interaction between energy consumption and other indices.
3. Sources of indices.

#### Parts discussed today:
1. (World Cartogram): energy consumption > (Continent thematic map) : energy type
2. (Country) : energy type
- Non-renewable resource
  - Nuclear
- Renewable resource
  - Solar
  - Wind
  - Hydro

Compare the proportion of each type in total energy production and consumption > piechart

3. (optional) timeline

#### Tasks:
- Data collection and organization -> I-Hui Huang(@ihuihuan)
- Cartograph -> Yi Chen(@chen310)
- Piechart -> Ching-Ju Hsieh(@chingju)

---

### Note on 10.07 Discussion Summary

#### Some Presentation Questions Answered
Discussion on project pitch

Lead with 10 words on why you chose this project
- Figure out how energy consumption affect human's life

Why is your project interesting?
- In this project, we do not only show energy data, but compare them with multiple kinds of social indicators and analyze them as well.

Who is the audience?
- Potential Audience: Policy makers, NGO members , anyone who is interested in environmental issues.

Why is your visualization important?
- Our visualization could give policy makers or NGO members some trend and relationship so that they could set up their action or create a new policy.

How is your visualization useful?
- Our visualization will make the comparison of temporal and spatial relations easier on both global scale and by country, facilitating the audience to locating the key issues.

What are you telling with your visualization? What is the story?
- What are you telling: the comparison between social indicators (e.g. GDP, Life Expectancy, etc) and energy data in different countries

- Stories: How significantly the energy (non-renewable energy/renewable energy) affects a country's national capabilities and citizen's living standard.

---

### Note on 10.08 Discussion Summary

#### Other Questions Answered

How do you plan to use interactive visuals?
1. Use Choropleth/Cartogram to show spatial distribution pattern in different scale, various kinds of charts (piechart, linechart) to show the information within a certain country/region/continent.
2. interactions to switch the spatial scales (between map and cartogram)
3. interactions between map objects and charts
4. do spatial query to filter spatial information

What are your design considerations?
- We consider providing friendly UI, intuitive color and layout chosen to let users focus on core information,  and follow the critique rules from Cairo to review our visualization

What are the components that make your visualization cool?
- Interactions between map and charts
- Dynamically changed color themes in choropleth map

How does your visualization compare to what others have done?
- Most of visualization just lists the energy consumption during a period of time. But we are more focus on these energy consumption has any influence or relation on human lifes.

What are the technologies you plan to use?
- webDev: Bootstrap(UI), AngularJS
- visualization: D3(chart), leaflet(map)
- backend: ArcGIS online

How are you going to design, build, and evaluate?
- design: make up blueprint for the visualization, polish it through several weekly meetings.
- build: set up development environment, gradually implement components in our blueprint.
- evaluate: test every components to see if it work. invite people to use it and give out feedback

What are your deliverables?
- Working demo
- Video
- Paper
- Presentation

How do you work together?
- Visualization
    - interactive map: @chen310
    - charts and graphs (energy alone): @ihuihuan
    - charts and graphs (comparison between energy and social indicators): @chingju
- Data Cleaning & User Survey: @ihuihuan
- Web Layout: @chen310 @chingju

What is your timeline?
- Followed the timeline Prof. recommended.