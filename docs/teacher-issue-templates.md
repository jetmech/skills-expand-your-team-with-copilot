# Issue Template Guide for Teachers

## Overview

We've created structured issue templates to help teachers easily request changes to the Mergington High School Activities system. These templates ensure that all necessary information is provided so that technical staff or automated coding assistants can quickly understand and implement your requests.

## Available Templates

### 🐛 Bug Report
**Use when:** Something isn't working correctly
**Example scenarios:**
- Students can't register for an activity
- Login page shows error messages
- Activity information displays incorrectly

**What it provides:** Step-by-step reproduction instructions, impact assessment, urgency level

### ✨ Feature Request  
**Use when:** You want new functionality added
**Example scenarios:**
- Add capacity limits for activities
- Create a waitlist system
- Add email notifications for registrations

**What it provides:** Clear problem definition, proposed solution, acceptance criteria, user stories

### 📝 Content Update
**Use when:** You need to change text, schedules, or activity information
**Example scenarios:**
- Update Chess Club meeting times
- Change activity descriptions
- Add new activities to the system

**What it provides:** Current vs. new content, approval tracking, deadline information

### 🎨 UI/UX Improvement
**Use when:** The interface is confusing or hard to use
**Example scenarios:**
- Registration buttons are hard to find
- Mobile version doesn't work well
- Need better accessibility features

**What it provides:** User experience analysis, specific improvement suggestions, success criteria

### ⚡ Performance Issue
**Use when:** The system is slow or unresponsive
**Example scenarios:**
- Pages take too long to load
- System crashes during peak registration
- Search function is slow

**What it provides:** Performance measurements, peak usage patterns, business impact

### ❓ Question or Help Request
**Use when:** You need help using the system or have questions
**Example scenarios:**
- How do I add a new activity?
- Can't find the teacher dashboard
- Need training on system features

**What it provides:** Structured help request with context and urgency

## How These Templates Help

### For Teachers
- **No technical knowledge required** - Templates use plain language
- **Guided questions** ensure you don't forget important details
- **Clear examples** show exactly what information to provide
- **Priority levels** help communicate urgency appropriately

### For Technical Implementation
Each template collects the essential information needed for automated coding assistants:

1. **Clear problem description** - What needs to be changed and why
2. **Acceptance criteria** - How to know when the task is complete
3. **Implementation hints** - Technical suggestions and constraints
4. **Context and limitations** - Related information that affects the solution

## Example: Using the Feature Request Template

**Before templates:** "Can we limit how many students sign up for activities?"

**With template guidance:**
```
Feature Title: Add activity capacity limits
Problem: Chess Club only has 12 seats but unlimited students can register
Solution: Teachers set max participants, system prevents over-enrollment
Acceptance Criteria: 
- ✓ Teachers can set capacity when creating activities
- ✓ Registration disabled when full
- ✓ Students see "Activity Full" message
User Stories:
- As a teacher, I want to set limits so I don't get overwhelmed
- As a student, I want to know if an activity is full before trying
```

This detailed information allows automated tools to implement the feature correctly without back-and-forth clarification.

## Getting Started

1. Go to the repository's Issues page
2. Click "New Issue"
3. Choose the appropriate template
4. Fill out all required fields (marked with red asterisks)
5. Submit your request

The templates will guide you through providing all the necessary details to get your request resolved quickly and accurately.