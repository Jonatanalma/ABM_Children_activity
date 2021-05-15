# An agent-based model of children's physical activity in an urban environment

An agent-based model (ABM) that explores how changes to outdoor play, school-based activities and active travel affect children’s physical activity (PA). Unique to this model is the ability to represent the complexity of multiple interdependent levels including built and social environment, individual characteristics, constraints of time/space, and policy measures, which influence PA. 

The ABM generates a synthetic population of agents representing 9-11 year-olds residing in the city of Glasgow, characterised by socio-economic demographics consistent with census data. The urban environment is represented by geospatial data layers, including land use, houses, schools and street networks. Agents follow a daily schedule: attending school, formal sport, outdoor play and meeting with friends. Agents’ decisions regarding the location of an activity and travel mode are affected by land use availability, accessibility, neighborhoods' deprivation level and street walkability. As agents engage in activities, they accumulate minutes of moderate-to-vigorous PA (MVPA). To define the proportion of time spent in MVPA per activity and site, we used empirical data of children's PA data collected in the SPACES project. 

To determine the frequency of active travel to school, each agents evaluates the distance to school and street walkability index. The algorithm used in the model to determine frequency of active travel is based on an analysis of travel to school reported by 713 Scotish children (see results in: ordered logistic regression file). 

The ABM code is written using the GAMA-Platform.
The ABM is using GIS files covering an area of 120 data zones in Glasgow, Scotalnd. 

## How to use the model?
1) Click on Code--> download zip
2) Extract the zip file
3) Open the GAMA-PLATFORM environment
4) Paste the extracted file "ABM_Children_activity-master" in GAMA under user models
5) In GAMA: Click ABM_Children_activity-master--> models-->click children_activity
6) In the right side window click the green botton called children_activity
7) The model will be uploaded and initialized (may take few minutes)
8) Click the play botton the start the model
 

