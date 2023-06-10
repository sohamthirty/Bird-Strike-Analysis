# Bird-Strike-Analysis

## Data
**[Bird Strike Dataset by H. Haveliwala | data.world](https://data.world/hhaveliw/data-visualization-bird-strike)**

The dataset provides comprehensive information about bird strikes on aircraft, offering valuable insights into the occurrence, location, and impact of these incidents. It includes relevant attributes such as date, time, location, aircraft type, bird species involved, and the resulting damage or consequences. Having the dataset available on a reputable platform like data.world makes it easily accessible and allows SQL analysts to collaborate, share findings, and contribute to the collective knowledge in the field of bird strike analysis.

## Tasks
**A. Schema Design and Database Creation:**
- • Inspect the data file and design a schema for the database based on the requirements
- • Create a new database and connect to it from R
- • Create tables for bird strike incidents, airports, and conditions with appropriate columns and data types
- • Establish foreign key relationships between the incidents and airports tables, as well as between the incidents and conditions tables
- • Harmonize flight phases to standardized values

**B. Data Loading and Validation:**
- • Load the Bird Strikes CSV file into R and populate the tables with the subset of data
- • Map the columns from the CSV file to the corresponding columns in the database tables
- • Handle missing or empty values using default values or synthetic keys
- • Validate the loading process by displaying partial data from each table and document decisions made

**C. Querying and Analysis:**
- • Create SQL queries to find the number of bird strike incidents for each flight phase
- • Create SQL queries to identify the flight phase with an above-average number of bird strike incidents
- • Create a SQL query to calculate the average number of bird strike incidents by month across all years
- • Build a column chart to visualize the number of bird strike incidents per year from 2005 to 2011

**D. Stored Procedure:**
- • Create a stored procedure in MySQL to add new bird strike incident to database, accounting for potential addition of a new airport
- • Test the stored procedure in R to ensure it successfully adds a new incident

## Conclusion
In this project, we successfully designed and created a robust database schema for bird strike incidents, airports, and conditions. By loading and validating data from the Bird Strikes CSV file, we ensured accurate and complete information in the tables. Through SQL queries, we analyzed incidents by flight phase, identified above-average phases, and calculated average incidents per month. Visualization was achieved using a column chart. The implementation of a stored procedure facilitated seamless addition of new incidents while maintaining data integrity. This comprehensive analysis provided valuable insights into bird strike incidents and patterns.
