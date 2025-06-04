# README

This project contains three SQL files for inserting data into the following tables: **Provinces**, **Counties**, and **Cities** in a database. Each file contains `INSERT INTO` commands to populate the respective table with data related to Iran's administrative divisions.

## Files

1. **ProvincesQuery.sql**  
   Contains SQL commands for inserting **province** data into the **Provinces** table. Each row includes a unique province ID and name.

   ### Provinces Table Structure:
   - `Id` (INT) – Province ID (Primary Key)
   - `ProvinceName` (NVARCHAR) – Name of the province

2. **CountiesQuery.sql**  
   Contains SQL commands for inserting **county (shahrestan)** data into the **Counties** table. Each county is linked to a province by its ID.

   ### Counties Table Structure:
   - `Id` (INT, auto-increment) – County ID (Primary Key)
   - `ProvinceId` (INT) – Reference to Province ID
   - `CountyName` (NVARCHAR) – Name of the county

3. **CitiesQuery.sql**  
   Contains SQL commands for inserting **city** data into the **Cities** table. Each city is also linked to a province by its ID.

   ### Cities Table Structure:
   - `Id` (INT, auto-increment) – City ID (Primary Key)
   - `ProvinceId` (INT) – Reference to Province ID
   - `CityName` (NVARCHAR) – Name of the city

## Usage

1. Ensure that the **Provinces**, **Counties**, and **Cities** tables are already created in your database with the correct structure.

2. Run the SQL files in the following order:
   - `ProvincesQuery.sql`
   - `CountiesQuery.sql`
   - `CitiesQuery.sql`

   You can execute these scripts using SQL Server Management Studio (SSMS), `sqlcmd`, or through any other database interface.

## Purpose

These SQL scripts are useful for anyone working with geographic or administrative data of Iran. They are ideal for use in GIS systems, address management, form dropdowns, and any application requiring structured Iranian location data.

## License

This project is provided under the MIT License — feel free to use, modify, and share it.

