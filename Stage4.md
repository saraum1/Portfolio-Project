# 1. Sprint Planning and Definition

## Sprint Planning Approach

During Stage 4, the team organized the development process using weekly sprints to divide the workload into smaller and manageable tasks. The sprint planning phase focused on converting the user stories and technical requirements from Stage 3 into implementable development tasks.

The team used the MoSCoW prioritization method to classify features based on importance and MVP requirements. Core functionalities such as authentication, frontend interfaces, backend APIs, and database integration were treated as Must Have features to ensure the platform could operate successfully.

User stories were broken down into smaller tasks and distributed among team members according to their technical responsibilities and areas of expertise.

---

## Sprint Duration

The project development phase was divided into weekly sprints. At the end of each sprint, the team conducted review meetings to evaluate progress, discuss completed work, identify blockers, and prepare tasks for the following sprint.

---

## Sprint Prioritization

### Must Have
- User registration and login system
- Frontend pages and routing
- Backend API development
- Database setup and integration
- Frontend-backend connection
- Authentication and authorization

### Should Have
- Form validation
- UI responsiveness improvements
- Better user experience enhancements

### Could Have
- Additional styling improvements
- Minor feature enhancements

### Won’t Have
- Online payment integration
- Real-time chat system
- AI recommendation system

---

## Task Dependencies

The team identified dependencies between tasks before development started. Frontend development depended on API structures and authentication workflows, while backend integration depended on database configuration and endpoint implementation.

To reduce delays, frontend and backend tasks were developed in parallel whenever possible, with continuous communication between members to ensure compatibility between APIs and UI components.

---

## Team Responsibilities

| Team Member | Responsibilities |
|-------------|------------------|
| Sara Almawkili | Frontend development, UI implementation, routing, and interface design |
| Roya Alahmari | Sprint planning, task management, progress tracking, coordination, and feature validation |
| Ghalyah Alotaibi | Backend development, API implementation, authentication, and database integration |
| Rateel Bahathek | Documentation support, testing activities, backend support, and QA coordination |

**Table 1: Sprint Responsibilities**

---

## Sprint Management Tools

The team used ClickUp to organize sprint activities, assign tasks, track deadlines, and monitor progress throughout development.

GitHub was used for source control management. The project followed a branching strategy using:
- `main` branch for the stable version
- `development` branch for active development work

Code changes were pushed regularly to GitHub during each sprint cycle.

---

# Sprint Task Breakdown

## Sprint 1 Task Breakdown

| Day | Feature | Main Tasks | Tools Used | Testing Type |
|------|------|------|------|------|
| Day 1 | Register + Role Selection | Role selection page, client/company register forms, register API, users/companies tables | React, Node.js, Express, PostgreSQL, bcrypt, GitHub | API testing with Postman, UI testing, validation testing |
| Day 2 | Login + Logout | Login page, login API, JWT token, save token, logout button | React, Node.js, Express, JWT, localStorage/sessionStorage, GitHub | API testing, UI testing, authentication testing |
| Day 3 | Current User Profile `/me` | Protected route, token verification, fetch logged-in user data, show role-based profile data | React, Node.js, Express, JWT middleware, PostgreSQL | Authorization testing, API testing, integration testing |
| Day 4 | Edit + Delete + Reset Password | Edit profile page, delete account, forgot/reset password, update user/company data | React, Node.js, Express, PostgreSQL, bcrypt, Postman | CRUD testing, security testing, end-to-end testing |

**Table 2: Sprint 1 Development Tasks**

---

## Sprint 2 Task Breakdown

| Day | Feature | Main Tasks | Tools Used | Testing Type |
|------|------|------|------|------|
| Day 1 | Client Home Page | Develop client home interface, navigation bar, hero section, responsive layout, routing setup | React, Vite, CSS, GitHub | UI testing, responsive testing |
| Day 2 | Company Interfaces | Build full construction, partial construction, and material supplier interfaces and dashboards | React, Node.js, Express, PostgreSQL | UI testing, integration testing |
| Day 3 | Frontend-Backend Integration | Connect frontend pages with backend APIs, fetch user/company data, authentication integration | React, Express, JWT, PostgreSQL, Postman | API testing, integration testing |
| Day 4 | Validation and User Experience | Add form validation, error handling, protected routes, improve user experience and navigation flow | React, JWT, bcrypt, Postman | Validation testing, authentication testing, end-to-end testing |

**Table 3: Sprint 2 Development Tasks**

---

## Sprint 3 Task Breakdown

| Day | Feature | Main Tasks | Tools Used | Testing Type |
|------|---------|------------|------------|--------------|
| Day 1 | Company Dashboard & APIs | Develop company dashboard interfaces and create backend APIs for company data and authentication | React, Node.js, Express, PostgreSQL, JWT, GitHub | UI testing, API testing |
| Day 2 | Company Profiles | Build frontend company profile pages and implement backend endpoints for creating and updating company profiles | React, Express, PostgreSQL, Postman | CRUD testing, integration testing |
| Day 3 | Services & Products Management | Create frontend interfaces for managing services/products and develop backend APIs for adding, editing, and deleting data | React, Node.js, Express, PostgreSQL | API testing, form validation testing |
| Day 4 | Request Management & Integration | Implement request management pages and connect frontend interfaces with backend APIs for updating request status and tracking data | React, Express, JWT, PostgreSQL, Postman | Integration testing, authentication testing, end-to-end testing |

**Table 4: Sprint 3 Development Tasks**

---

## Sprint 4 Task Breakdown

| Day | Feature | Main Tasks | Tools Used | Testing Type |
|------|---------|------------|------------|--------------|
| Day 1 | UI Redesign | Update the website design, improve layout consistency, adjust colors, spacing, and page structure | React, Vite, CSS, GitHub | UI testing, responsive testing |
| Day 2 | Frontend Bug Fixing | Fix navigation issues, form errors, layout problems, and user interface inconsistencies | React, CSS, GitHub | UI testing, validation testing |
| Day 3 | Backend Bug Fixing | Fix API errors, database connection issues, authentication problems, and request handling bugs | Node.js, Express, PostgreSQL, JWT, Postman | API testing, integration testing |
| Day 4 | Final Testing & Review | Test the full system, verify frontend-backend integration, review completed features, and prepare for final delivery | React, Express, PostgreSQL, ClickUp, GitHub | End-to-end testing, regression testing .

---
# 2. Execute Development Tasks

## Development Execution

During Stage 4, the team focused on implementing the planned MVP features according to the sprint plan. Development tasks were completed incrementally during each sprint while following coding standards, documentation practices, and collaborative workflows.

Frontend and backend development were executed in parallel to improve productivity and reduce integration delays between system components.

The team successfully implemented the following features during development:
- User authentication system
- Client and company registration workflows
- Login and logout functionality
- Role-based interfaces
- Client home page and dashboards
- Company profile management
- Services and product management
- Request tracking and status updates
- Frontend-backend integration
- Database integration and API communication

---

## Frontend Development

The frontend was developed using React and Vite. The team implemented responsive interfaces and organized navigation structures to improve usability and user experience.

Implemented frontend features included:
- Authentication pages
- Role selection pages
- Client dashboards
- Company interfaces
- Navigation and routing
- Form validation
- Responsive layouts
- Protected routes

---

## Backend Development

The backend was implemented using Node.js and Express. APIs and authentication workflows were integrated successfully with PostgreSQL.

Implemented backend features included:
- REST API endpoints
- JWT authentication
- Database models and relationships
- Request handling
- Role-based authorization
- CRUD operations
- Frontend-backend integration

---

## Source Control Management (SCM)

GitHub was used as the main source control platform during development.

The team followed a branching strategy consisting of:
- `main` branch for the stable version
- `development` branch for ongoing implementation

Code changes were pushed regularly to GitHub, and development activities were organized through branches to maintain project stability and reduce merge conflicts.

---

## Quality Assurance and Testing

QA activities were performed continuously during development to verify completed features and identify bugs early.

Testing activities included:
- API testing using Postman
- Authentication testing
- UI testing
- Validation testing
- CRUD operation testing
- Integration testing
- End-to-end testing

The team fixed multiple frontend and backend bugs during testing to improve system stability, performance, and user experience.

---

# 3. Monitor Progress and Adjust

## Progress Monitoring

Throughout Stage 4, the team continuously monitored development progress to ensure sprint goals were completed on time and according to the project plan.

Weekly meetings were conducted at the end of each sprint to:
- Review completed tasks
- Discuss blockers and technical issues
- Evaluate development progress
- Verify implemented features
- Prepare tasks for the next sprint

These meetings helped maintain communication between team members and ensured alignment between frontend and backend development activities.

---

## Task Tracking and Coordination

The team used ClickUp as the main project management tool to organize and monitor sprint activities.

ClickUp was used to:
- Assign tasks to team members
- Track task status and completion progress
- Organize sprint workflows
- Monitor deadlines and priorities
- Adjust tasks when necessary

The team updated task progress continuously during development to maintain visibility of completed and pending work.

---

## Team Collaboration

Frontend and backend developers communicated regularly during implementation to reduce integration issues and ensure compatibility between APIs and frontend interfaces.

Tasks were reassigned or adjusted when needed to keep the development process on schedule and avoid delays.

---

## Sprint Metrics

The team monitored several indicators during development, including:

| Metric | Description |
|--------|-------------|
| Sprint Velocity | Number of completed tasks during each sprint |
| Task Completion Rate | Percentage of completed tasks compared to planned tasks |
| Bug Resolution Rate | Number of identified and fixed bugs |
| Integration Success | Successful frontend-backend connectivity and API communication |

**Table 6: Sprint Monitoring Metrics**

---

## Challenges and Adjustments

During development, the team faced some technical and integration challenges, especially while connecting frontend interfaces with backend APIs and managing multiple user roles.

To address these issues, the team:
- Increased communication between members
- Reviewed incomplete tasks during sprint meetings
- Fixed bugs continuously during development
- Adjusted priorities when necessary
- Improved testing activities before moving to the next sprint

These adjustments helped maintain project stability and improve overall development progress.

---

# 4. Conduct Sprint Reviews and Retrospectives

## Sprint Reviews

At the end of each sprint, the team conducted review meetings to evaluate completed development tasks and verify implemented features.

During these meetings, team members presented completed frontend and backend functionalities, discussed development progress, and reviewed the integration status between different system components.

The sprint reviews helped the team:
- Verify completed features
- Identify incomplete tasks
- Review frontend-backend integration
- Discuss technical issues and blockers
- Prepare tasks for the following sprint

Completed features such as authentication, dashboards, APIs, routing, and request management workflows were reviewed continuously during these meetings.

---

## Retrospectives

After reviewing sprint progress, the team conducted retrospectives to evaluate the overall development process and identify opportunities for improvement.

The retrospectives focused on:
- What worked well during development
- Technical and communication challenges
- Workflow improvements for future sprints
- Task management effectiveness
- Testing and bug fixing processes

---

## What Worked Well

Several practices contributed positively to the development process, including:
- Clear task distribution between members
- Regular communication and coordination
- Effective use of ClickUp for sprint management
- Continuous frontend-backend collaboration
- Organized GitHub workflow and version control practices

The team also managed to complete the planned MVP features within the scheduled sprint timeline.

---

## Challenges Faced

During development, the team faced some technical and workflow challenges, including:
- Frontend-backend integration issues
- Managing multiple user roles and interfaces
- Time management during implementation and testing
- Resolving authentication and API-related bugs

Most issues were addressed through team discussions, testing activities, and continuous collaboration between frontend and backend development members.

---

## Improvements for Future Sprints

Based on retrospective discussions, the team identified several improvements for future development phases:
- Increase testing earlier during implementation
- Improve API documentation updates
- Continue enhancing UI consistency and responsiveness
- Allocate additional time for bug fixing and integration testing
- Maintain regular sprint review meetings and progress tracking

These retrospective activities helped the team improve communication, maintain project organization, and enhance the overall development workflow.

---

# 5. Final Integration and QA Testing

## Final Integration

During the final phase of Stage 4, the team focused on integrating all frontend and backend components to ensure the MVP worked as a complete and connected system.

The integration process included:
- Connecting frontend interfaces with backend APIs
- Verifying authentication and authorization workflows
- Testing database operations and API responses
- Ensuring correct routing and protected page access
- Verifying role-based functionality for clients and companies

The team confirmed that frontend pages successfully communicated with backend services and that user data, requests, and authentication processes worked correctly across the system.

---

## QA Testing Activities

Quality Assurance activities were conducted continuously before the final delivery phase to identify bugs, validate functionality, and improve system stability.

Testing activities included:
- API testing using Postman
- Authentication and authorization testing
- CRUD operation testing
- Frontend UI testing
- Responsive design testing
- Validation testing
- Integration testing
- End-to-end testing

The team manually tested the implemented features to ensure proper system behavior under different usage scenarios.

---

## Bug Fixing and Improvements

Several frontend and backend bugs were identified and resolved during the QA phase.

Frontend fixes included:
- Navigation and routing issues
- Layout inconsistencies
- Form validation problems
- Responsive UI improvements

Backend fixes included:
- Authentication and JWT issues
- API response handling
- Database connection problems
- Request and data validation improvements

These fixes improved overall system performance, usability, and stability.

---

## Final System Verification

Before finalizing the MVP, the team reviewed all completed features and verified that the core project requirements were functioning correctly.

The final verification process confirmed:
- Successful frontend-backend integration
- Stable authentication workflows
- Correct database operations
- Proper request management functionality
- Functional role-based interfaces
- Stable user experience across implemented pages

The MVP was successfully prepared for final delivery after completing the integration and QA testing phase.

---

## Testing Tools

| Tool | Purpose |
|------|---------|
| Postman | API and endpoint testing |
| React Developer Tools | Frontend debugging and UI verification |
| Browser DevTools | Responsive testing and frontend debugging |
| PostgreSQL | Database verification and query testing |
| GitHub | Version tracking and bug fix management |
