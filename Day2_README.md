# CreatorOS 🚀

## Day 2 Progress Report

**Project:** CreatorOS -- AI-Powered Creator Management Platform\
**Day:** 2

------------------------------------------------------------------------

# Project Overview

CreatorOS is a full-stack web application designed for content creators,
YouTubers, influencers, and freelancers.

Day 2 focused on building the backend authentication system and
integrating a cloud PostgreSQL database.

## Objectives Completed

-   Backend authentication setup
-   PostgreSQL (Neon) integration
-   Prisma ORM configuration
-   User Registration API
-   User Login API
-   Password hashing using bcrypt
-   JWT authentication
-   API testing using Thunder Client

## Technologies Used

-   Node.js
-   Express.js
-   TypeScript
-   PostgreSQL (Neon)
-   Prisma ORM
-   bcrypt
-   JSON Web Token (JWT)
-   Thunder Client

## Backend Folder Structure

``` text
backend/
├── prisma/
├── src/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── routes/
│   ├── services/
│   ├── app.ts
│   └── server.ts
├── .env
├── package.json
└── tsconfig.json
```

## Features Implemented

### User Registration

-   Duplicate email validation
-   Password hashing with bcrypt
-   User stored in PostgreSQL

Endpoint: `POST /api/auth/register`

### User Login

-   Email verification
-   Password verification
-   JWT token generation

Endpoint: `POST /api/auth/login`

## Security Features

-   Password hashing
-   Duplicate email validation
-   JWT authentication
-   Environment variables

## APIs Developed

  Method   Endpoint             Status
  -------- -------------------- --------
  POST     /api/auth/register   ✅
  POST     /api/auth/login      ✅

## Testing

Successfully tested: - Registration - Duplicate email validation -
Login - JWT generation

