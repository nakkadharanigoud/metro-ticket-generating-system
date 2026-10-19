# Metro Ticket Generating System

A ServiceNow-based metro ticket booking application that automates fare calculation, ticket generation, QR-code generation, ticket verification, and administrative reporting.

## Project Overview

The Metro Ticket Generating System is developed using the ServiceNow platform. It provides a centralized system for managing metro stations, route fares, and passenger tickets.

## Features

- Metro station management
- Route-based fare management
- Automated fare calculation
- Unique metro ticket number generation
- QR-code generation for tickets
- Ticket verification
- Booking confirmation email notification
- Ticket cancellation validation
- Administrative reports and dashboard

## Technology Stack

- ServiceNow Developer Instance
- ServiceNow scoped application
- JavaScript
- Script Includes
- Business Rules
- REST Message integration
- ServiceNow UI Pages and GlideAjax
- ServiceNow Reports and Dashboards

## Application Modules

### 1. Metro Station Management
Maintains station names, station codes, metro lines, sequence numbers, and active status.

### 2. Metro Fare Management
Stores source stations, destination stations, fare amounts, and active status.

### 3. Ticket Booking
Stores passenger information, journey details, passenger count, and booking status.

### 4. Fare Calculation
Calculates the fare per passenger and total fare using the configured route fare.

### 5. QR-Code Generation
Generates QR-code content and associates a generated QR image with the ticket record.

### 6. Ticket Verification
Checks ticket numbers and returns the appropriate verification result.

### 7. Email Notification
Triggers a confirmation email when a booking becomes confirmed.

### 8. Reports and Dashboard
Displays booking statistics, ticket status distribution, booking trends, and confirmed-ticket fare summaries.

## Testing

The project includes checks for:

- Automatic fare calculation
- Invalid journey validation
- Ticket verification
- QR-code generation
- Confirmation notification
- Ticket cancellation rules
- Dashboard and report functionality

## Limitations

- QR-code generation depends on an external service.
- Payment gateway integration is not implemented.
- Production security and end-user access require further validation.
- Formal load and scalability testing remains future work.

## Future Enhancements

- Secure payment gateway integration
- Passenger-facing booking portal
- Enhanced route planning
- Ticket PDF generation
- Expanded security and performance testing

## Project Details

**Platform:** ServiceNow  
**Application:** Metro Ticket Generating System  
**Repository:** `metro-ticket-generating-system`

## Author

Nakka Dharani Goud
