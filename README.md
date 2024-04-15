# Deloitte Auditor Enterprise Chat UI - SQL Storage

## Overview
This project involves developing a web interface for Deloitte Auditor team to prompt tax-related questions and store client responses locally using SQL. The interface will be connected with a REST interface for communication.

## SQL Table Design
To store the prompt and responses details, a SQL table needs to be constructed. Here's a basic design for the table:

```sql
CREATE TABLE TaxResponses (
    ID INT PRIMARY KEY AUTO_INCREMENT,
    Prompt TEXT,
    Response TEXT,
    ClientID INT,
    Timestamp TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

## Screenshots
Here are some screenshots showcasing the functionality of the web interface:

<img width="1040" alt="Tax question - Screenshot" src="https://github.com/irasharma13/Deloitte-Auditor-Enterprise-Chat/assets/36807339/eef43b60-42f3-4005-a8e8-682c18c7339b">
<img width="831" alt="Non Tax question - Screenshot" src="https://github.com/irasharma13/Deloitte-Auditor-Enterprise-Chat/assets/36807339/66032205-10d9-41f9-9efe-472170eda351">
<img width="580" alt="Saving question - Screeshot" src="https://github.com/irasharma13/Deloitte-Auditor-Enterprise-Chat/assets/36807339/77b6c39a-20a0-4423-b4ab-9f63f80d0156">

https://github.com/irasharma13/Deloitte-Auditor-Enterprise-Chat/assets/36807339/2451c1bc-8570-4438-9cdc-5a0886ebdba0

