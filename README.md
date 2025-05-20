# TaskFlow - Task Management System

A full-stack task management system built with React, Firebase, and Tailwind CSS. TaskFlow allows users to manage tasks efficiently with features like Google OAuth authentication, CRUD operations for tasks, and PDF report generation.

## Features

- **Authentication**
  - Google OAuth 2.0 login
  - Protected routes for authenticated users

- **Task Management**
  - Create, read, update, and delete tasks
  - Task fields: title, description, deadline, assigned to, status
  - Search, sort, and filter capabilities

- **Dashboard**
  - Task summary statistics
  - Quick actions for common tasks

- **PDF Report Generation**
  - Export task lists as formatted PDF reports

- **Responsive Design**
  - Works on mobile, tablet, and desktop devices

## Tech Stack

- **Frontend**
  - React with TypeScript
  - Tailwind CSS for styling
  - Zustand for state management
  - React Router for navigation
  - React Hook Form for form handling

- **Backend**
  - MongoDB Authentication
  - MongoDB Database

- **Other Tools**
  - jsPDF for PDF generation
  - Lucide React for icons
  - date-fns for date formatting

## Getting Started

1. Clone the repository
2. Copy `.env.example` to `.env` and update with your Firebase configuration
3. Install dependencies with `npm install`
4. Start the development server with `npm run dev`

## Project Structure

The project follows a modular architecture with components separated by functionality:

- `/src/components` - Reusable UI components
- `/src/pages` - Page components
- `/src/services` - API services
- `/src/store` - State management
- `/src/types` - TypeScript interfaces and types

## Deployment

To build the app for production, run:

```
npm run build
```
