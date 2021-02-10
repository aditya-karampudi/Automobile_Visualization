Introduction
With out-burst of Automobile production, many firms have released multiple variations of four-wheeler vehicles. This git is a Python based EDA project carried out of an Automobile Dataset, The attributes of interest are:	
•	Price
•	Mileage 
•	Performance 

Also, I have worked on finding the Best Car in Budget car category.

Dataset Description
The Automobile Dataset consists of various information relating to the built, engine power, make, mileage and body attributes of a car. The data types include integers, floating points, and strings.
This data set consists of three types of entities:
•	The specification of an auto in terms of various characteristics
•	Its assigned insurance risk rating
•	Its normalized losses in use as compared to other cars. 

Attribute Information:
(a)	
1. symboling: -3, -2, -1, 0, 1, 2, 3.
2. normalized-losses: continuous from 65 to 256.
3. make: alfa-romero, audi, bmw, chevrolet, dodge, honda, isuzu, jaguar, mazda, mercedes-benz,  mercury, mitsubishi, nissan, peugot, plymouth, porsche, renault, saab, subaru, toyota, volkswagen, volvo
(b)	4. fuel-type: diesel, gas.
5. aspiration: std, turbo.
6. num-of-doors: four, two.
7. body-style: hardtop, wagon, sedan, hatchback, convertible.
8. drive-wheels: 4wd, fwd, rwd.
9. engine-location: front, rear.
10. wheel-base: continuous from 86.6 120.9.
11. length: continuous from 141.1 to 208.1.
12. width: continuous from 60.3 to 72.3.
13. height: continuous from 47.8 to 59.8.
14. curb-weight: continuous from 1488 to 4066.
15. engine-type: dohc, dohcv, l, ohc, ohcf, ohcv, rotor.
16. num-of-cylinders: eight, five, four, six, three, twelve, two.
17. engine-size: continuous from 61 to 326.
18. fuel-system: 1bbl, 2bbl, 4bbl, idi, mfi, mpfi, spdi, spfi.
19. bore: continuous from 2.54 to 3.94.
20. stroke: continuous from 2.07 to 4.17.
21. compression-ratio: continuous from 7 to 23.
22. horsepower: continuous from 48 to 288.
23. peak-rpm: continuous from 4150 to 6600.
24. city-mpg: continuous from 13 to 49.
25. highway-mpg: continuous from 16 to 54.
26. price: continuous from 5118 to 45400.


The variables have been segregated as below.

![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture19.png)
            
            
            
### Price Analysis
From the graph it is clear that the price has varied mainly by three segments. Hence I have classified as low price segment, medium price segment and premium cars.
 
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture20.png)
 
 Going in-depth we can find that the relation between the price and other attributes.
 As the engine sixe increases the price increases
 The mileage decreases price increases
 The horse power and price are directly co-related
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture2.png)
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture3.png)
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture4.png)
 
 The boxplot of price and the drive distribution reveals that 4-wheel-drive vehicle are costliest followed by front-wheel drive and then rear wheel drive
 
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture5.png)
 
 The price range based on body style shows that the hard-top and convertible are priceiest and are in same price range. Where as hatchback are cheapest of all
 
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture6.png)
 
 
 ## Perfoemance Analysis
 
 Classification of Cars Based on Engine Power
 
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture21.png)
 
 
 Average Peak RPM Comparison on Wheel Drive
 
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture8.png)
 
 Factors Influencing & Influenced by the Engine Power
 
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture9.png)
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture10.png)
 
 
 ## Mileage Analysis
 Mileage Comparison of Cars
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture11.png)
 
 Mileage Comparison With Different Fuel Systems
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture12.png)
 
 Mileage Comparison With Other Attributes
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture13.png)
 
 ## Best Budget Car  Analysis
 
 Cars Qualifying for The ‘Budget Car’ Category
 
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture18.png)
 
 Feature Analysis of The Qualified Cars
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture15.png)
 
 Feature Analysis of The Qualified Cars
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture16.png)
 
 Final qualifiers
 ![alt text](https://github.com/aditya-karampudi/eda_car_dataset/blob/master/images/Picture17.png)
            
Please refer the notebook to have look on all the analysis.




