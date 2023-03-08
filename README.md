# Self-ordering Kiosk application for restaurants

Usage
- "/restaurant" - screen displayed for clients
- "/kitchen" - screen with all orders details and options to finalize order for kitchen stuff
- "/" - main ordering application for clients

Program needs local DB to run (sample file - db.sql)
DB configuration in application.proporties file.

Technologies:
1. Java Spring Boot: 
  -	Thymeleaf (HTML, CSS, JavaScript)
  -	Spring Web
  -	Spring Security
  -	Spring Data JPA
2.	SQL (MySQL)

## Demo Application

### Main screen
List of all products with categories
### <img src="https://user-images.githubusercontent.com/59538107/223592822-4b65f10b-f0d7-4da3-a4aa-19168aba83b8.png" width="800">

### Product description
### <img src="https://user-images.githubusercontent.com/59538107/223592886-124068f8-333a-44d1-9673-5f8f06c2a1ed.png" width="800">

### Order summary
### <img src="https://user-images.githubusercontent.com/59538107/223592927-ad0f84d6-18c8-4741-8e2b-b6e2c2961650.png" width="800">

### Payment and order number
### <img src="https://user-images.githubusercontent.com/59538107/223592995-ced2688c-eab8-4c1d-b91b-b0684f4595f2.png" width="800">
### <img src="https://user-images.githubusercontent.com/59538107/223593078-79f7b893-6398-465e-96f2-d5f4211d9479.png" width="800">

## Screen for kitchen stuff
Allows to browse all current orders, mark them as finished or cancel.
### <img src="https://user-images.githubusercontent.com/59538107/223593334-54c56778-3bb6-47fc-b1ee-a13114b272c4.png" width="800">

## Customer information screen
Shows orders that are currently in preparation and those which are ready to be picked up.
### <img src="https://user-images.githubusercontent.com/59538107/223593374-75d16267-f01e-4255-bc28-5e6bc70fe0e8.png" width="800">
