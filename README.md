# SNOW-ITSM

## Service
A service is a means of delivering value to the customers by facilitating the outcomes that customers want to achieve without the ownership of specific costs and risks.

![image](https://user-images.githubusercontent.com/12488769/148668601-e9650050-b0c7-4d22-bd4c-ddec2c281b0f.png)

## IT Service Management
ITSM is a process based practice intended to align the delivery of Information Technology (IT) services with needs of the organization, emphasizing benefits to customers.

IT service management (ITSM) refers to the entirety of activities – directed by policies, organized and structured in processes and supporting procedures – that are performed by an organization to design, plan, deliver, operate and control information technology (IT) services offered to customers.

It is thus concerned with the implementation of IT services that meet customers' needs, and it is performed by the IT service provider through an appropriate mix of people, process and information technology.


## ITSM Objectives
- To align IT Services with the current and future needs of the business and its customers
- To improve the quality of the IT services delivered
- To reduce the long term cost of service provision

![image](https://user-images.githubusercontent.com/12488769/148668644-d770f40a-6707-4bcf-a66f-97c91df666a6.png)

## Why Service Management
- Increasing demand from Business to deliver effective IT solutions/services (Cost effective)

- Increasing Competition

- Increasing Pressure to realize return on investment

- Increasing Complexity of IT infrastructure and processes

- Increasing IT Visibility

## Core ITSM Disciplines
- Service Support
Day to day operational support of IT services
- Service Delivery
Long term planning and improvement of IT service provision
![image](https://user-images.githubusercontent.com/12488769/148668689-795ed7c1-cb3e-4fa8-9aa4-fbfec737a44a.png)

![image](https://user-images.githubusercontent.com/12488769/148668705-cb760c04-1421-4eb0-8f95-dfbe2fe7cd37.png)

# ServiceNow ITSM
- ServiceNow is a leading provider of cloud-based services that automate enterprise IT operations. We focus on transforming enterprise IT by automating and standardizing business processes, transforming IT's relationship to its customers, and consolidating IT across the global enterprise. 
- ServiceNow is an on demand IT Service Management Solution platform founded in 2003 by Fred Luddy, former CEO of Peregrine Systems and Remedy Corporation.
- Headquartered in Santa Clara, CA with offices throughout the US, EMEA, Asia, Australia, India and customers in more than 48 countries.
- Supports more than 1900+ global customers including Fortune 1000 and Global 2000 companies.
- One of the fastest growing software companies with more than triple digit revenue growth.

![image](https://user-images.githubusercontent.com/12488769/148668775-67b2c913-02aa-4471-81c2-e2931b1de362.png)


- Web2.0 fast, flexible, affordable, simple & consistent.
- SaaS (Software as a Service), provides remote access to ITSM through a web based interface.
- ITIL (IT Infrastructure Library), provides the framework for IT services.
- PaaS (Platform as a Service), allowing to build applications without maintaining infrastructure.
- IT 3.0 – IT for people.
= SNOW is having a java based platform using tomcat web server running on                            Linux machine.


## Architecture
![image](https://user-images.githubusercontent.com/12488769/148668840-d93227e0-b66a-448a-8d92-1dd40d94b905.png)

## Features and key benefits
![image](https://user-images.githubusercontent.com/12488769/148668860-86140ac1-0d2b-442f-b1fd-b1f852388eac.png)

## Availability
![image](https://user-images.githubusercontent.com/12488769/148668867-e4cdfc76-5634-4e11-8b22-8cfde14a21d2.png)

## Scalability
![image](https://user-images.githubusercontent.com/12488769/148668870-ffb39701-f283-4d60-9213-4cde9f5de395.png)

## Security
![image](https://user-images.githubusercontent.com/12488769/148668874-a0b362af-f289-4bfe-b196-fd637e4a225b.png)

## Backup
7 Daily - preserved for one week
1 weekly – preserved for one month
Include data from all customer instances (Primary and secondary, Production and Non Production instances) 
Entire DB server backed up every night 

## Recovery
Restoration from backup is last resort especially in Production.
While restore, Production is unavailable.
For some customers, restoration can be longer and can take hours causing downtimes.

## Modules
Restoration from backup is last resort especially in Production.
While restore, Production is unavailable.
For some customers, restoration can be longer and can take hours causing downtimes.

## Licensing
Out of box users -> Admin, ITIL and Employee

Fulfiller – Can access all functionality based on assigned roles. 
Approver – Can perform all requester actions. 
Requester – Can submit requests (typically vis ESS) 

Note: Users having at least one role are counted as Licensed users in ServiceNow.
![image](https://user-images.githubusercontent.com/12488769/148668913-415089f3-053a-469e-92bb-36cd9b56e939.png)

## Cloaning
![image](https://user-images.githubusercontent.com/12488769/148668919-03f72816-73b2-465c-a57d-1a810c6c51d9.png)
Users having admin role can only place a request. 
Request has be placed 48 hours in advance to start of cloning action by ServiceNow.
![image](https://user-images.githubusercontent.com/12488769/148668925-8776821e-457e-45cb-8722-7d30e21be94b.png)

## Plugins
![image](https://user-images.githubusercontent.com/12488769/148668929-f210c65c-4f62-4308-bd5d-84ce9a10ac08.png)

Admins can activate any published Plugins. 
System Definition -> Plugin -> Right click – activate / upgrade
Plugins activated by default on newly created instances. 
Also, can be activated by request to HI portal.
![image](https://user-images.githubusercontent.com/12488769/148668933-aa193606-b4e8-4a3c-b988-46ebc2c8ab35.png)

## Tables and Columns
![image](https://user-images.githubusercontent.com/12488769/148668943-e8a81481-d6f2-4e78-9475-671c0bd78290.png)
![image](https://user-images.githubusercontent.com/12488769/148668949-a3645f4c-d5c2-499a-ad13-6b3e46a90b22.png)

## Single and Multitenant
- Single Tenant: One Domain per instance.

- Multi-Tenant: Multiple Domains per instance















