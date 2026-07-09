# Feature: Attendance Tracking

## Description
Track attendance for individual activity sessions/lectures.

## Current State
- Only tracks signup/registration
- No attendance at specific sessions
- No session-level data

## Proposed Changes
- Create session/lecture entities separate from activities
- Track attendance for each session
- Attendance management UI for instructors
- Attendance reports for students

## Implementation Details
- Database schema for sessions and attendance records
- Session management API
- Attendance API endpoints (check-in, check-out)
- Attendance UI components for instructors
- Student attendance history view

## Related Features
Works with Session Management, Analytics, and Admin Dashboard
