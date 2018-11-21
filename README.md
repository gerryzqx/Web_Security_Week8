# Project 8 - Pentesting Live Targets

Time spent: **X** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:

- Username Enumeration
- Insecure Direct Object Reference (IDOR)
- SQL Injection (SQLi)
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQL Injection
- GIF Walkthrough:
  -
  - Steps taken:
  1. Using sqlmap it gives us the vulnerability
  ```
  ' AND SLEEP(5)=0--'
  ```
  2. Insert this into the url
  3. The server will execute the SQLI and sleep for 5 seconds.

Vulnerability #2: Session Hijacking
- GIF Walkthrough:
  

## Green

Vulnerability #1: ********\_\_********

Vulnerability #2: ********\_\_********

## Red

Vulnerability #1: ********\_\_********

Vulnerability #2: ********\_\_********

## Notes

Describe any challenges encountered while doing the work
