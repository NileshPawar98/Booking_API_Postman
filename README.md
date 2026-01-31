*** Booking API Postman Project***

* Overview
This repository contains Postman collections and environments for testing the [Restful Booker API](https://restful-booker.herokuapp.com/).

*Features
- Create Booking (POST)
- Get Booking (GET)
- Update Booking (PUT/PATCH)
- Delete Booking (DELETE)

* How to Use
1. Import the collection JSON file into Postman.
2. Import the environment JSON file and set variables (`fname`, `lname`, `b_id`, `b_token`).
3. Run the requests in sequence:
   - Generate Token
   - Create Booking
   - Get Booking
   - Update Booking
   - Delete Booking

*Requirements
	- Postman installed
	- Valid token generated from `/auth` endpoint

* Repository Structure
	- collections/` → Postman collection JSON
	- environments/` → Postman environment JSON

* Author
Created by **Nilesh Pawar**