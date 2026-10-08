# Flight Management Records
This repository contains a MongoDB-based NoSQL project designed to store and manage flight information efficiently, as detailed in the reference document "abhishek maurya11.docx".  

## Overview

The main aim of this project is to understand the practical application of NoSQL databases for managing real-world flight data in a flexible and efficient manner. It handles various flight details, including flight ID, airline, route (source and destination), fare, passengers, available seats, and current flight status.   

## Project Information

* Developer: Abhishek Maurya (Roll no: 1250258020)

* Department: BCA(DS & AI)   

* Institution: BBD University, School of Computer Application   

* Academic Session: 2026-2027   

* Submitted to: Mr. Harendra Singh   

## MongoDB Operations Implemented

This project demonstrates a comprehensive suite of MongoDB operations to query and manage the database:   

* Database & Collection Management: Commands to create databases and collections (e.g., flight collection).

* Insert Operations: Bulk data insertion using insertMany().   

* Find & Search: Standard retrieval using find(), including multiple condition filtering.   

* Nested Document Search: Querying embedded documents (e.g., "route.from").   

* Comparison Operators: Filtering numerical data like fares and passenger counts using $gt, $lt, $gte, and $lte.   

* Logical Operators: Complex querying using $and and $or operations.   

* Text Search: Utilizing regular expressions ($regex) for pattern matching, such as searching by aircraft type.   

* Sorting & Aggregation: Organizing query results in Ascending (1) or Descending (-1) order using sort(), and counting records with countDocuments().   

## Sample Document Structure

The database is structured to handle nested JSON documents representing individual flights. A typical record includes:

{
  "flightId": "FL001",
  "airline": "IndiGo",
  "flightNumber": "6E201",
  "aircraft": "Airbus A320",
  "route": { "from": "Delhi", "to": "Mumbai", "distanceKm": 1150 },
  "departure": "06:30",
  "arrival": "08:40",
  "passengers": 164,
  "seatsAvailable": 16,
  "fare": 5200,
  "baggageLimitKg": 15,
  "status": "On Time"
}


This hands-on implementation serves as a practical foundation for understanding database creation, robust querying, and data filtering using modern NoSQL technologies.
