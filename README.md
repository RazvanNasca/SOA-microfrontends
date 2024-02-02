# SOA-microfrontends by Nașca Răzvan-Alexandru

### MicroFrontends Application Documentation
This document provides an overview of the Micro Frontends application, its architecture and how to run and develop it.

# Overview 
The MicroFrontends application is a web application written in ReactJs that uses microfrontends to create a modular architecture. It consists of three microfrontends:
1.	Host MicroFrontend: The main application and the entry point for the user
2.	Products MicroFrontend: Display the products
3.	Cart MicroFrontend: Finish order

# Architecture
The MicroFrontends application architecture follows the MicroFrontends pattern. Each project is developed and deployed independently, and communicates with the other micro frontends through the Host MicroFrontend.

The Host MicroFrontend is the main application and is responsible for rendering the navigation menu and loading the other microfrontends as required. 

All this microfrontends run on different ports:
1.	Host MicroFrontend: 3000
2.	Products MicroFrontend: 3001
3.	Cart MicroFrontend: 3002


# Installation

## Prerequisites:
1.	NodeJS
2.	Docker
3.	Docker Compose

From the root project, run the following commands:
1.	docker-compose build
2.	docker-compose up

Than open your browser and navigate `"http://localhost:3000"`
