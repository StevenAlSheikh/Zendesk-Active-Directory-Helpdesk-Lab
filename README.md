# Zendesk & Active Directory Help Desk Lab

## Overview
This project demonstrates a functional IT help desk environment built on AWS. A Windows Server 2022 EC2 instance was deployed and promoted to a Domain Controller, Active Directory users and groups were created and managed, and support requests were documented through Zendesk to simulate real-world help desk workflows.

## Technologies Used
- Amazon Web Services (AWS) EC2
- Windows Server 2022
- Active Directory Domain Services (AD DS)
- PowerShell
- Zendesk

## Lab Environment
- **Cloud Platform:** AWS EC2
- **Operating System:** Windows Server 2022
- **Domain:** helpdesk.local

## Active Directory Tasks Completed
- Deployed Windows Server 2022 EC2 instance and promoted to Domain Controller using PowerShell
- Created user accounts: John Smith, Jane Doe, Bob Johnson
- Modified user attributes including job title and department
- Reset user password for Jane Doe
- Disabled user account for Bob Johnson (offboarding simulation)
- Created IT Department security group
- Added and removed users from security groups
- Deleted departed employee account

## Zendesk Tickets Documented
- **Ticket #1:** Password reset request — resolved
- **Ticket #2:** New user account setup — resolved
- **Ticket #3:** Employee offboarding — account disabled — resolved

## Screenshots
Screenshots of each step are included in this repository.
