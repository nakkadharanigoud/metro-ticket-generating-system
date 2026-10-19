# Metro Ticket Generating System — Project Report

## 1. Introduction
### 1.1 Project Overview
The Metro Ticket Generating System is a ServiceNow-based application for managing metro stations, fares, and passenger ticket bookings.

### 1.2 Purpose
The project aims to automate fare calculation, ticket generation, ticket verification, and administrative reporting.

## 2. Ideation Phase
### 2.1 Problem Statement
Manual ticketing processes can cause fare calculation errors, inconsistent records, and delays in checking ticket status.

### 2.2 Empathy Map Canvas
- Passenger needs a simple booking process.
- Passenger expects accurate fare information.
- Passenger needs a ticket reference and status verification.
- Administrator needs accurate records and reports.

### 2.3 Brainstorming
- Centralized station and fare records
- Automated fare calculation
- Unique ticket numbers
- QR-code generation
- Ticket verification
- Confirmation notifications
- Administrative dashboard

## 3. Requirement Analysis
### 3.1 Customer Journey Map
1. Enter passenger and journey details.
2. Select source and destination.
3. Validate booking details.
4. Calculate fare.
5. Generate ticket reference and QR code.
6. Confirm and verify the ticket.

### 3.2 Solution Requirements
- Manage station and fare records.
- Validate journey details.
- Calculate total fare.
- Generate ticket numbers and QR codes.
- Verify ticket status.
- Send confirmation notifications.
- Display reports and dashboard information.

### 3.3 Data Flow Diagram
Passenger → Ticket Booking → Validation → Fare Calculation → Ticket Record → QR Generation → Ticket Verification.

Administrator → Reports and Dashboard → Booking and Fare Summaries.

### 3.4 Technology Stack
- ServiceNow
- JavaScript
- Script Includes
- Business Rules
- REST Message integration
- UI Pages and GlideAjax
- Reports and Dashboards

## 4. Project Design
### 4.1 Problem Solution Fit
The application centralizes ticket information and automates fare calculation and ticket-status validation.

### 4.2 Proposed Solution
A scoped ServiceNow application containing station management, fare management, ticket booking, QR-code generation, verification, notifications, and reporting.

### 4.3 Solution Architecture
The user interface communicates with server-side scripts and Business Rules. These components process data stored in ServiceNow tables and integrate with an external QR-code service.

## 5. Project Planning & Scheduling
### 5.1 Project Planning
1. Requirements analysis
2. Database and table design
3. Business logic implementation
4. QR-code integration
5. Verification and notification implementation
6. Reports and dashboard creation
7. Testing and documentation

## 6. Functional and Performance Testing
### 6.1 Performance Testing
Functional checks cover fare calculation, ticket verification, QR generation, notifications, cancellation validation, reports, and dashboard functionality.

Formal load testing and performance benchmarking remain future work.

## 7. Results
### 7.1 Output Screenshots
Add screenshots of:
- Ticket booking
- Fare calculation
- Generated QR code
- Ticket verification
- Email notification
- Cancellation validation
- Dashboard
- Reports

## 8. Advantages & Disadvantages
### Advantages
- Centralized ticket records
- Automated fare calculation
- QR-code generation
- Ticket-status verification
- Administrative reporting

### Disadvantages
- QR generation depends on an external service.
- Payment gateway integration is not implemented.
- Additional security and performance testing is needed.

## 9. Conclusion
The project demonstrates a ServiceNow-based metro ticket workflow with automated fare calculation, ticket generation, verification, notifications, and reporting.

## 10. Future Scope
- Payment gateway integration
- Passenger-facing portal
- Improved route planning
- Ticket PDF generation
- Expanded security and performance testing

## 11. Appendix
### Source Code
ServiceNow scripts and configuration can be exported from the application for documentation.

### Dataset Link
Station and fare records are maintained in the ServiceNow application.

### GitHub & Project Demo Link
Repository: https://github.com/nakkadharanigoud/metro-ticket-generating-system.git
Demo video: Add your video link after uploading.
