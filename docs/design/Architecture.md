# Architecture & Components

## Context
Our student support platform helps university students find
study partners and organize academic goals. This section
describes the proposed system components and how they connect.

## Content

### User Interface
- Displays the study-partner search and academic goals pages.
- Allows students to enter course codes and manage their goals.
- Shows search results, progress and error messages.

### Study-Partner Search
- Receives a course code from the user interface.
- Finds matching study-partner profiles in data storage.
- Returns matching profiles or a message when no matches exist.

### Goal Management
- Allows students to create goals with titles and target dates.
- Checks that required information is provided.
- Allows students to mark goals as complete or unfinished.

### Data Storage
- Stores study-partner profiles, course information and goals.
- Keeps each student's goals associated with their account.
- The storage technology is still to be decided.

### How the Components Connect
- The student enters a request through the user interface.
- The search or goal-management component processes the request.
- The component reads or updates the relevant stored data.
- The user interface displays the result to the student.

## Decisions (if any)
- This architecture is a proposal for team review.
- Programming languages, frameworks and storage technology
  are still to be decided.

## Next Steps
- [ ] Confirm the components with the team. Owner: prince uchenna. Due: 2026/10/20.
- [ ] Choose suitable development and storage tools. Owner: prince uchenna. Due: 2026/10/20.