# Ambulance Service System

The Ambulance Service System is a web-based application that enables users to request ambulance services and allows ambulance drivers to pick up users and navigate to their locations. This system is designed to provide efficient and timely ambulance services to those in need.

## Features

- User Login/register: Users can create an acciount and log in to their accounts.
- Driver Login/register: Ambulance drivers can register their vehicle and log in to their accounts.
- User Booking: Users can request an ambulance service by providing their location, name and category of medical emergencies.
- Booking algorith: The Mulesoft used as a middleware in this project will perform logical operation to detect the available ambulance based on the data and create a trip.
- Driver Navigation: After the ambulance is provided with the trip, Ambulance drivers can view user requests and navigate to the user's location.
- Tracking: The system will monitor the current location of the Ambulance and provide accurate location of the ambulance to the user.
- Security: User and driver details are secured with crypto encryption, Logins are secured with unique session id, usage of PIN is used to begin and end the trips to provide surety of service to the patient.
- Rollback Strategy: Rollback strategy is used as exception handling to ensure the successful completion of each transaction/ operation.
