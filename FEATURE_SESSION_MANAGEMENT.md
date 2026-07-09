# Feature: Session Management

## Description
Separate activity sessions/lectures from the activities themselves for better granularity.

## Current State
- Activities are treated as single entities
- No way to track individual sessions/meetings
- No session-specific scheduling

## Proposed Changes
- Create session model separate from activities
- Schedule multiple sessions for each activity
- Track attendance per session
- Session-specific details (location, instructor, etc.)
- Calendar view of sessions

## Implementation Details
- Database schema for sessions with foreign keys to activities
- Session CRUD API endpoints
- Session calendar/schedule UI
- Instructor ability to create/manage sessions
- Session attendance tracking

## Related Features
Enables Attendance Tracking and Analytics features
