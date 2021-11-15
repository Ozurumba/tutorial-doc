
Database CurrentPrice Documentation
=====

**The Database** Of Currentprice is in an SQL architecture, we use Microsoft MySQL. We use Redshift as our data warehouse, it makes it as easy to gain new insights from all data. With Redshift, we can query and combine exabytes of structured and semi-structured data across your data warehouse.



.. _installation:

Installation
------------

The database can be run using Myworkbench or DBeaver CE

Architecture
----------------

.. image:: https://res.cloudinary.com/dpsujx7rk/image/upload/v1634031978/word-image-6_vvxuqi.png
  :width: 600
  :height: 400
  :alt: Alternative text
  
  
  
General Description
----------------

1 Product Functions
The system performs the following functions. The functions depend on the user’s level
and permission package, as explained in the user characteristics.

2 Login
This function allows the user to enter into the application. The user is required to provide
username and password. After authentication user will have access to main menu. Availability of
menu functions depends on user’s level.

3 View/add/edit/delete records
This function allows the admin to view/add/edit/delete records in the appropriate categories of the
DB. System has four main databases: “Surveyor”, “Assets”, “Manager”, and
“Assets_Allocation”.

4 Create new type of asset
This function allows the admin with to create a new type of asset.

5 Assign asset/employee to employee/manager
This function allows the user with appropriate permissions to assign:
 asset(s) to employee
 surveyor(s) to manager
Asset Management System

6 Add new request
This function can be done by employee or manger. The users can request a specific assets
which they are needed. After submission, the requests will forwarded to admin for
approval/rejection.

7 View list of all requests in the system
This function allows the admin to browse list of all requests existing in the system.

8 Approve/reject request
This function allows the admin to approve/reject any submitted request. He/she can either
approve or reject the request. While approving the request system will check whether
sufficient number of assets are available or not. If not available then the request is decline
by the system. Admin when rejects request shall provide reason for rejection.

9 View “My profile”
This function allows all the users to view list of all assets assigned to him/her, and own
details with name of manager.

10 View “Team”
This function allows the manager to view list of all team members with assets assigned to
them.

11 View “Allocated Assets”
This function allows all the admin to view list of all assets assigned to which employee.

12 Search
This function enables the admin to perform search operation with admin types text to
search for specific assets or employee.

13 Logout
This function can be done by all users. It terminates the user session. The system can also
do this function automatically if the session is left unused for half an hour.

14 User Characteristics
The users include the employees, manager and admin. For this system, the user is
required to know the basic usability of a very base level understanding of access, which
hopefully will be facilitated by the software team through training.

15 User Problem Statement
The users system, currently, is slow and inefficient as it relates to the manual asset
allocation. Employee may wait hours to get the asset they requested.

16 User Objectives
The user wants a database that will store information of asset allocated to employees. The
program must faciliatate the speed and ease of input.

17 General Constraints
Constraints include an easy to use interface for the program through forms, a Windows
platform. Our system is implemented in Angular. To install and execute the asset
management system, NPM is required.

Performance Requirements
----------------
The database is designed to be operated through MySQL, thus no additional system requirements
exist beyond those required to run MySQL, except for a negligible amount of hard drive space to
store the database.


Non-Functional Attributes
----------------
1 Security
The system shall be designed with a level of security appropriate for the sensitivity of
information enclosed in the database. More interaction is needed with client about the volatility
of the information. Since there is no obvious information that is of a high security level such as
credit card information, the only requirements that could be implemented are encrypting the
database and/or making the database password-protected, by user’s request.


2 Binary Compatibility
This system will be compatible with any computer that has MySQL 5.5 or later installed, and
will be designed with more than one computer in mind.


3 Reliability
Reliability is one of the key attributes of the system. Back-ups will be made regularly so that
restoration with minimal data loss is possible in the event of unforeseen events. The system will
also be thoroughly tested to ensure reliability.

Monitoring
------------

The Database services is monitored using Papertrail, which is hosted on Heroku
