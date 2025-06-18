# Practicum Project  
PALTUS team. Report 2

## Detailed Requirements Elaboration

### 1. User Management & Progress Tracking
  - Users can mark subtopics as completed.
  - Display user’s course progress (e.g., completed 5/10 lessons).

### 2. Course Management
  - Fetch all user's courses (ID + name) for course selection.
  - Fetch course content - lessons, subtopics, etc.
  - Users can delete courses.
  - Save LLM-generated courses to the database.

### 3. Frontend Application
  - MVP pages: Home, Course View (with lessons), Course Creation View, Login View.
  - Persist progress data in browser storage (local/session).
  - HTTP requests to backend endpoints.

### 4. Backend Services
  - Enable cross-origin requests for frontend-backend communication.
  - Process user inputs via LLM API to generate courses.
  - Optimize database queries for course/lesson retrieval.

### 5. Non-Functional Requirements
  - Responsive layouts
  - In future, code formatting enforced via CI/CD.
  - Docker Compose setup for single-command execution.

### 6. Dependencies & Risks
*Dependencies* 
  - LLM API reliability.
  - Asana backlog prioritization for task alignment.

*Risks* 
  - Inconsistent progress tracking if subtopic/lesson logic fails.
  - CORS misconfiguration blocking frontend requests.



### Prioritized backlog

[Asana board](https://app.asana.com/1/1210531224311325/project/1210531182984698/board/1210531325851441)

## Project specific progress

### *Frontend*

Finished layout for neccessary pages for MVP, configured some libraries for needed functionalities.

### *Backend*

Created functions for getting the course with all the content inside, to get IDs and names of all courses, deleting a course, getting a certain lesson, saving generated course in database.

### *Other*

Created README.md for the project, fixed prompt for LLM-model, finished design of an app in Figma, discussed gamification ideas, set up task board in Asana.

# Weekly commitments

## Individual contribution of each participant

**Sergey Knyazkin** 
  - Created layout for all the pages of MVP
  - Configured Pinia to maintain global state of an app
  - Configured Vue router
  - Configured Axios for HTTP requests

**Ramazan Gizamov** 
  - Added README.md
  - Report for week 2
  - Finished Figma design with working prototype

**Aidar Sarvartdinov** 
  - Created database structure
  - Configured interactions with database
  - Database request optimization
    
**Igor Dubrovsky**
  - Docker configuration
  - Added LLM API integration to communicate with the user

**Amir Fayzullin** 
  - Fixed prompt for LLM model 
  - Added system prompt for validation of user's inputs

**Danil Demin** 
  - Introduced gamification ideas

## Plan for Next Week

### *Frontend*
  - Set up requests
  - Configure storage for a course to track learning
  - Develop a logic for a few frontend features

### *Backend*
  - Add ability to mark subtopic as finished
  - Mark lesson as completed if all subtopics finished
  - Get request for dashboard
  - Calculate last unfinished lesson(for dashboard)
  - Configure CORS for request
  - Refactor books and links entity as just array of values

## Confirmation of the code’s operability

We confirm that the code in the main branch:
Run via docker-compose.



