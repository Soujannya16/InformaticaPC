# InformaticaPC

Duration - 16.11.2020 to 29.11.2020

**Main objective of this project is to transform unstructured data into structured data so that the data can be used to for _Business Intelligence_.**

## 1.1. Problem Statement
To develop a complete Student Report defining the Department Dimension Table, Student Dimension Table, Marks Fact  Table, Subject Average Aggregate Table, Subject Pass Percentage Aggregate Table to have a clear picture about the personal details, individual marks & overall passing percentage of students of a certain institution.

## 1.2. Purpose & Scope
The purpose of this report is to systematically capture the requirements for the 'Student Report' project and the same system to be developed. Functional requirements of this system are captured in this document. It also serves as the input for the project scoping.
The motivation behind the undertaking is to assemble an information stockroom according to the necessities of the organisation utilizing Informatica PowerCenter ETL instrument. In the Student Report System, we are intending to assemble a Data Warehouse to help the organisation to have better choices.
The scope of this document is limited to addressing the requirements from a user, quality, and non-functional perspective. It is recommended that design aspects are not added in this document

## 1.3. Assumptions
-  All source files will be available in specified format
- Target database will be available to create Data Warehouse tables
- Informatica server will be able to connect to Data Warehouse database
- The system will not be available if there are any outages to Data     Warehouse Database

## 1.4. Key Requirements
- The system should allow the user to generate the result of the students on the basis of marks obtained keeping in mind the passing criteria as given.
 The system is required to generate the passing percentage of each subject grouped by department.

## 1.5. Impact
The system will be beneficial in order to manage the academics of a batch of students in an institution & generate a clear picture of necessary changes for betterment.

## 1.6 How to run
- First, the mapping xml files need to be imported in the Informatica PC _Designer_.
- Then, the workflow xml files need to be imported in the  _Workflow Manger_ associated with the mappings given.
- The sessions need to personalised and the location of the targets needs to be set. To do this, open the respective sessions in _Task Developer_ of _Workflow Manager_ and double click on the session icon. In the mapping part, the target location can be set.
- Now the workflow can be run and the progress and session logs can be checked in the _Workflow Monitor_ and the target database tables.
- The source files are given as text files for further reference.
- The target is relational databases here, so it isn't provided, the screenshots can be refered from the report.
- The session logs of when the project was run is given.
- The testing was done in sql developer and the testing file is also provided. The testing screenshots are provided in the report.
