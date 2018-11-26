
How do we identify the level of the project ? 

**Level one: Simple Practice**

Only one Simple Super Admin account

One account rules and manage all infomation without support of backup , error logging and limited permissions 

**requirment**
- manage all tenants, products, services .etc with Create, Read, Update, Delete functions
- simple relationship between tenants, products, services .etc
- build up database, backend api server, font-end single page application
- request and response api calls with right format 
- implement cloud tech: AWS/Azure
- good name convension(**NO** one, two ,three, a, b, c etc..)
- clean code(**USE** only tab or space)
- agile teamwork
- deal with code conflicts 

**Level Two: Prototype**

**requirment**
- All functions from Level One
- Supports Login and register function
- Supports JWT, OAuth
- Supports authentication
- Complex logic prior to Commercial
- Deploy to cloud
- Has swagger etc. api tools
- Design pattern considered
- Clean and professional UI/UX design
- MVC

**Level Three: Commercial**

**requirment**

- All functions from Level Two
- Multiple permissions support
- Mulitple authenticated tenants support
- Meaningful attributes and logic
- Different organizations, departments
- Transaction, logging, history, alert supports
- Error handling
- Linting and code standard
- Unit test, e2e test
- Google analysis suite intergrated
- Microservice / serverless / other structures considered
- Docker CI CD

**Level Four : Sass**

**requirment**
- Cloud based 
- scalable
- membership
- third party authentication
- Complex authentication and permissions

## Projects

### Mindset STEM Teaching Management System

**Objective:** Deliver a teaching management system which includes:
- assigns kids to the specific class
- supports one classroom to host one class at a specific period
- records all kids' behavior to the system
- assigns one teacher to be responsible for one classroom

**Level** Three

#### Site Structure
- kid profile
	- emergency contact profile
- history
	- records all kids' behavoir for every class
- classroom
- teachers
- class
- notification

### Ivy School Management System

**Objective:** Deliver a teaching management system which includes:
- assigns students to the specific class
- supports one classroom to host one class at a specific period
- assigns one teacher to be responsible for one classroom
- submit and reviews assignments

**Level** Three

#### Site Structure

- Student Profile:
	- Avatar
	- Name
	- Email
	- School
	- Mobile
	- City
	- Address
	- Introduction
	- Title
	- Enrolments
	- Assignments
- Course Profile:
	- Name
	- Course Code
	- NumberOfStudents
	- PrerequisiteKnowledge
	- CourseLength
	- TeachingMethod
	- CIty
	- CourseObjective
	- Level
	- CommenceDate
	- StartAppliedDate
	- CompleteDate
	- Tuition
	- Teachers
	- Project
	- Assignment
	- Thumbnail
	- Address
- Teacher Profile:
	- Name
	- Title
	- Avatar
	- School
	- Mobile
	- Company
	- Introduction
	- Course
	- Assignment
- Assignment Details
	- Name
	- Title
	- Content
	- Acceptance Criteria 
	- Belong to

#### Features

Only authenticated admin could manage all users, products, service .etc.
Teacher
- CRUD course and wait for approval
- assign course
- Manage assignment
- View students’ assignment

Student
- Login/ Register
- Enroll courses
- Update profile 
- Upload avatar
- Payment
- View Class


### TOP PTE Management System

**Objective:** Deliver a pte management system which includes:
- 

**Level** Three

### Handy Booking App (For Customer & Tradie)

**Level** Three
**Objective:** Deliver a tradie\handy booking app which includes:

For user
- book one specific service provided by a tradie
- make an online payment when booking a tradie
- user could login the system then mange and view history of bookings
- user could change their profiles
- list all services and tradies by category
- search functionality

For tradie
- check bookings
- arrange bookings 
- post their service by category
- update profile

** The app could specify one or multiplie industries, reference: cleaning, repairs, builders,handyman, plumbers, pest control, carpenters, electricians, removalists

** The app could pick other names, reference: goTradie, iHandy, taskify, Tradify, getHandy, getTradie, getClean, Houzz

** Reference website and apps: Gumtree, Airtasker, hipage

** Logos // TODO add logos 

#### Site Structure

**Front-end:**

- Home
- Find a Handy
	- Search (results)
	- Filter by categories
		- Location
		- Vocation
	- Select one tradie
		- View details
		- Book & Request
- Browse Handy
- Login/ Register

**Back-end API/DB**
-  Query Tradie
-  Book/Update Tradie
-  Payment
-  SQL/nosql

**Roles**
- Customer
	- Profile
		- Email
		- Name
		- Gender
		- Language
		- Address
		- Mobile
		- Avatar
		- Introduction
	- Features
		- Update profile
		- Search tradies by location, name, vacation, purpose
		- View tradies
		- Book/request/confirm tradies
		- view your appointment
		- view history (optional)
		- make a payment (optional)
		- chat/message tradie (optional)
		- make a review (optional)
- Tradie 
	- Profile
		- Email
		- Name
		- Title
		- Gender
		- Age
		- Address
		- Language
		- Avatar
		- Professional Years
		- Skills - list of skills tag
		- Vocation
		- Bages - Award or verification  (optional)
		- Reviews  (optional)
		- Portfolio (optional)
		- Introduction
	- Features
		- View request and confirm / change request
		- Update profile
		- Arrange appointment
		- issue invoices (optional)

### Handy Booking Management System

**Level** Three

**Objective:** Deliver a tradie\handy booking system which includes:

- manage bookings from users
- assign related tradie to the user
- CRUD tradies and services
- view history of tradies
- view transactions

**Front-end:**

A portal for staff/admin to manage the handy app

**Back-end API/DB**
-  Query Tradie
-  Book/Update Tradie
-  Payment
-  SQL/nosql

**Roles**
- Staff
	- CRUD Customer and Tradie
	- CRUD transactions
	- CRUD bookings
- Super Admin
	- CRUD Customer and Tradie
	- CRUD transactions
	- CRUD bookings

#### Site Structure

### Teachable Sass Teaching Management System (Hard)

**Level** Four

Roles:
- super admin
- school admin
- staff admin
- teachers
- students

- Multiple tenants support
- Multiple schools support
- Individual repository for schools
- Payment & Transaction support (PCI compliance)
- Super Admin

**Level** Four

### Insight People Management System
* Commercial Rate: 5
* Hardness Rate: 5

#### System Includes

Time & Attendance Mangement

Performance Management

Shift Shceduling

Time Tracker

Time-off Management

#### Site Structure

- Settings
	- Organization
		- departments
		- locations
		- staff
		- Holiday Calendar
	- Employee
		- Users
		- Employee profiles
	- Notification
		- Workflows
		- Mail Alerts
		- Scheduler
	- Approvals
- Time Tracker
	- Log Time
	- List roaster
		- List by Calender
		- List by table
- Leave Tracker
	- Leave List
	- Add Leave
- Organization
	- Department
		- Assign Department Lead
	- Employee
		- Employee(List all employee)
		- Directory(List all employee by directory)
	- Company Policy
	- Announcements
- My Approvals
	- My Approvals
	- My Requests

#### Features

##### Update company profiles

**description**

AS a Admin

I WANT to modify the profile of the company

SO THAT I'm able to change the company profile any time

**attributes (reference)**
- Email ID
- Current Locale
- Name
- Phone
- Address

##### Apply for leave

**description**

AS a Staff

I WANT to apply for a leave

SO THAT I'm able to change the company profile any time

**attributes (reference)**

- Leave type
- Duration
	- Full Day
	- Multiple Days
	- Part Day 
- Start Date
- Details
- Sent to (Supvervisor)
- Message
- Submit

##### Approve leave


**description**

AS a Admin

I WANT to approve for a leave

SO THAT I'm able to change the company profile any time

**attributes (reference)**
- User id
- Who approved


### IntelHR Management System


### Insight Recruit Management System


### Hulu Customer Relationship Management System

#### System Includes
Task Management
Contacts Management
Deals Managment
Lead Management

#### Site Structure

- Contacts
	- List People
		- People Details
			- Basic Infomation
				- Contact Owner
				- Email
				- Phone
				- Number
				- Department
			- Contact Details
				- Contact Owner
				- Account Name
				- Email
				- Phone
				- Other Phone
				- Mobile 
				- Assistant
				- Reports To
				- Created
				- Modified By
				- Lead Source Trade Show
				- Contact Name
				- Title
				- Department
				- Home Phone
				- Fax
				- Date of Birth
				- Asst Phone
				- Email Opt Out
				- Skype ID
				- Secondary Email
				- Twitter kris
				- Reporting To
			 - Address Infomation
				- Mailling Street
				- Mailing City
				- Mailing State
				- Mailing ZIp
				- Mailing Country
			- Description
			- Notes
			- Relationship
				- Deals
				- Activities
				- Events
	- Company
- Leads
	- List Lead
		- Lead details
			- Lead Name
			- Lead Owner
			- Phone
			- Mobile
			- Lead Status
				- Attempted to Contact
				- Contact in futre
				- Contacted
				- Junk Lead
				- Lost Lead
			- Lead infomation
- Deals
	- Process
- Task
- Activities