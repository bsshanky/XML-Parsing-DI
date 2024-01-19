# XML Parsing and Database Integration

## Project Motivation:

The main motivation behind this project was to effectively manage and analyze a large dataset of bibliographic information from PubMed. Given the extensive amount of data available in the XML format, the challenge was to parse, structure, and store the data in a relational database for efficient querying and analysis. The project aimed to leverage the power of R and database management systems (SQLite and MySQL) to handle large datasets, ensuring data integrity and providing a foundation for advanced data analysis and reporting.

## Goals:

1. Efficient Data Parsing and Loading:
To parse the pubmed22n0001-tf.xml file efficiently and load the data into a well-structured relational database.
To handle the XML structure intricately, ensuring that every piece of relevant data, especially related to Articles, Journals, and Authors, is accurately extracted.

2. Database Design and Implementation:
To design a normalized relational schema that effectively represents the data from the XML file, ensuring data integrity and facilitating easy retrieval.
To implement the schema in SQLite for initial data loading and processing, and then in MySQL for more advanced data handling and querying.

3. Data Integrity and Validation:
To validate the XML file against an external DTD, ensuring that the data conforms to the specified structure and is free from inconsistencies.

4. Performance Optimization:
To ensure that the script runs efficiently, even with large datasets. Specifically, the goal was to complete the parsing and loading of the data in under 5 minutes.

5. Data Transformation and Reporting:
To transform the date formats for consistency and analyze the data to provide insightful reports, such as the number of articles and authors per journal per month/year.

6. Code Quality and Maintainability:
To structure the R code in a readable, maintainable manner, with proper commenting and documentation for easy understanding and future enhancements.


## Results:

1. Complete and Accurate Data Parsing:
Successfully parsed the PubMed XML file, extracting all relevant information about articles, journals, and authors without losing data integrity.

2. Relational Database Implementation:
Designed and implemented a normalized database schema in SQLite, effectively capturing the relationships between articles, journals, and authors.
Transitioned the data into a MySQL database for advanced data handling and querying capabilities.

3. XML Validation:
Ensured the correctness of the XML file structure by validating it against the external DTD.

4. Performance Achievement:
Optimized the data parsing and loading process, achieving the complete parsing and insertion of data into the SQLite database in less than 5 minutes, which is a significant accomplishment given the complexity and size of the data.

5. Insightful Data Reporting:
Transformed and analyzed the data to produce meaningful reports, such as the number of articles and authors per journal, categorized by year, month, and quarter, providing valuable insights into the dataset.

6. High Code Quality:
Maintained high code quality with a well-structured, modular, and thoroughly commented R script, facilitating easy maintenance and future enhancements.

