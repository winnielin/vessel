# Vessel Geo Monitoring

## Report

### Individual Report 3600

1. Intro 400  
1-1 Big data & blockchain (Hook + Technical area) 100  
1-2 Marine insurance (Business context + Problem statement) 150  
1-3 Rationale + Thesis Statement + Limitation (Structure) 150  
    -Possible topics  
      --marine insurance claims  
      --lack of competition and dynamic pricing  
      --the effects of big data on insurance  
      --modelling risk  
    -Data science working process  
      --Business Problem/ Use Case  
      --Data Discovery (Collection, cleaning & mining) & difficulty  
      --Production Solution  

2. Subject area - Data visualisation on helping decision making 1000  
2-1 What is data visualisation? Why use? 150  
    -different kind of visualisation 50   
    -the use in the business area 100  
    (the importance of using the notification to transmit information to the user then to make value)  
2-2 Current status of visualisation in marine area 750  
    -AIS data 100   
    -weather visualisation 100  
    -some websites pros and cons (BigOceanData & MarineTraffic) 200  
    -big data + visualisation 150  
    -situational awareness 50  
    -the detection of anomalous maritime behaviour 150  
2-3 future development 100  
    -4D 50  
    -conclusion 50  
    
3. Working process - user interface 1500  
3-1 Developing tools used & considered 400  
    -html or power BI  
    -bing maps API and d3.js  
    -front-end framework - bootstrap, react, vue  
3-2 Fleet Page 600  
    -what to deliver 100  
    -data selection 150  
    -UI design 100  
    -result 200  
    -to improve/ link to subject area ??  
3-3 Vessel Page 500  
    -what to deliver 50  
    -data selection 50  
    -result 350  
    -to improve/ link to subject area ??  
  
4. Reflection 400  
4-1 project (what you learned during the project) 200  
    -project management  
    -brainstorming  
    -persona  
    -storyboarding  
    -use case  
    -scenario  
    -hypothesis  
    -actual webpage development  
    -local server or Github  
4-2 interaction with industry partner 100  
    (the relation between the academic programme and the project)  
    -slack  
    -difficulties in developing

5. Conclusion 300  

## Coding To Do

### Fleet Page  

1. show weather info - implement a tile layer to the map (weather radar map) -> how to change location 
2. fake dropdown list - CustomOverlay Class (ref:https://www.shipmap.org)  
3. planned vessel event button function - (approval & reject, additional premium)  
4. actual vessel event - clear map  
5. remove specific polygons -> layer?  
6. a block with political and piracy events  
7. how to use zone entry & exit data?  

### d3.js chart block

1. zone chart strange???  
2. year 2018,19 change to slider  
3. solve the size of svg (always minimize sidebar)  
  
~~1. select vessels from the table then add data into chart~~  
~~2. age slider, vessel type & shipping company selector~~  
~~3. valuation chart - stacked bar & line~~  
~~4. mileage + port visits + ??~~  
~~5. restricted zone visits - by zone -> total accepted, change more/less~~  
~~6. some claims, premium, value information message by side~~  

### Vessel Page

1. remove heatmap
1. zone visits graph put somewhere for kimi  
2. past important events block  
3. using queue.js to show all JWC zones  
4. dropdown list for all vessels  

#### Bing Maps  

1. how to untick route then remove only specific polyline from the map (different layer)    
2. direction for vessel  
  
~~1. check how many zones a vessel crossed by checking points from the route~~  
~~2. how many times planned schedule to cross the zone -> show zone + alert (zone call)~~  
~~3. current location generate alert (if huge deviation -> reason)~~  

#### Template  

~~1. receive vessel name then read csv file and show the basic information of the selected vessel~~  
~~2. notification block read from csv file~~  
~~3. date selector (a date or a period)~~  