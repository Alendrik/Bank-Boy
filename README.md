# Bank-Boy
## Overview
This repo is just a project I'm intending to build to get back into programming and learning nim.

It will be a client-server application with a web-app interface? and CLI API.

## Goals
I'll try to cover the following 5 components to reach the completed product:
- Functionality
- Authentication
- Authorization
- Security
- Logging

## Categories
### Functionality
**Goal Functionality**:	Functionality will be the traditional experience found at a typical bank/ATM.
**Stretch Functionality**: Have Loans, Interest to and against the customer, different accounts (savings/checking) that will incur interest at different rates based on system time.


### Authentication
**Goal Authentication**: Users that exist will be able to access their accounts through a login mechanism.

### Authorization
**Goal Authorization**: Authenticated users will only be able to access their own accounts and be allowed to perform only the things that a user at their level can. One Administrator Account will have abilities that are used to manage the system.


### Security
**Goal Security**: All the mechanisms mentioned above will have corresponding security measures to make them more secure
- Examples:
	- Input validation and sanitization
	- Hardened against undesired user behavior.
	- Logs are kep securely
	- TSL/SSL are used
	- DB is encrypted
	- etc.


### Logging
**Goal Logging**: Key Events should be logged in a designated log file. These logs should be free of as much PI as possible besides what users did what.



## Current State
- Figuring out Functionality.

Once Functionality is figured out, then we could move to other worries such as client serv, Access Control, etc.
