# **Aviation Database System**

## **Project Overview**
The **Aviation Database System** is a robust and scalable platform designed to manage airline operations such as flight scheduling, passenger details, reservations, payments, crew assignments, and real-time flight status updates. Built using **MySQL**, the system ensures secure data management, streamlined workflows, and an optimized user experience for both passengers and administrators.

The project aims to improve operational efficiency, minimize booking errors, and enhance the customer experience by providing real-time flight updates, personalized discounts, and seamless integration of various airline operations.

---

## **Features**
- **Flight Scheduling**: Easy management of flight details, including departure/arrival information and airline assignments.
- **Passenger Management**: Store and manage passenger details securely, including reservations and personal information.
- **Reservations & Payments**: Allow passengers to search for flights, book seats, and make secure payments.
- **Crew Management**: Assign crew members to specific flights and monitor their roles (pilot, co-pilot, attendants).
- **Real-Time Flight Status**: Monitor and update the flight status (e.g., delayed, landed, cancelled) in real-time.
- **Luggage Tracking**: Track luggage related to specific reservations.
- **Offers & Discounts**: Manage and offer personalized discounts to passengers.
- **MySQL Database**: The system is built on a well-structured MySQL database with optimized tables, foreign key constraints, and indexing.

---

## **Database Structure**

The database is structured with the following core tables:

1. **Airlines**: Contains airline details like name, country, and headquarters.
2. **Airports**: Stores airport information including city, country, and airport code.
3. **Flights**: Stores flight-related details including airline, departure/arrival, status, and aircraft type.
4. **Passengers**: Stores passenger details including name, contact information, passport number, and nationality.
5. **Reservations**: Records booking details for passengers, including seat class, flight, and seat assignments.
6. **Crew**: Contains crew information including role (pilot, co-pilot, etc.) and flight assignments.
7. **Payments**: Tracks payment details including amount, method, and date.
8. **Luggage**: Manages luggage information, linking it to specific reservations.
9. **Flight_Status**: Monitors the current status of flights (delayed, departed, etc.).
10. **Offers_Discounts**: Manages available discounts and promotions for passengers.

---

## **Usage**

Once the database is set up, you can interact with the system by:
1. Adding flight schedules, airport information, and crew members.
2. Allowing passengers to make reservations and process payments.
3. Monitoring flight statuses, handling luggage, and applying special offers.


## **Project Workflow**
The system is designed to function in the following steps:

1. **Passenger makes a reservation** by selecting a flight, seat class, and submitting payment details.
2. **Administrator** manages the flight schedules, crew assignments, and monitors flight statuses.
3. **Real-time updates** are sent to the system for any changes in flight status (delayed, cancelled, etc.).
4. Passengers can track **luggage** and receive **offers and discounts** on upcoming flights.

