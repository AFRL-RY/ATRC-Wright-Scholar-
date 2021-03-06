<!-- TOC -->

- [ATRC Wright Scholar](#atrc-wright-scholar)
    - [Wright Scholar Program](#wright-scholar-program)
    - [AFRL Center](#afrl-center)
- [ATRC - Wright Scholar - Summer 2017](#atrc---wright-scholar---summer-2017)
    - [AFRL-RYAT](#afrl-ryat)
        - [Explore Coarse 3D Reconstruction Path Planning](#explore-coarse-3d-reconstruction-path-planning)
        - [Girder Data Management Query Web Client](#girder-data-management-query-web-client)

<!-- /TOC -->
# ATRC Wright Scholar

## Wright Scholar Program
***[External Web Page Link](http://www.wpafb.af.mil/Welcome/Fact-Sheets/Display/Article/985968/wright-scholar-research-assistant-program/)***

The Wright Scholar Research Assistant program is an Air Force Research Laboratory (AFRL) initiative designed to expose high school juniors and seniors to various disciplines of engineering and science in an effort to further their interest in future STEM career options. Wright Scholars are employed as full-time, paid interns for 9 weeks during the summer. A panel of scientists, engineers, and educators will use a “blind” review system to select the students (names and other personal data are removed from applications prior to review to prevent biases). Students are competitively selected to work on a research project under the guidance of their assigned mentors. They also participate in weekly workshops, lectures, and tours to expand their knowledge of potential science and engineering career fields. At the end of the program, Wright Scholars are required to present their project work to their peers and mentors, and a program certificate is awarded.

***Benefits:***
1. Exciting research topics
2. Technical training
3. Mentorship from experienced AFRL scientists and engineers
4. Opportunities to tour AFRL laboratories
5. Networking through social events
6. Competitive stipend rates

## AFRL Center
The AFRL ATR Center Summer Program is a collaborative research experience for university professors, students, industry, and  government to work together to solve challenging Air Force problems in sensor processing and exploitation, including object 
detection, tracking and recognition. Students work with an Air Force mentor at Wright Patterson Air Force Base or 
nearby Wright State University, and have access to outstanding computing resources, measurement and modeling tools, and data.
```
Air Force Research Lab
AFRL/RYA
2241 Avionic Circle
Wright Patterson AFB, OH, 45433
```

# ATRC - Wright Scholar - Summer 2017

## AFRL-RYAT

### Explore Coarse 3D Reconstruction Path Planning
***[GitHub Link](https://github.com/AFRL-RY/Explore-Coarse-3D-Reconstruction-Path-Planning-ATRC-Summer-2017)***


View planning is the process of planning or selecting a set of images for 3D reconstruction. In many cases this process can improve the quality of the resulting 3D models, and reduce the number of images required, which in turn reduces the processing time. The objective of this project is to explore the application of view planning algorithms to SUAS platforms. The projected consist of several stages, each contingent on the success of the previous stage:
  * Test view planning algorithms on existing public data sets
  * Test view planning algorithms on non-public release data
  * Extend algorithms to produce coarse 3D reconstructions in flight and re-plan
  
Martin, R.A.; Blackburn, L.; Pulsipher, J.; Franke, K.; Hedengren, J.D. Potential Benefits of Combining Anomaly Detection with View Planning for UAV Infrastructure Modeling. Remote Sens. 2017, 9, 434.

Martin, R.A.; Rojas, I.; Franke, K.; Hedengren, J.D. Evolutionary View Planning for Optimized UAV Terrain Modeling in a Simulated Environment. Remote Sens. 2016, 8, 26.
#### Mongo Aggregation
Optional subproject that adds a direct restapi to mongo for use of aggregation calls. 
***[GitHub Link](https://github.com/AFRL-RY/Girder-Data-Management-Query-Web-Client-Mongo-Aggregation)***

### Girder Data Management Query Web Client
***[GitHub Link](https://github.com/AFRL-RY/Girder-Data-Management-Query-Web-Client-Wright-Scholar-Summer-2017)***

The objective of this project is to provide a web interface to query a Girder instance based on a selected geospatial region and then filter the results based on available metadata fields. The interface provides a map where the user can select a region (using a rectangle, polygon, or point+radius). It then display the results and allow for filtering of data. 
1. Functional on isolated networks or in a public cloud (ex. AWS)
2. Resizable and movable controls
3. Authentication through Girder
4. Filtering works using ANY metadata field
5. Web interface – accessible from any computer with browser
6. Heatmap showing concentration of available imagery
7. Region selection & search in region
8. Display search results in a table (supports paging)
9. Filter search results and heatmap display using metadata


