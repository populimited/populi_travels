# Populi Travels website

Populi travel is a new Tour Operator, that will work as a reseller of Vox Mundi Services in the Vatican. 

Out purpose is to build a website show available services, and allow customers to book activities.

The bookings will be inserted in the Vox Mundi software via API.

You can find Api documentation at the end of this document.



## Step 1 - Api Wrapper

- Build a client library for Vox Mundi API
- build a simple script that will use the client, and book the first possible availability of the first product for 2 "full" tickets


## Step 2 - Website

- Discussion about how to structure the project
- Do we need a database ? 

### Pages

#### Home page

- Welcome message and list of available services

#### Service page
- list available languages and times for a user defined date 
- The user will be able to select a specific date/time and language (some services are available in "ANY LANGUAGE") and proceed to the booking page

#### Booking page
- user will tell how many people for the booking (Adult/reduced)
- to simplify , all pricess will be 20€ for adult, 10€ for reduced (total price should be shown in real time)
- no real payment integration, the "PAY" button will just work and proceed with the booking

#### Booking Confirmation

after the booking is confirmed and saved to mundi sw, this page will show the details
and will provide a printable receipt with priority qrcode, and the access code (if available)


## Step 3 - Add some tests
___


### API Docs
https://mundistaging.populi.rocks/api_doc.html


### API Access
- base url  https://mundistaging.populi.rocks/api/v2


