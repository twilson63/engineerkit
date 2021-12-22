# Data

![Hard](https://img.shields.io/badge/Difficulty-◆%20Hard-black?style=flat-square)
<a href="https://github.com/engineerkit/engineerkit/discussions">![Ask Questions](https://img.shields.io/badge/Ask%20Questions%20-blue.svg?style=flat-square&logo=discourse&logoWidth=15&labelColor=555&color=4d51cc)</a>

### With this module, you’ll learn about persisting data beyond a process in memory, including binary files and structured data stored in databases.

<img width="1440" alt="Data Module" src="https://user-images.githubusercontent.com/894178/138357282-e49884e2-dd8b-42fd-828f-74c833d3d31a.png">

## Topics

<details open>
   <summary><b>Types of Data</b></summary><br/>

   With this topic, you’ll learn about the spectrum of unstructured to structured data types and how to classify data correctly.
   
   #### Learning Outcomes
   * Describe binary data
   * Compare structured and unstructured data types
   * Theorize what data types you might use in an application

   #### Resources
   * https://www.ibm.com/cloud/blog/structured-vs-unstructured-data

   #### Exercises
   * Use hexdump to extract data from a file
</details>

----

<details open>
   <summary><b>Data Storage</b></summary><br/>

   With this topic, you’ll learn techniques to store data of all types for usage in an application.
   
   #### Learning Outcomes
   * Compare storing data in a relational and non-relational database
   * Explain storing data using object storage providers such as AWS S3
   * Describe three different approaches to persist data for an application

   #### Resources
   * https://aws.amazon.com/products/databases
   * https://aws.amazon.com/products/storage

   #### Exercises
   * Setup a relational and non-relational database and store data in them (what are some of the differences?)
</details>

----

<details open>
   <summary><b>Data Manipulation</b></summary><br/>

   With this topic, you’ll learn how to interact with and manipulate data from storage providers using techniques such as SQL or SSH. 
   
   #### Learning Outcomes
   * Explain what CRUD operations are
   * Explain what relational database schema is
   * Retrieve data from a database using a SELECT query
   * Use an ORM to retrieve data from a database in an application
   * Download a file from a server using SSH
   * Create a new item in a database table using an INSERT INTO query
   * Update an existing item in a database table using an UPDATE query
   * Delete an existing item in a database table using a DELETE query
   * Use migrations to update the schema of a database

   #### Resources
   * https://sql-playground.wizardzines.com/

   #### Exercises
   * Connect an application to an ORM (such as Prisma) and update the schema of a database using data models
</details>

----

<details open>
   <summary><b>Data Wrangling</b></summary><br/>

   With this topic, you’ll learn to convert data from one type to another using data wrangling techniques.
   
   #### Learning Outcomes
   * Describe the ETL (extract, transform, load) process
   * Use a regular expression (Regex) to grep for IP addresses in log files
   * Convert a WAV audio file to an MP3 audio file using ffmpeg

   #### Resources
   * https://missing.csail.mit.edu/2020/data-wrangling/

   #### Exercises
   * Convert a video file with audio into an audio file only using ffmpeg (what did you learn?)
</details>

----

<details open>
   <summary><b>Managing State</b></summary><br/>

   With this topic, you’ll learn about effectively using different patterns to manage the state in an application.
   
   #### Learning Outcomes
   * Describe application "state"
   * Explain the factors to consider when caching data
   * Describe the purpose of offline data storage
   * Compare using global and local state in an application
   * Compare eventual and strong consistency and explain their differences

   #### Resources
   * https://www.martinfowler.com/articles/201701-event-driven.html

   #### Exercises
   * Throttle your network connection using Chrome Dev Tools and figure out which aspects of an app are cached
</details>