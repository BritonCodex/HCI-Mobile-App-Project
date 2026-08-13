## Group Members

| No. | Name | Registration Number |
|---|---|---|
| 1. | Collins Arusei | C025-01-1363/2023|
| 2. | Christine Wanjiru | C025-01-0607/2023 |
| 3. | Corrine Rita | C025-01-0627/2023 |
| 4. | Cecilia Wanjiku | C025-01-0644/2023 |
| 5. | Briton Kiptoo | C025-01-0670/2023 |
# DeKUT Hostel Connect

## Project Overview

**DeKUT Hostel Connect** is a mobile accommodation booking prototype designed to simplify the process of finding, comparing, and booking student accommodation around Dedan Kimathi University of Technology (DeKUT).

The prototype provides students with a centralized platform where they can search for available hostels, filter rooms according to their preferences, compare different room options, make bookings, complete payments, and manage their bookings after confirmation.

This project was developed as a collaborative group project, with all five members contributing to the design, prototyping, testing, documentation, and GitHub submission.

---

## Problem Statement

Students looking for accommodation around DeKUT may have difficulty finding reliable information about available rooms, prices, room types, amenities, and booking procedures. Information can be scattered across different sources, making it difficult for students to compare accommodation options and make informed decisions.

The existing process can also involve unnecessary movement, communication delays, uncertainty about room availability, and difficulties during the booking and payment process.

**DeKUT Hostel Connect** addresses these challenges by providing a centralized and user-friendly accommodation booking interface.

---

## Project Objectives

The main objectives of the prototype are to:

* Provide students with an easy way to search for available accommodation.
* Allow users to filter rooms based on accommodation preferences.
* Enable comparison of different rooms and their features.
* Provide detailed information about hostels and available amenities.
* Guide users through the accommodation booking process.
* Collect essential student and booking information.
* Provide an error-prevention mechanism during form completion.
* Demonstrate a payment process using M-Pesa.
* Provide booking confirmation and reference information.
* Allow users to view and manage their existing bookings.
* Provide check-in information and a QR-code-based check-in concept.

---

## Key Features

### 1. User Login

The prototype begins with a login screen where users can enter their Email/Student ID and password.

### 2. Home Dashboard

The dashboard allows users to:

* Search for accommodation.
* Filter rooms by type.
* View hostel listings.
* See accommodation prices.
* View available rooms.
* Navigate between major sections of the application.

### 3. Hostel Details

Users can view detailed information about a selected hostel, including:

* Hostel name
* Amenities
* Wi-Fi availability
* Water availability
* Security information
* Available rooms

### 4. Search and Filtering

Users can search for accommodation and filter results according to room preferences such as:

* All
* Single
* Shared

The prototype also demonstrates search results for shared rooms near campus.

### 5. Room Comparison

The comparison interface allows users to compare room options based on features such as:

| Feature  | Standard Room          | Premium Room           |
| -------- | ---------------------- | ---------------------- |
| Price    | Displayed in prototype | Displayed in prototype |
| En-suite | Compared               | Compared               |
| Space    | Compared               | Compared               |

Users can then select either the Standard or Premium option.

### 6. Room Selection

After browsing available accommodation, users can select a specific room from a list of available rooms.

Example rooms include:

* Room 101
* Room 102

Each room contains a thumbnail, room identification and selection button.

### 7. Booking Form

The booking form collects important information from the user, including:

* Full Name
* Student Registration Number
* Phone Number
* Move-in Date

Placeholder text is provided inside input fields to improve usability and guide users when entering information.

### 8. Error Prevention

The prototype includes an error state demonstrating how the system handles incomplete information.

For example, when the Student Registration Number is missing:

> *Registration number is required

The input field is highlighted to clearly communicate the problem to the user.

### 9. Payment

The payment screen provides a summary of the booking cost and demonstrates an M-Pesa payment process.

The user is required to provide an M-Pesa phone number before confirming the payment.

### 10. Booking Confirmation

After completing the booking process, users receive a confirmation screen containing:

* Booking confirmation message
* Booking reference number
* Option to view their bookings

### 11. My Bookings

The My Bookings section allows users to view their accommodation bookings, including:

* Hostel name
* Booking dates
* Payment status
* Booking information

Paid bookings are clearly identified using a status indicator.

### 12. Booking Details and Check-in

Users can access detailed information about their booking and view a QR-code placeholder intended for check-in.

The screen also provides instructions on presenting the QR code to the caretaker upon arrival.

---

## Prototype Screens

The completed prototype consists of **12 interconnected screens**:

1. Splash / Login
2. Home Dashboard
3. Hostel Details
4. Filter / Search Results
5. Compare Rooms
6. Room Selection List
7. Booking Form
8. Form Error State
9. Payment Gateway
10. Booking Confirmation
11. My Bookings List
12. Booking Details / Check-in Status

The screens are connected to demonstrate the complete user journey from login through accommodation search, room selection, booking, payment, and post-booking management.

---

## Human-Computer Interaction (HCI) Considerations

HCI principles were incorporated throughout the prototype to improve usability and user experience.

### Consistency

Similar buttons, labels, navigation elements and layouts are used throughout the prototype to create a consistent interface.

### Visibility

Important actions such as **Login**, **View Rooms**, **Select**, **Next**, and **Confirm & Pay** are made clearly visible to users.

### Error Prevention

The booking form includes validation feedback for missing required information. The error state demonstrates how users are informed when the Student Registration Number has not been entered.

### User Feedback

Users receive feedback after important actions, particularly after completing a booking and payment.

### Simple Navigation

A bottom navigation bar is used to provide straightforward access to major areas of the application.

### Clear Information Presentation

Accommodation information is presented using hostel cards, room lists, labels, prices and comparison tables to make information easier to understand.

---

## Prototype Development

The prototype was designed using **Balsamiq**. The team created individual screens and subsequently consolidated them into one master prototype.

The completed screens were linked together to simulate the intended navigation flow of the proposed system.

The main prototype flow is:

```text
Login
   ↓
Home Dashboard
   ↓
Search / Filter
   ↓
Hostel Details
   ↓
Compare Rooms
   ↓
Available Rooms
   ↓
Booking Form
   ↓
Error Validation (where applicable)
   ↓
Payment
   ↓
Booking Confirmation
   ↓
My Bookings
   ↓
Booking Details / Check-in
```

---

## Usability Testing

The completed prototype was reviewed to identify usability issues and ensure that the main booking process could be followed logically.

Testing focused on:

* Ease of navigation
* Clarity of labels and buttons
* Search and filtering
* Room comparison
* Booking form usability
* Error handling
* Payment flow
* Booking confirmation
* Viewing existing bookings
* Check-in information

The findings from the usability testing were documented and included in the project repository.

---

## Project Repository Structure

The GitHub repository is organized as follows:

```text
DeKUT-Hostel-Connect/
│
├── docs/
│   └── usability-testing-notes.txt
│
├── prototype/
│   ├── screen-01-login.png
│   ├── screen-02-home-dashboard.png
│   ├── screen-03-hostel-details.png
│   ├── screen-04-search-results.png
│   ├── screen-05-compare-rooms.png
│   ├── screen-06-room-selection.png
│   ├── screen-07-booking-form.png
│   ├── screen-08-error-state.png
│   ├── screen-09-payment.png
│   ├── screen-10-booking-confirmation.png
│   ├── screen-11-my-bookings.png
│   ├── screen-12-booking-details.png
│   └── DeKUT-Hostel-Connect-Prototype.pdf
│
└── README.md
```

---

## Team Collaboration

This project was completed collaboratively by **five group members**. Each member contributed to different aspects of the prototype, including screen design, booking flow, HCI considerations, payment and error handling, post-booking management, documentation, and testing.

The project was consolidated into a single prototype to ensure that the screens form one complete user journey rather than disconnected individual designs.

GitHub was used for version control and collaboration, allowing the team's contributions and project development to be documented through repository commits.

---

## Technologies and Tools Used

| Tool / Technology | Purpose                                   |
| ----------------- | ----------------------------------------- |
| **Balsamiq**      | Wireframe and prototype design            |
| **GitHub**        | Version control and project collaboration |
| **Markdown**      | Project documentation                     |
| **PDF Export**    | Sharing the clickable prototype           |
| **PNG Export**    | Providing individual prototype screens    |

---

## Project Deliverables

The completed project includes:

* A 12-screen Balsamiq prototype
* A linked/clickable prototype flow
* Exported PNG images of the prototype screens
* A clickable PDF prototype
* Usability testing documentation
* Project README documentation
* GitHub repository containing the project files

---

## Conclusion

**DeKUT Hostel Connect** demonstrates a proposed digital solution for improving the student accommodation booking experience around DeKUT.

The prototype brings together accommodation discovery, searching, filtering, room comparison, room selection, booking, payment, confirmation, and post-booking management into one user-centered workflow.

Although the current implementation is a prototype rather than a fully functional booking system, it establishes the user interface, navigation structure, interaction flow, and HCI considerations that can guide the future development of the complete accommodation management system.

---

## Team Members

This project was developed by a five-member team:

1. **Member 1** – Onboarding and Home Dashboard
2. **Member 2** – Search and Room Comparison
3. **Member 3** – Booking Flow
4. **Member 4** – Error Prevention and Payment
5. **Member 5** – Post-Booking and Booking Management

All members contributed to the completion, review, testing, consolidation, and documentation of the final prototype.
