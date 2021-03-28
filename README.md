# Air Asia Retrieve Booking Unofficial API
##### Features:
- [x] Retrive Booking
- [x] Get PDF URL
- [ ] Download PDF

##### How to run?
```
git clone https://github.com/archv-id/airasia-retrieve-booking.git
cd airasia-retrieve-booking
npm install 
npm run dev
```
###### *node & npm required

##### URL:
> http://localhost:5000/airAsia?departure={}&bookingNumber={}&lastName={}
##### API Doc:
> https://www.getpostman.com/collections/affac083145127dc7e0c

##### Usage:
```
Method: GET
Params: 
- departure = Departure Airport Codes
- bookingNumber = Booking Number
- lastName = Passenger Last Name
```

##### Response 200:
```
{
    "status": 200,
    "err": false,
    "data": {
        "pdfUrl": "https://webitinerary.airasia.com/GetWebItinerary/...",
        "date": "2021-03-28"
    },
    "timeStamp": "2021-03-28 18:32:45"
}
```
### Author
> https://archv.id
