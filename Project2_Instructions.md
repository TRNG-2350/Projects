# Project Title: Full-Stack Social App: Spring Boot API + Angular UI

## Code Freeze Thursday, March 12
## Presentation Friday, March 13

## Project Description

For this project, you will Build a full-stack Web Application with a Spring Boot RestAPI backend and an Angular frontend. The Angular application will consume the existing API and present all meaningful backend data in a clean, user-friendly UI.

The full-stack application must support:
- User registration & login
- User profile and account management
- Content management (create, view, edit, delete content)
- A complete UI experience that displays relevant data from the backend and supports common user flows end-to-end
- Component Templates which showcases proper consumption of API endpoint data

## Objective / Tools Used
### Backend
- Java
- Spring Boot (Spring Web)
- H2 Database (in-memory)
- (Recommended) Spring Data JPA
- Maven or Gradle

### Frontend
- TypeScript
- Angular
- Angular Router (multi-page navigation)
- Angular Forms (template-driven or reactive)
- Angular HttpClient (API calls)

### Architecture
#### 3-tier backend architecture
- Controllers
- Backend Services
- Backent Repositories / Data Access

#### Frontend component-based architecture
- Components (UI + user interaction)
- Services (API communication)
- Models/Interfaces (typing API responses)

## Project Type: Individual Project

## Outcome
### “Presentable UI” Requirements
- The Angular frontend must display all meaningful backend information, including:
- Authentication & User Register and login screens
- Logged-in user summary (username, profile info, etc.)
- Ability to view/edit user account details
- Ability to view/edit Content
  - Content feed/list page (all content)
  - Content detail page (single content with full info)
  - Create content page
  - Edit content page
  - Delete content action with confirmation
  - Search/filter/sort content feed
- Clear layout (navigation bar + main content area)
  - Clean display of data (titles, timestamps if available, author info, etc.)
- User-friendly feedback:
  - Validation messages
  - API error messages
  - Loading indicators
    - Empty states (“No content yet”)

### Suggested Pages / Screens (Minimum)
- Home / Content Feed
- Content Details
- Create Content
- Edit Content
- Register
- Login

### Session Handling
- Simple “current session” handling (store token/session flag in localStorage)

### Security
- Basic route guards (prevent navigation to protected pages if not logged in)

Stretch Goals:
- Angular Test Suite
- GCP Deployment

