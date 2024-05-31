# Practical Instances
The 240 instances are modified instances from Krebs et al. (2021). 

The name of each file consists in four elements:
- the instance number
- the number of customers
- the number of boxes
- the number of item types

The structure of an instance is as follows:
1. the name of the instance
2. the number of customers
3. the number of boxes
4. the number of item types
5. the number of vehicles (fleet size)
6. description of the vehicle type (weight, length, width, height) and the maximum working (driving, waiting, service) duration of the driver
7. customers information: id of the customer - x location - y location - total demand - the beginning of the time window - the end of the time window - the service duration
8. items information : type id - length - width - height - mass
9. demands per customers: the customer id followed by the box type and the associated quantity


**References**

Krebs C, Ehmke JF, (2021). Axle Weights in combined Vehicle Routing and Container Loading Problems. EURO Journal on Transportation and Logistics, Volume 10, ISSN 2192-4376, DOI: 10.1016/j.ejtl.2021.100043,
URL https://www.sciencedirect.com/science/article/pii/S2192437621000157 
