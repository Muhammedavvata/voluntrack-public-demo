# VolunTrack Public Demo

VolunTrack is a volunteer campaign management platform that helps organizers create and manage volunteering campaigns, while allowing volunteers to discover opportunities, apply to campaigns, track their participation, and build a trusted public volunteering profile.

This repository is a public demo version used to present the project idea, main features, and backend concepts safely without exposing private database files, uploaded files, or sensitive configuration.

## Overview

VolunTrack provides a centralized web platform where organizers can create campaigns, volunteers can apply to participate, and completed participation can be reflected through points, badges, certificates, posts, and public profiles.

## Main Features

- User registration, login, and profile management
- Public user profiles
- Campaign creation and management
- Volunteer applications
- Campaign lifecycle tracking
- Points system for volunteers and organizers
- Badge levels based on user activity
- Certificate generation and download
- Campaign-related posts
- Feedback, ratings, and comments
- Notifications for important campaign updates
- Forgot password and reset password flow

## Campaign Lifecycle

Upcoming → Confirmed → Active → Completed

Alternative path:

Upcoming → Cancelled

## Tech Stack

### Frontend

- HTML
- CSS
- JavaScript

### Backend

- Node.js
- Express.js

### Database

- MySQL

### Security

- Password hashing
- JWT-based authentication
- Protected routes
- Secure password reset tokens
- Environment variables for sensitive data

## Backend Concepts Practiced

- REST API routes
- Controllers and middleware
- CRUD operations
- Authentication and authorization
- Password hashing with bcrypt
- JWT authentication
- SQL queries and database relationships
- Error handling
- API testing with Postman
- Git and GitHub collaboration

## Note

The original development repository is private because it may contain database dumps, uploaded files, and local configuration files.

This public repository is used to present the project safely.
