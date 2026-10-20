# Data & Content

## Context
Our student support platform helps university students find
study partners and organize academic goals. This section
describes the information the platform needs and how it
should be organized, checked and displayed.

## Content

### Student Profiles
- Each student has a unique user ID.
- Profiles contain a display name and course codes.
- Students may optionally provide their study availability.
- Students enter and update their own profile information.

### Academic Goals
- Each goal has a unique goal ID.
- Each goal is linked to its owner's user ID.
- Goals contain a title, target date and completion status.
- Students can create goals and update their completion status.

### Data Validation
- Display names and goal titles cannot be empty.
- Course codes must follow the agreed course-code format.
- Target dates must be valid dates.
- Completion status must be either complete or unfinished.

### Information Displayed
- Search results show matching students' display names,
  courses and any study availability they choose to share.
- The goals page shows the signed-in student's goals,
  target dates and completion status.
- Clear messages explain when no study partners are found
  or when required information is missing.

### Privacy and Access
- Academic goals should only be accessible to their owner.
- Private contact details should not appear in search results.
- Students should be able to update or remove their information.
- Access restrictions must be enforced by the system.

## Decisions (if any)
- These data requirements are proposed for team review.
- The database technology and exact course-code format
  are still to be decided.

## Next Steps
- [ ] Confirm required and optional fields with the team. Owner: Toufiq EL-Dik. Due: 2026-10-20.
- [ ] Agree on privacy rules and validation details. Owner: Toufiq EL-Dik. Due: 2026-10-20.