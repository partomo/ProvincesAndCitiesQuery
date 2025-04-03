# README

This project contains two SQL files for inserting data into two tables: **Cities** and **Provinces** in a database. The files contain `INSERT INTO` commands to populate the respective tables with data.

## Files

1. **ProvincesQuery.txt**  
   This file contains SQL commands for inserting province data into the **Provinces** table. The data includes the province ID and name. This file is used to populate the provinces table.

   ### Provinces Table Structure:
   - `Id` (Province ID)
   - `ProvinceName` (Province Name)

2. **CitiesQuery.txt**  
   This file contains SQL commands for inserting city data into the **Cities** table. The data includes the province ID and city name. This file is used to populate the cities table.

   ### Cities Table Structure:
   - `ProvinceId` (Province ID)
   - `CityName` (City Name)

## Usage

1. First, make sure the **Provinces** and **Cities** tables exist in your database.
   
2. Execute the SQL commands from the files:
   - First, run the **ProvincesQuery.txt** file to insert province data into the database.
   - Then, run the **CitiesQuery.txt** file to insert city data into the database.

## Purpose

These files are useful for individuals who need to have information about Iranian provinces and cities in their database. This data can be used in various projects such as Geographic Information Systems (GIS) or data management systems.

---

