# Technical Task: Task Management System

## Introduction

Thank you for taking the time to complete this technical task. We understand you may be in full-time employment and have other commitments, so we've designed this task to be completed in a reasonable timeframe whilst still allowing you to demonstrate your skills effectively.

**Expected time commitment:** 3-5 hours (though you have up to 5 days to complete it)

**What we're looking for:** This task is designed to see how you work in your day-to-day environment. Please use:
- Your preferred IDE or code editor
- Any AI coding assistants you normally use (GitHub Copilot, Cursor, ChatGPT, Claude, etc.)
- Your usual development tools and workflows
- Any libraries, frameworks, or packages you'd typically reach for

We want to see how you actually code, not how you code under artificial constraints. The only requirements are the **programming language/framework** and the **functional requirements** outlined below.

## Table of Contents

- [The Task](#the-task)
  - [Core Requirements](#core-requirements)
  - [Bonus Features](#bonus-features-optional)
- [Technology Requirements](#technology-requirements)
  - [For Backend Engineers (Ruby on Rails)](#for-backend-engineers-ruby-on-rails)
  - [For Frontend Engineers (React)](#for-frontend-engineers-react)
- [Deliverables](#deliverables)
  - [README Documentation](#readme-documentation)
  - [Working Application](#working-application)
  - [Tests](#tests)
  - [Code Quality](#code-quality)
- [Submission & Timeline](#submission--timeline)
  - [Repository Setup](#repository-setup)
  - [Granting Access](#granting-access)
  - [Timeline](#timeline)
- [Next Steps](#next-steps)
  - [Technical Interview](#technical-interview)
  - [Questions](#questions)
- [Fair Assessment Commitment](#fair-assessment-commitment)

## The Task

Build a simple **Task Management System** where users can create, view, update, and delete tasks. Think of it as a lightweight version of Trello or Todoist.

### Core Requirements

Your application must allow users to:

1. **Create tasks** with the following properties:
    - Title (required)
    - Description (optional)
    - Status (To Do, In Progress, Done)
    - Priority (Low, Medium, High)
    - Due date (optional)

2. **View all tasks** in a clear, organised interface

3. **Update tasks** - edit any property of an existing task

4. **Delete tasks** - remove tasks from the system

5. **Filter tasks** by at least one criterion (e.g., status, priority)

6. **Search tasks** by title or description

### Bonus Features (Optional)

If you have time and want to demonstrate additional skills, consider implementing:
- Tags or categories for tasks
- Task sorting (by due date, priority, creation date)
- Basic authentication (doesn't need to be production-ready)
- Data persistence across browser sessions (frontend) or proper database storage (backend)
- Responsive design (frontend)
- API documentation (backend)

**Note:** These are truly optional. We'd rather see excellent execution of the core requirements than a rushed implementation of everything.

## Technology Requirements

### For Backend Engineers (Ruby on Rails)

#### Required Technologies
- Ruby on Rails framework
- RESTful API design
- Any database you're comfortable with (PostgreSQL, MySQL, SQLite)

#### Frontend Flexibility
You can build the frontend in any way you're comfortable with. This can be as simple as Rails views with HTML/CSS, a basic React app, or even just a Postman collection demonstrating your API.

**Focus on the backend** - we're primarily evaluating your API design, business logic, and data modelling.

#### What We'll Be Evaluating
- API design and RESTful principles
- Data modelling and database schema
- Validation and error handling
- Code organisation and structure
- Testing approach
- Documentation

### For Frontend Engineers (React)

#### Required Technologies
- React (either React for web or React Native - your choice)
- Modern JavaScript/TypeScript

#### Backend Approach
You should **mock the API calls** and return data you'd expect from real endpoints. Create mock data/fixtures that demonstrate various states.

**Focus on the frontend** - we're primarily evaluating your component architecture, state management, and user experience.

#### What We'll Be Evaluating
- Component architecture and organisation
- State management approach
- User experience and interface design
- Error handling and loading states
- Code quality and readability
- Testing approach

## Deliverables

### 1. README Documentation

Your README must include:

**Overview**
- Brief description of your application and approach

**Setup Instructions**
- Step-by-step guide to get the project running locally
- Prerequisites (Ruby version, Node version, database, etc.)
- Installation steps
- Database setup (backend) or any required configuration
- How to run the application
- How to run tests

> **Note:** We'll be running your application on macOS, so please ensure your instructions work for macOS or provide Docker setup for portability.

**Design Decisions**
- Key technical decisions you made and why

**Trade-offs**
- What you would do differently with more time, budget, or access to production tools (e.g., paid services, monitoring tools, etc.)

**Technology Choices**
- Brief explanation of major libraries/tools used

### 2. Working Application

- The application must run locally on our machines following your README
- All core requirements should be functional
- The application should handle errors gracefully

### 3. Tests

- Include automated tests demonstrating your testing approach
- We're not looking for 100% coverage, but key functionality should be tested
- Document how to run the tests in your README

### 4. Code Quality

- Write clean, readable code as you would in a professional setting
- Use appropriate design patterns and best practices
- Include comments where they add value (but don't over-comment)
- Commit regularly with clear, descriptive commit messages

## Submission & Timeline

### Repository Setup

You have two options:

**Option A: Fork this repository**
- Fork this repository to your own GitHub account
- Make your fork private (we'll explain why below)
- Complete the task in your forked repository

**Option B: Create your own repository**
- Create a new private repository in your GitHub account
- Copy this README if you'd like to keep the instructions handy
- Complete the task in your new repository

#### Why Private?

We ask that your repository remains private to:
- Protect your work from being copied by other candidates
- Keep your application to our company confidential
- Ensure fair assessment - we want to see your original work, not something influenced by seeing others' solutions

### Granting Access

Once you've completed the task:

1. Ensure your repository is **private**
2. Add the following GitHub users as collaborators to your private repository:
    - `adamwhp`
3. Send us an email confirming you've completed the task and granted access

#### How to Add Collaborators
1. Go to your repository settings
2. Navigate to "Collaborators and teams"
3. Click "Add people"
4. Add the usernames provided above

### Timeline

You have **5 days** from receiving this task to complete and submit it. Please let us know if you need more time due to extenuating circumstances.

## Next Steps

### Technical Interview

After you submit your task, we'll schedule a technical discussion (approximately 60 minutes) where you'll:

1. **Demonstrate your application** - Show us the working application via screen share
2. **Walk through your code** - Explain your key technical decisions
3. **Discuss trade-offs** - Talk about what you'd do differently with more time
4. **Answer technical questions** - We'll ask about specific implementation details
5. **Explore improvements** - Discuss how you'd scale or enhance the application

This is a collaborative discussion, not an interrogation. We want to understand your thought process and how you approach problems.

### Questions

If anything is unclear, or you have questions about the requirements, please don't hesitate to reach out to us at the email address provided in your application.

We're here to help and want you to have the best opportunity to demonstrate your skills.

## Fair Assessment Commitment

We're committed to fair and inclusive hiring. This task:
- Does not have hidden trick requirements
- Should be completable by someone with the stated experience level
- Respects your time and other commitments
- Allows you to work in your natural environment with your usual tools

If you feel at any point that this task is unreasonable or unclear, please let us know.

---

**Good luck! We look forward to seeing what you build.**
