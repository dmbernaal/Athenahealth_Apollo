# Apollo V 0.10
This repository contains everything regarding the Apollo program. This progam is meant to connect various **Front-End** clients with our **Apollo Back-End**. 

This *agnostic* back-end connects directly into **Athenahealth API** endpoints for various purposes.

With our **current version 0.10** we simply feed in appointment data so patients can schedule appointments directly from the feed source. 

Another thing the **Apollo Back-End** does is feed all lead information to other **Lead Management Systems** so the third party marketer can keep track of everything in one organized place. 

The **Lead Management System** we will be hooking to is: **Pipedrive** and will be connecting to their API. To learn more about their API go here: https://github.com/jscott1989/python-pipedrive

## Workflow
The common workflow is feeding raw patient data (agnostic front-ends) into our **Apollo Back-End**. Though an un-common but solution embedded into **Apollo Back-End** is feeding raw patient data directly from a **Lead Management System** into the back-end and ultimately into the **Athenahealth API**. 

## Installations
This backend is built with **Python**. Therefor we will be using ```pip``` to install all dependencies. 

To install all dependencies for **Apollo** simply run the follow command: 

```
pip install -r requirements.txt
```
It is ideal to create a new ```env``` before installing dependencies.
