# Spring-cloud-gateway-zuul
This project is a spring cloud project for gateway using netflix zuul and spring cloud

discovery-server - It is using Eureka and used for discovering different clients

gateway-service - This is the project using netflix-zuul and spring cloud providing Gateway and Filtering services

hello-service and goodbye-service - These both services and configured using zuul and any request which is routed to these services goes through gateway-service.
