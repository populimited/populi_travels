# Populi Travels website

Populi travel is a new Tour Operator, which will work as a reseller of Vox Mundi Services in the Vatican. 
The purpose of the website is to show available services, and allow customers to book activities. 
The bookings will be inserted in the Mundi software via API.

## Pages


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

___

### ADD some tests
___


### API Docs
https://mundistaging.populi.rocks/api_doc.html


### API Access
- base url  https://mundistaging.populi.rocks/api/v2


