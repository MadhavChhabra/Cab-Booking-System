# REST API for Online Cab Booking Application

* To Create an Application for Online Cab Booking 

* Customer should be able to view the list of available cabs.

* Customer should be able to book cab for desired location from a certain location. 

* Admin should be able to perform below operations:

      1. Cab Management 
      2. Driver Management
      3. Booking Management

## Tech Stack:

* Java
* Spring Framework
* Spring Boot
* Spring Data JPA
* Hibernate
* MySQL
* Swagger

## Modules:

  * Login Module
	* Admin Module
	* Customer Module
	* Driver Management Module
	* Cab Management Module
	* Booking Management Module

## Swagger Deployed link
http://localhost:8080/swagger-ui/index.html#/

### Sample API Response for User Login

`POST   localhost:8080/online_Cab_Booking_Application/login`

* Request Body

```
    
    {
        "email": "madhav@gmail.com",
        "password": "password"
    }
    
```
 
 
### E-R Diagram Of Online Cab Booking Application
---

<img src="https://user-images.githubusercontent.com/101389007/233461279-5b887298-050a-45f0-adcd-671add82e5ad.png">


---

### Login Controller

---

<img src="https://user-images.githubusercontent.com/101389007/232260920-4d916958-50dd-4410-828e-427a4348ea70.png">

---

### Admin Controller

---

<img src="https://user-images.githubusercontent.com/101389007/232260962-0a4a970d-4e1f-4487-8de1-199212405115.png">

---

### Customer Controller

---

<img src="https://user-images.githubusercontent.com/101389007/232261022-1fcf7b10-854f-4f4b-b833-6f14eace4b8f.png">

---

### Driver Controller

---

<img src="https://user-images.githubusercontent.com/101389007/232261089-d8fd340c-9e7c-4d86-a746-a53c62d6ed2b.png">

---

### Cab Controller

---

<img src="https://user-images.githubusercontent.com/101389007/232261140-f4bb904e-e033-4798-a356-9dfd30c8a3fa.png">

---

### TripBooking Controller

---

<img src="https://user-images.githubusercontent.com/101389007/232261155-0c9521b4-6998-484c-9e31-270705c3b70d.png">

--- 
