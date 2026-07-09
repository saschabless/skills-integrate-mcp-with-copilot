# Feature: Persistent Database Storage

## Description
Replace in-memory storage with a persistent SQL database.

## Current State
- All data stored in memory (activities, participants)
- Data lost on server restart
- Not scalable for production use

## Proposed Changes
- Set up SQL database (PostgreSQL, MySQL, or SQLite)
- Create database schema for activities, students, registrations
- Migrate in-memory data to database
- Add ORM (SQLAlchemy) for database operations
- Replace in-memory dictionary with database queries

## Implementation Details
- Database schema design
- SQLAlchemy models
- Data migration from memory to DB
- Connection pooling
- Environment configuration for DB credentials

## Related Features
Enables all other features that rely on data persistence
