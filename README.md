# Meeting Cost Calculator - CSCI410 Project 1

## Project Status
*Setup in Progress* - Android Studio installation completing. Full code implementation pending.

## Project Plan (Ready for Implementation)

### App Description
A single-screen Android application that calculates meeting costs based on attendee salaries and meeting duration.

### Technical Specifications
- *Platform*: Android
- *Language*: Java
- *IDE*: Android Studio
- *Architecture*: Single Activity, No Database

### Features to Implement
1. *Basic Calculator*
   - Input: Hourly salary, meeting duration
   - Output: Total meeting cost
   - Real-time calculation

2. *UI Components*
   - Salary input field (EditText)
   - Duration input field (EditText) 
   - Calculate button (Button)
   - Result display (TextView)

3. *Business Logic*
   ```java
   // Calculation formula
   totalCost = hourlySalary * (meetingMinutes / 60)
