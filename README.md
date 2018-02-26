# Study of US Craft Beer and Breweries

## The purpose of this repository is to store files for Case Study 1 of MSDS: 6306 - Doing Data Science at SMU

### Authors:  David Stroud, Cory Thigpen, Korey MacVittie, and Stacy Conant
### Date: Feb 2018

## **Introduction**
The United States is currently enjoying a surge in popularity, variety and availability of craft beer, which is beer that is typically brewed using traditional, non-mechanized methods at smaller breweries. From Alaska to Maine, craft beer has proliferated, offering, not only delicious libations, but also ample data to examine. The report that follows will conduct an analysis of brewery data collected from all 50 states and Washington, D.C. about 558 US Breweries and 2410 US craft beers. We will examine craft beer bitterness and alcohol content by state, as well as, the relationship between bitterness and alcohol content.

## **Raw Data**

### **Breweries: [Breweries.csv](Breweries.csv)**  
#### Variables:
* Brew_ID:  ID number for each brewery
* Name:  Brewery Name
* City:  City each brewery is located
* State:  State each brewery is located

### **Beers: [Beers.csv](Beers.csv)**
#### Variables:
* Name: Beer Name
* Beer_ID:  ID number for each beer
* ABV:  Alcohol by volume
* IBU:  International Bitterness Unit
* Brewery_id:  ID number for each brewery
* Style: Style of Beer
* Ounces:  Fluid ounces of each beer


## **Clean/Combined Data**
### **BrewPub: [BrewPub.csv](BrewPub.csv)**
#### Merged by brew_ID/Brewery_id
* Name.x:  Beer Names
* Beer_ID:  ID number for each beer 
* ABV: Alcohol by Volume
* IBU:  International Bitterness Unit
* Brew_ID:  ID number for each brewery
* Style: Style of Beer
* Ounces Fluid ounces of each beer
* Name.y:  Name of each Brewery
* City:  City each brewery is located
* State: State each brewery is located


## **Analysis**
### Exploration of merged data to assess craft beer bitterness (IBU) and alcohol content (ABV) by state and the relationship, if any, between IBU and ABV.

### Completed analysis file: [BottomsUp_DS.pdf](BottomsUp_DS.pdf) 

