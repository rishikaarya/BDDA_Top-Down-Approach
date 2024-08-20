
# Railway System Database_Top Down Approach

This repository contains the entity-relationship diagram (ERD) and schema structure for a Railway System database. The system manages passenger bookings, train details, routes, and payment information.

# Features

Journey Management: Tracks journey details, including booking, seat allocation, meal booking, and payment status. Passenger Information: Manages passenger details, including sign-up information and contact details. Station Management: Maintains a list of railway stations with associated city and state information. Train Information: Stores train details such as type, availability, source, destination, and passenger capacity. Train Routes: Organizes train routes, including estimated arrival and departure times, and station halts. Payment Processing: Tracks payment status and related booking information.

# Entity Relationship Diagram (ERD)

The ERD outlines the structure and relationships between key tables in the database:

Journey - Tracks booking, payment, and journey details. Passenger - Holds passenger data including personal and contact information. Station - Information on railway stations. Train Details - Stores information about individual trains. Train Routes - Defines routes and stations for each train. Train Type - Holds train types and coach information. User Login - Manages user login credentials and sign-up details.

# Database Schema

The following tables are used in the database:

Journey: Manages passenger journeys, bookings, and payments.

Key fields: journey_id, passenger_id, train_id, payment_status, seat_alloted Passenger: Stores passenger registration and contact details.

Key fields: passenger_id, first_name, last_name, email_id Stations: Stores railway station information.

Key fields: station_id, station_name, city, state Train Details: Stores information about trains including schedule and capacity.

Key fields: train_id, train_type_id, source_station_id, destination_station_id Train Routes: Manages train routes and station stops.

Key fields: route_id, train_id, station_id, estimated_arrival, estimated_departure Train Type: Stores the type and configuration of trains.

Key fields: train_type_id, train_type, coaches_count User Login: Manages user login details for passengers.

Key fields: user_id, user_password, email_id
