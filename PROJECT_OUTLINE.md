# FacilityFix — Project Outline

## Purpose and audience
FacilityFix is a mobile-friendly campus maintenance request app for employees and facilities staff.

## Problem
Requests made by phone, email, or word of mouth can be hard to organize and follow up. FacilityFix provides one place to submit, review, and track maintenance tickets.

## Scope
Employees can enter an issue title, category, priority, campus location, floor, room/area, description, and optional photo or GPS coordinates. Facilities staff can review tickets, filter by building or status, and update progress.

## Design and technology
HTML structures the forms and views; CSS provides responsive layouts; JavaScript implements navigation, validation, filtering, image preview, and ticket handling. `localStorage` provides browser-only persistence. The application is not a native Android app.

## Screens
1. Welcome / demo role selection
2. Employee request form
3. Request dashboard and filters
4. Request detail dialog

## Campus coverage
The location selector contains 41 supplied campus locations plus an Other option. Music Building and Security are separate; Wellness Center and Benedictine are separate. Outdoor areas support room/area descriptions.

## Development progression
- **Version 1:** Role selection, requests, status dashboard, browser storage.
- **Version 2:** Photos, image preview, request details, navigation menu.
- **Version 3:** Campus location directory, floor and room fields, GPS, maps, building filter, updated categories.
- **Final documentation:** README, lesson alignment, test plan, GitHub submission and Wiki outline.

## Constraints
The app is a classroom demonstration without verified user identities, server-side access control, or a shared database. Networking (Lesson 11) is intentionally excluded from this submission.

## Success criteria
The application opens in a browser; employees can submit requests; staff can change status; requests persist after refresh in the same browser; photos and location fields can be inspected; campus filters work.
