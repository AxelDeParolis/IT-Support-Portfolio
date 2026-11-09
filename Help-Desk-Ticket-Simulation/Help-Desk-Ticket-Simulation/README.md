Help Desk Ticket Simulation – Shared Folder Access

Project Overview

This project simulates a Level 1 IT Support scenario involving a user who cannot access a shared network folder.

The objective was to demonstrate a structured troubleshooting approach, user verification, permission investigation, escalation procedures, and ticket documentation.

Note: This is a simulated Help Desk exercise created for learning and portfolio development. It does not represent professional workplace experience.

Environment

Scenario: Corporate IT Support

User: John Smith

Department: Finance

Operating System: Windows

Directory Service: Active Directory (simulated)

Ticket ID: INC-001

Priority: Normal

1. Incident Description

The user reported being unable to access the Finance shared folder.

The error message indicated insufficient permissions. The user confirmed that:

Access had worked normally the previous day.

Other Finance employees could still access the folder.

The issue started that morning.

The computer was connected to the corporate network.

2. Initial Investigation

The first step was to verify the user's identity and gather relevant information.

The investigation focused on determining whether the issue was related to authentication or authorization.

Authentication verifies a user's identity.

Authorization determines which resources a user is allowed to access.

Since the user could log in to Windows successfully, the investigation focused on access permissions.

3. Root Cause Identification

The simulated Active Directory investigation revealed:

John Smith was a member of Domain Users.

Other Finance employees were members of GG_Finance.

The shared folder granted access to GG_Finance.

John Smith was not a member of GG_Finance.

Root Cause: The user's account was missing from the required security group.

4. Authorization and Escalation

Before making any permission changes, approval was requested from the user's manager.

The manager confirmed that John required access to the Finance shared folder.

The incident was then escalated to the responsible Active Directory team, which added the user to GG_Finance.

This approach follows the principle of least privilege and ensures that access changes are properly authorized.

5. Resolution and Verification

After the security group membership was updated:

John was asked to test access to the shared folder.

The user confirmed that access was working correctly.

The resolution was documented in the incident ticket.

Final Status: Resolved.

6. Ticket Documentation

The incident record included:

Issue: Unable to access the Finance shared folder.

Root Cause: Missing membership in GG_Finance.

Authorization: Manager approval obtained.

Resolution: User added to the required security group by the responsible team.

Verification: User confirmed successful access.

Status: Resolved.

7. Skills Demonstrated

Help Desk troubleshooting methodology

Active Directory fundamentals

User and permission management concepts

Authentication vs. Authorization

Security groups and access permissions

Escalation procedures

Principle of Least Privilege

Incident documentation

User communication and verification

Key Learning Outcome

This exercise demonstrated the importance of investigating access issues systematically, obtaining proper authorization before changing permissions, escalating tasks when necessary, and documenting the resolution clearly.
