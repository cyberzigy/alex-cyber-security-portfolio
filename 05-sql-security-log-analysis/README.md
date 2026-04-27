# SQL Security Log Analysis

## Project Overview

This project demonstrates the use of SQL to analyze authentication logs and identify suspicious login activity. SQL is commonly used in cybersecurity for log analysis, user investigations, and security reporting.

## Objectives

* Create a sample login activity database
* Query failed login attempts
* Identify suspicious IP addresses
* Detect repeated login failures
* Review successful logins after failures

## Tools Used

* SQLite / MySQL / PostgreSQL (any one)
* SQL Queries
* Local Lab Environment

## Database Table

`login_attempts`

| id | username | ip_address | status | timestamp |
| -- | -------- | ---------- | ------ | --------- |

## Example Security Queries

* Count failed logins by user
* Identify top suspicious IP addresses
* Show successful logins after repeated failures
* Detect repeated failed attempts in short periods

## Skills Demonstrated

* SQL SELECT statements
* WHERE filtering
* GROUP BY aggregation
* COUNT analysis
* Security event investigation
* Reporting suspicious behavior

## Conclusion

This project demonstrates how SQL can be used to investigate authentication activity and support cybersecurity monitoring operations.
