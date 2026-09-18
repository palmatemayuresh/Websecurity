# Day 01 - Web Security Basics

**Date:** 18-09-2026

## What I learned today:

* Learned about the **CIA Triad**:

  * Confidentiality = making sure private information is only seen by the right people.
  * Integrity = making sure information doesn't get changed without permission.
  * Availability = making sure the system is available when people need it.

* Learned the difference between **Authentication and Authorization**.

  * Authentication = proving who you are.
  * Authorization = what you are allowed to access.

* Learned about **Encryption and Hashing**.

  * Encryption can be reversed if you have the correct key.
  * Hashing is basically a one-way process and is commonly used for passwords.

* Learned about **HTTPS and TLS** and how TLS helps protect information while it is being sent between a browser and a website.

* Learned what **SQL Injection** is.

  * It happens when user input can change the SQL query.
  * This can sometimes let an attacker read or change database information.
  * Parameterized queries are one of the main ways to prevent it.

* Learned about **XSS (Cross-Site Scripting)**.

  * This happens when a website allows unwanted JavaScript to run in a user's browser.
  * So unlike SQL Injection, XSS mainly affects the browser.

## Things I practiced:

* CIA Triad
* Authentication vs Authorization
* Encryption vs Hashing
* HTTPS / TLS
* SQL Injection
* `AND` and `OR` logic
* Parameterized queries
* XSS

## Things I understood better today:

I initially thought SQL Injection basically meant getting full access to a database, but I learned that it depends on the vulnerability and what permissions the database has.

I also understood the difference between SQL Injection and XSS:

**SQL Injection → database**

**XSS → browser**

## Mistakes / difficult parts:

* At first I was a little confused about how `AND` and `OR` work in SQL.
* I also wasn't sure about the difference between authentication and authorization, but the examples made it easier.

## What I will learn next:

* More about SQL Injection and XSS
* HTTP requests and responses
* HTTP methods and status codes
* Cookies and sessions

