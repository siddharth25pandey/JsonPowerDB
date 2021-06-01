# JsonPowerDB
JsonPowerDB is a Database Server with Developer friendly REST API services. It's a High Performance, Light Weight, Ajax Enabled, Serverless, Simple to Use, Real-time Database.

## Description
JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

## Benefits of using JsonPowerDB
* Simplest way to retrieve data in a JSON format.
* Schema-free, Simple to use, Nimble and In-Memory database.
* It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
* It is low level (raw) form of data and is also human readable.
* It helps developers in faster coding, in-turn reduces development cost.

### Json PowerDB Documentation
* [JPDB Document](http://login2explore.com/jpdb/docs.html)
* [Java Script Library](https://login2explore.com/jpdb/resources/js/0.0.3/jpdb-commons.js) (JPDB using jpdb common js - A Javascript library to make it even easy and fast for developers)
* [ Talend API TesterPage](https://chrome.google.com/webstore/detail/talend-api-tester-free-ed/aejoelaoggembcahagimdiliamlcdmfm?hl=en) (Visually interact with REST, SOAP and HTTP APIs)

### CRUD operations
* Create (PUT): Use to Insert single record in the database

 `Http method : POST`
 
`Base url : http://api.login2explore.com:5577`

`End-point url : /api/iml (mentioned in command when different)`

* Read (GET): Retrieve single record by json data ( Deprecated - use GET_BY_KEY)

 `Http method : POST`
 
`Base url : http://api.login2explore.com:5577`

`End-point url : /api/irl`

* Update (UPDATE): Update multiple records in the database or add a new column in a record

 `Http method : POST`
 
`Base url : http://api.login2explore.com:5577`

`End-point url : /api/iml (mentioned in command when different)`

* Delete (Remove):Remove records from the database

 `Http method : POST`
 
`Base url : http://api.login2explore.com:5577`

`End-point url : /api/iml (mentioned in command when different)`

**IML (JPDB Index Manipulation Language) - To insert, update and delete Json data.**

**IRL (JPDB Index Retrieval Language) - To retrieve Json data.**

