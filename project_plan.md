# Meeting Cost Calculator - Development Plan

## Project Overview
*Course:* CSCI410 Mobile Application Development  
*Project:* Meeting Cost Calculator  
*Timeline:* 1-2 day implementation

## Technical Specifications
- *Platform:* Android
- *Language:* Java
- *IDE:* Android Studio
- *Architecture:* Single Activity
- *Data Storage:* No database (in-memory only)

## Implementation Timeline

### Phase 1: Project Setup 
- [x] Project concept design
- [x] GitHub repository creation
- [x] Android Studio installation
- [ ] Project creation in Android Studio
- [ ] GitHub connection from Android Studio

### Phase 2: Core Features 
- [ ] Create basic UI layout (activity_main.xml)
- [ ] Implement MainActivity.java with calculation logic
- [ ] Connect UI elements to Java code
- [ ] Basic calculation functionality:
  ```java
  // Formula: totalCost = hourlySalary * (meetingMinutes / 60)
  public double calculateMeetingCost(double salary, int minutes) {
      return salary * (minutes / 60.0);
  }
