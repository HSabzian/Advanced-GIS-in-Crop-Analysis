
<img width="1600" alt="Screen Shot 2024-08-09 at 1 41 38 AM" src="https://github.com/user-attachments/assets/7caf2669-01ea-4107-a3e8-d5ff5598bc7d">



# Final Project Title: USDA Crops Data Analyzer (USDACDA)


NASS (National Agricultural Statistics Service) is a branch of the USDA (United States Department of Agriculture) that collects and disseminates agricultural statistics for the United States. NASS has developed a number of databases for agricultural purposes three of which can be :

-	Cropland Data Layer (CDL) : The CDL is a raster, geo-referenced, crop-specific land cover data layer created annually for the continental United States using moderate resolution satellite imagery and extensive agricultural ground truth.

Survey data and census data are other two types of data collection methods used by NASS to gather information about agriculture and related topics. Both data sources include 46899262 records as of June 17, 2023.

-	Survey data are collected through a sample survey of a subset of the population of interest. The survey collects information from farmers, ranchers, and other agricultural producers on a regular basis. NASS conducts various surveys throughout the year to collect data on crop production, livestock inventory, farm income, and other related topics. Survey data include 18772894 records (from 1850 to 2023)

-	Census data, on the other hand, are collected once every five years and provide a complete count of all farms and ranches in the United States. The census collects data on land use, ownership, production practices, and other characteristics of farms and ranches. Census data include 28126368 records (from 1997 to 2021) 

Both survey data and census data are important sources of information for policymakers, researchers, and others interested in the agricultural industry. The data is used to make informed decisions, develop policies, and support research on agriculture and related topics.

Both data sources cover several items and sub-items such as 
-	Program: Census, Survey
-	Sector: CROPS,….
-	Group: FIELD CROPS,….
-	Commodity: BARELY, BEANS, ALMONDS ,……
-	Category: AREA PLANTED,…
-	Data Item: ACREAS PLANTED,…
-	Domain: TOTAL,..
-	Geographic Level: AGRICULTURAL DISTRICT, COUNTY, STATE, ….
-	Year: 2022, …
 

Problems for users:

1-	No fast-query database and researchers must save 50K records at each query. 
2-	No SRS for these data and researchers cannot analyze them in a map structure. 
3-	No Special functions for scientific visualization (line plots, maps…) and statistical analysis


Purpose of this Project:

The purpose of this project is to develop a highly easy-to-use software technology, USDA Crops Data Analyzer (USDACDA) for deep exploration of all USDA survey data of field crops. 
This technology is developed to enable the researchers to get the following goals:

1-	Fast-query database of all field crops from 2000 to 2022 (1.2 M records).
Fast integration with map data and high scalability
2-	Easy access to this database by a simple query (two-queries)
3-	Easy analysis of these data at different levels (country, state and county)
4-	Easy visualization of these data at different levels (country, state and county)


# High-Level View (Flowchart & Database Architecture)

## Flowchart

<img width="529" alt="Screen Shot 2024-08-09 at 1 36 50 AM" src="https://github.com/user-attachments/assets/8f1d883d-7381-4403-a377-9e696d64d643">

## Spatio-temporal Data base structure

<img width="826" alt="Screen Shot 2024-08-09 at 1 37 13 AM" src="https://github.com/user-attachments/assets/3a2c2ad9-3bbf-4b45-a31f-35093293036b">


# Examples of output analysis by functions


## Example 1: crops based on planted acres query

<img width="952" alt="Screen Shot 2024-08-09 at 1 47 22 AM" src="https://github.com/user-attachments/assets/c980eb65-3e01-4cc6-a176-12a84c3978cc">


<img width="1052" alt="Screen Shot 2024-08-09 at 1 48 48 AM" src="https://github.com/user-attachments/assets/c055c08b-942d-4ae2-b248-dc94bf1fb0c8">


## Diversity Map of Example (Shanon diversity)

<img width="873" alt="Screen Shot 2024-08-09 at 1 41 08 AM" src="https://github.com/user-attachments/assets/0f73665b-1b84-42d6-a088-5f05501dad24">


## Finer Level Analysis (county, State, country)

<img width="932" alt="Screen Shot 2024-08-09 at 2 02 40 AM" src="https://github.com/user-attachments/assets/4d38dc8b-d088-4d2c-879c-c75085b1d63a">


<img width="910" alt="Screen Shot 2024-08-09 at 2 02 32 AM" src="https://github.com/user-attachments/assets/3a73f727-4cd3-4836-9933-4348c94c07c5">


<img width="1007" alt="Screen Shot 2024-08-09 at 2 02 21 AM" src="https://github.com/user-attachments/assets/9f90cc55-b548-4cd5-a37f-3b2395cba3b7">


For complete details run the attched program and see this PDF: 

[USDA Crops Data Analyzer (USDACDA).pdf](https://github.com/user-attachments/files/16556677/USDA.Crops.Data.Analyzer.USDACDA.pdf)

