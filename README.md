# INF 554 Assignment 7 -- Project Pitch

#### Lead with 10 words on why you chose this project

- Figure out how energy consumption affect human's life

#### Why is your project interesting?

- In this project, we do not only show energy data, but compare them with multiple kinds of social indicators and analyze them as well.

#### Who is the audience?

- Potential Audience: Policy makers, NGO members , anyone who is interested in environmental issues.

#### Why is your visualization important?

- Our visualization could give policy makers or NGO members some trend and relationship so that they could set up their action or create a new policy.

#### How is your visualization useful?

- Our visualization will make the comparison of temporal and spatial relations easier on both global scale and by country, facilitating the audience to locating the key issues.

#### What are you telling with your visualization? What is the story?

- What are you telling: the comparison between social indicators (e.g. GDP, Life Expectancy, etc) and energy data in different countries

- Stories: How significantly the energy (non-renewable energy/renewable energy) affects a country's national capabilities and citizen's living standard.


#### How do you plan to use interactive visuals?

1. Use Choropleth/Cartogram to show spatial distribution pattern in different scale, various kinds of charts (piechart, linechart) to show the information within a certain country/region/continent.
2. interactions to switch the spatial scales (between map and cartogram)
3. interactions between map objects and charts
4. do spatial query to filter spatial information

#### What are your design considerations?

- We consider providing friendly UI, intuitive color and layout chosen to let users focus on core information,  and follow the critique rules from Cairo to review our visualization

#### What are the components that make your visualization cool?

- Interactions between map and charts
- Dynamically changed color themes in choropleth map

#### How does your visualization compare to what others have done?

- Most of visualization just lists the energy consumption during a period of time. But we are more focus on these energy consumption has any influence or relation on human lifes.

#### What are the technologies you plan to use?

- webDev: Bootstrap(UI), AngularJS
- visualization: D3(chart), leaflet(map)
- backend: ArcGIS online

#### How are you going to design, build, and evaluate?

- design: make up blueprint for the visualization, polish it through several weekly meetings.
- build: set up development environment, gradually implement components in our blueprint.
- evaluate: test every components to see if it work. invite people to use it and give out feedback

#### What are your deliverables?

- Working demo
- Video
- Paper
- Presentation

#### How do you work together?

- Visualization
    - interactive map: @chen310
    - charts and graphs (energy alone): @ihuihuan
    - charts and graphs (comparison between energy and social indicators): @chingju
- Data Cleaning & User Survey: @ihuihuan
- Web Layout: @chen310 @chingju



#### Data Source

**Energy Data :**

BP Statistical Review of World Energy June 2017

https://www.bp.com/content/dam/bp/en/corporate/excel/energy-economics/statistical-review-2017/bp-statistical-review-of-world-energy-2017-underpinning-data.xlsx

**Social Indicators:**

UNData

http://data.un.org/

UNDP (United Nations Development Programme)

http://www.undp.org/content/undp/en/home.html

**Image Resource:**

Flaticon

https://www.flaticon.com

Iconfinder

https://www.iconfinder.com/
