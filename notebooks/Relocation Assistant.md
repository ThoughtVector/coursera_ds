# Relocation assistant - ML based helper for those looking to relocate to Los Angeles County

## Business Problem  
People often relocate to a different area for various reasons. The reason why people move are varied, and the following graphics shows some of the top reasons.

![us-moving-reasons-graphic](moving-reasons.jpg)

[source: [us-moving-statistics-for-2019](https://www.moving.com/tips/us-moving-statistics-for-2019/)]

[This article based on a survey](https://www.allied.com/infographic/job-relocation-survey) outlines more reasons and factors that govern the job related relocation, and what people look for.

As part of their relocation plans it becomes important for people to explore the area. When people live far away from the places to which they are seeking relocation, it becomes expensive to undertake travel and personally explore the area. Even though the final decision will require them to travel, it will make a lot of sense for them to use a resource (like an application or a human consultant) that can provide useful suggestions about the area and the neibourhood. 

For example, people may want to find out places closer to the schools or shopping malls, or beaches. Individual requirements vary, and hence it will be helpful to have an application that can suggest areas, and also indicate possible cities / neighbourhoods to look for, from the standpoint of efficient exploration. 

Crowd sourcing is one of the best ways to see what kind of people relocate and for what reasons, and how their reasons influence the choice of their neighbourhoods. Some of the criteria are outlined in [this article](https://www.urbanbound.com/blog/crowdsourcing-mobility-the-most-valuable-relocation-data-is-closer-than-you-think)  

This notebook implements a subset of the requirement by pulling geographical information about LA county and adding additional data for the users to query and decide the location to visit for relocation.

This notebook, though not a full fledged application, provides a simple prototype for the analytics part of a hypothetical application. While things like persistence, deploymet, GUI are outside the scope of this exercise, the trained model in this notebook can be deployed and used with real data for a real life application. 
