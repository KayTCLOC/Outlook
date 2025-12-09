# Outlook TCLOC – Beginner’s Manual

## Overview
This repository contains the Outlook documentation project for TCLOC.  
The documentation is written in the GitHub Wiki and follows the instructor’s template.

## Contents
- **Wiki Documentation**: Concepts, Tasks, References  
- **Images**: Screenshots and diagrams included in Wiki pages  
- **Swagger API Demo Project**: 2 fake endpoints documented in Swagger

## Key Topics Covered:

### Concepts
1. Outlook Architecture Overview for End‑users 
2. How Outlook Stores Your Data (End-users)

### Tasks
3. Add Your Email Account to Outlook 
4. Send Your First Email 
5. Organize Emails into Folders
6. Create a Calendar Event 
7. Set a Reminder for an Event 
8. Use Rules to Sort Emails Automatically 
9. Share Calendars and Delegate Access 
10. Install and Manage Outlook Add‑ins
11. Search for Emails Quickly 

### References
12. Outlook Keyboard Shortcuts Reference
13. Outlook Startup Options Reference


## How to Navigate
- Start at the [Wiki Home](https://github.com/KayTCLOC/Outlook/wiki) page  
- Use the **Index page** for a numbered list of topics  
- Topics are organized by type: Concepts, Tasks, References


## Target Audience
End‑users, especially beginners learning Outlook for daily productivity.


## API Documentation
As part of the assignment requirements, a **fake API project** has been created using Swagger (OpenAPI).
- The API is documented in [`swagger.yaml`](./swagger.yaml).
- It defines **two endpoints** to demonstrate how Outlook functionality could be exposed via an API:
  1. `GET /emails` – Retrieve a list of emails (fake data).
  2. `POST /emails` – Send a new email (fake data).

These endpoints are not connected to a real Outlook service. They are **documented examples** to illustrate API design and documentation practices.


## Author
Kayo Hosonuma


## License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
