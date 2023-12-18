# Development of a Causal Model for Improving Rural Seniors’ Accessibility: Data Evidences
## Abstract
Seniors residing in rural areas often encounter limited accessibility to opportunities, resources, and services. This paper introduces a model proposing that both aging and rural residency are factors contributing to the restricted accessibility faced by rural seniors. Leveraging data from the 2017 National Household Travel Survey, the study examines three hypotheses pertaining to this causal model. Multiple causal pathways emerge in the data analysis, with mobility identified as a mediator in one of them. The study further identifies specific challenges faced by rural seniors, such as the reduced accessibility in reaching medical services and assisting others. These challenges stem primarily from aging and geographic obstacles that not only diminish their willingness to travel but also restrict more in the group from choosing transportation modes with higher mobility. The insights gained from this study serve as a foundation for devising effective methods to enhance transportation accessibility for seniors in rural areas.
## Causal model and hypothesis
![image](https://github.com/KELISBU/accessibility-among-seniors-in-rura-l-area/assets/130044827/85d6c82c-8039-4ace-9724-ad5045ec3fa6)

H1: Rural seniors’ accessibility is directly impacted by their inherently altered needs for accessing opportunities, resources, and services, as well as their rural residency.

H2: Reduced mobility among rural seniors stems from their constrained choices of travel modes and decreased travel willingness.

H3: The reduced mobility among rural seniors is another reason that rural seniors experience reduced accessibility.
## NHTS Dataset
This study examines the hypothesized causal relationship in Figure 1 by extracting evidences from the 2017 National Household Travel Survey (NHTS 2017), which contains a completed survey from 129,696 households and 923,572 person trips. This study defines its scope of data analysis by concentrating on:(https://nhts.ornl.gov/)  
•	Four primary travel modes: automobiles, bicycles, walking, and public transit

•	Six key travel purposes: home, work, medical service, shopping, recreational activities, and transporting someone.

•	Local travel with distance being within 75 miles.

•	Two age groups: travelers from 16 to 64 years are defined as younger adults (Yadults), and those aged 65 or older are defined as seniors.

•	Two regions of household residency: urban and rural based on home address and 2014 TIGER/Line Shapefile (NHTS 2017).
## Measurement for mobility and accessibility
**Mobility**:1.the distribution of trips by travel modes 2.travel frequency 3.travel speed 4.time to access public transit stations.  
**Accessibility**: travel distance and travel time to intended destinations as measures of accessibility. Their 75th percentiles conditioned on a specific travel purpose are used as indicators of the ease to reach an intended destination. 
## Data result and analysis
### H1:The Direct Impact of Aging and Rural Residency on Accessibility
The increased travel distance for rural seniors to reach their intended destinations, in contrast to their urban counterparts, is a contributing factor to their reduced accessibility.  
We compared rural seniors to urban seniors on their cumulative distribution functions (CDFs) of travel distance for each specific travel purpose.
**Result**:  
Rural seniors can access fewer intended destinations than their urban counterparts within the same travel distance. For example, within 15 miles rural seniors reach 52.8% of their destinations for medical services, whereas this percentage for urban seniors is 82.9%. Rural seniors experience drawbacks while accessing intended destinations than their counterparts in urban areas within the same travel time. For example, rural seniors reach 69.0% of their shopping destinations within 20 minutes, whereas urban seniors can reach 76.1%. Differences in their travel distance and travel time distributions are verified by the Kolmogorov-Smirnov (KS) test (p-value = 0).
Aging is a factor that alters the intended destinations of rural seniors, which in turn changes their accessibility.  

![image](https://github.com/KELISBU/accessibility-among-seniors-in-rura-l-area/assets/130044827/03275f86-153e-423c-956e-9939bd3476fc)
In summary, rural seniors encounter restricted accessibility for accessing medical services and assisting others. Nevertheless, it is noteworthy that they do not face equivalent limitations in activities such as returning home, work commute, shopping, or recreational pursuits. This distinction can be attributed to the special needs and willingness of this group to access some services or resources.
