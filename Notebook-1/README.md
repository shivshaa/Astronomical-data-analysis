## Overview

This lesson demonstrates the steps for selecting and downloading data from the Gaia Database.

## Steps

1. **Connect to the Gaia Server**
   - Establish a connection to the Gaia server to access the database.

2. **Explore the Database**
   - Retrieve and review information about the database structure and the tables it contains.

3. **Write and Execute a Query**
   - Compose a query tailored to the data you want to extract and send it to the server.

4. **Download the Response**
   - Obtain and store the server's response locally for further analysis.

## Query Language

In order to select data from a database, you have to compose a query, which is a program written in a "query language". 
The query language we'll use is ADQL, which stands for "Astronomical Data Query Language".

ADQL is a dialect of SQL (Structured Query Language), which is by far the most commonly used query language. 
Almost everything you will learn about ADQL also works in SQL.

### Connecting to Gaia
The library we'll use to get Gaia data is Astroquery. Astroquery provides Gaia, which is an object that represents a connection to the Gaia database.

We can connect to the Gaia database like this:
## from astroquery.gaia import Gaia

With tables this big, we generally don't directly download the tables. Instead, you use queries to select only the data you want.
A query is a string written in a query language like SQL; for the Gaia database, the query language is a dialect of SQL called ADQL.


