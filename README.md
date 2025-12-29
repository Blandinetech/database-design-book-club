# Database Design Project - Book Club

## Overview

This project demonstrates the design of a normalized relational database starting from raw and unstructured reporting data.

The goal was to analyze non-structured information and organize it into a clear and consistent Entity Relationship Diagram (ERD).

## Source Data

The data views shown in the `views` folder represent the type of raw, reporting-style data used as a starting point for the database design process.

These views contain unstructured and repeated information that required analysis and restructuring in order to produce a normalized data model.

## Design Approach

The design process was based on the business rules extracted from the data.

The initial data contained repeating groups, partial dependencies, transitive dependencies, and composite attributes.

The design process included:

- Identifying entities and their responsibilities
- Removing repeating groups
- Splitting composite attributes
- Resolving partial and transitive dependencies
- Defining clear primary and foreign keys
- Producing a clean and normalized ERD

## Concepts Demonstrated

- Data analysis and structuring
- Database normalization
- Entity Relationship Diagram (ERD)

The final result is a 3NF-compliant database design represented in the ERD.
