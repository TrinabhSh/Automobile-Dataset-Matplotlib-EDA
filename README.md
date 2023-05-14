 # Automobile Dataset EDA

![Automobile | Definition, History, Industry, Design, & Facts | Britannica](https://cdn.britannica.com/16/126216-050-D9865939/Automobiles-John-F-Fitzgerald-Expressway-Massachusetts-Boston.jpg)



## About the Dataset

This dataset consist of data From 1985 Ward's Automotive Yearbook. Here are the sources

1) 1985 Model Import Car and Truck Specifications, 1985 Ward's Automotive Yearbook.  
2) Personal Auto Manuals, Insurance Services Office, 160 Water Street, New York, NY 10038  
3) Insurance Collision Report, Insurance Institute for Highway Safety, Watergate 600, Washington, DC 20037

## Content

### Content

This data set consists of three types of entities: (a) the specification of an auto in terms of various characteristics, (b) its assigned insurance risk rating, (c) its normalized losses in use as compared to other cars. The second rating corresponds to the degree to which the auto is more risky than its price indicates. Cars are initially assigned a risk factor symbol associated with its price. Then, if it is more risky (or less), this symbol is adjusted by moving it up (or down) the scale. Actuarians call this process "symboling". A value of +3 indicates that the auto is risky, -3 that it is probably pretty safe.

The third factor is the relative average loss payment per insured vehicle year. This value is normalized for all autos within a particular size classification (two-door small, station wagons, sports/speciality, etc…), and represents the average loss per car per year.

Note: Several of the attributes in the database could be used as a "class" attribute.

## We will structure the code as follows

1.  Loading the data
    
2.  Preparing the data
    
3.  Exploratory Data Analysis
    
5.  Final Analysis of the model

## Findings
![Statistic GIFs - Get the best gif on GIFER](https://i.gifer.com/origin/71/711557abfeed55bc0ebc5185168147c6.gif)

We have taken some key features of the automobile dataset for this analysis and below are our findings.

1.  Toyota is the make of the car which has most number of vehicles with more than 40% than the 2nd highest Nissan
2.  Most preferred fuel type for the customer is standard vs trubo having more than 80% of the choice
3.  For drive wheels, front wheel drive has most number of cars followed by rear wheel and four wheel. There are very less number of cars for four wheel drive.
4.  Curb weight of the cars are distributed between 1500 and 4000 approximately
5.  Symboling or the insurance risk rating have the ratings between -3 and 3 however for our dataset it starts from -2. There are more cars in the range of 0 and 1.
6.  Normalized losses which is the average loss payment per insured vehicle year is has more number of cars in the range between 65 and 150.
 1.  Price is more correlated with engine size and curb weight of the car.
7.  Curb weight is mostly correlated with engine size, length, width and wheel based which is expected as these adds up the weight of the car.
8.  Wheel base is highly correlated with length and width of the car.
9.  Symboling and normalized car are correlated than the other fields.
10. The most expensive car is manufacture by Mercedes benz and the least expensive is Chevrolet.
  11. The premium cars costing more than 20000 are BMW, Jaquar, Mercedes benz and Porsche.
    12. Less expensive cars costing less than 10000 are Chevrolet, Dodge, Honda, Mitsubishi, Plymoth and Subaru.
   13. Rest of the cars are in the midrange between 10000 and 20000 which has the highest number of cars.
14. As horsepower and engine size increases, price also increases.

 15. Most vehicles in the lot are forward wheel drive.


# FIN










