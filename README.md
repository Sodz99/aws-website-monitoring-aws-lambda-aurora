# AWS Project-Website Monitoring using AWS Lambda and Aurora

AWS Project-Website Monitoring using AWS Lambda and Aurora — AWS Data Engineering project.

## Overview
- Streams are dividing into ordered Shards / Partitions
- Data retention is 24 hours by default, can go up to 7 days
- Ability to reprocess / replay data
- Multiple applications can consume the same stream
- Real-time processing with scale of throughput
- Once data is inserted in Kinesis, It can’t be deleted(immutability)
- Billing is as per number of provisioned shards

What?

A fully-managed No-SQL database that can store both Key-Value Pairs or documents(of JSON). Unlike SQL databases, No-SQL can save different rows with different number of columns in each row which is quite not possible in SQL. Its highly preferred to store unstructured data where SQL-like operations are not needed 1RCU= 4KB read(2 eventual and 1 strong) 1WCU = 1KB write

Why?

DynamoDB offers out of the availability(3 AZ replication) along with single digit millisecond latency for retrievals irrespective of data size stored.

Where?

## How to run

## Project structure
```
.gitignore
Codes/
  Codes/
    Python_files/
    new_lambda_function.py
    setup.sql
README.md
```

## Credits
Based on a ProjectPro guided project.
