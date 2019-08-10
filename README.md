# Vessel Geo Monitoring

## Report

### Individual Report 4000

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

2. Subject area - visualisation helping decision making 1400 (8/10)  
2-1 What is data visualisation? Why use? 200  
    -different kind of visualisation  
    -the use in business area  
2-2 Current status of visualisation in marine area 1000  
    -some websites pros and cons  
    -analysis  
2-3 future development 200  
  
3. Working process - user interface 1400 (8/9)  
3-1 Developing tools used & considered 400  
    -html or power BI  
    -bing maps API and d3.js  
    -front-end framework - bootstrap, react, vue  
3-2 Fleet Page 500  
    -what to deliver  
    -data selection  
    -UX design
    -result  
    -to improve/ link to subject area  
3-3 Vessel Page 500  
    -what to deliver  
    -data selection  
    -UX design
    -result  
    -to improve/ link to subject area 
  
4. Reflection 400 (8/11)  
4-1 project (what you learned during the project) 200  
    -project management  
    -brainstorming  
    -persona  
    -story boarding  
    -use case  
    -scenario  
    -hypothesis  
    -actual webpage development -local server or github  
4-2 interaction with industry partner (the relation between the academic programme and the project) 200  
    -slack  
    -difficulties in developing

5. Conclusion 400 (8/11)  

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