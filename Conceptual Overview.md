# importance of finishing design process
	- the level of structural integrity and data integrity in the database is proportional to how thoroughly you follow the design process
## define a mission statement and mission objectives
- first phase in database design 
	- mission statement
	- mission objectives
	- help ensure develop a appropriate database structure
- two groups involved in the process
	- 1: database developer, person who owns the database and management personnel
		- define the mission statement
	- 2. developer, management personnel and the end user
		- define the mission objectives
## analyze the current database
- second phase
	- analyze the current database if exists
		- legacy database or a paper-based database
		- legacy database is the one used for years
		- paper-based database is the loose collections of forms, manila folders
	- involve review the way your organization currently collects and present the data
	- involve conducting interviews with users and management to identify how they interact with the database on a daily basis.
	- use the information gathered from the prior stages
		- refine the list by removing all calculated fields and place them on the list
			- will need the calculated field later in the design process
	- send to users and management for a brief review and possible refinement
## create the data structures
- third phase
	- define tables and fields, establish keys, and define field specifications for every field
	- tables are the first structures defined in the database
	- determine the various subjects that the tables will represent from the mission objectives compiled during the first phase
- review the fields within each table
	- define all multipart of multivalued fields in the table so they can store only a single value
- review the refine the table structure
	- check the work you performed on the fields to ensure tat each table structure is properly defined
- establish the appropriate keys for each table
- establish field specifications for each field in the database
## Determine and establish table relationship
- fourth stage
	- gain interviews from user testing and identify relationships among the data
	- establish a logical connection between tables with a primary key or with a linking table
## Determine and define business rules
- fifth stage
	- conduct interviews, identify limitations, establish business rules, and define and implement validation tables
		- the interview will reveal specific limitations on various aspects of the database
		- will also show some **general** limitations
	- define the implement validation tables
		- ensure the consistency and validity of the values stored
		- ongoing and iterative process
## Determining and define views
	- sixth phase
		- conduct interviews
		- identify the types of views
			- users may require detailed information to perform their work, whereas others need only summary information to help them make strategic decisions.
		- define the views identified during the interview process
# Review the data integrity
	- review each table to ensure that it meets the criteria of a properly designed table and check the fields within each table for proper structure
	- review and check field specifications for each field
		- make necessary refinement to the fields and then check field-level integrity
	- review the validity of each relationship, confirm the relationship type and confirm the participation characteristics.
	- review the business rule identified earlier in the database design process and confirm the constraints
