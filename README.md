# FacilityFix — Campus Maintenance Request App

**Student project | Responsive web application | HTML, CSS, JavaScript**

FacilityFix helps campus employees report maintenance problems and allows facilities staff to view requests and update their progress. It is a classroom prototype intended for use with demonstration data.

## Features

- Demo employee and facilities-staff role selection
- Submit maintenance requests with title, category, priority, description, building, floor, and room/area
- Choose from **41 campus locations** or specify another location
- Categories include Plumbing, Electrical, HVAC, Cleaning, **Grounds**, **Fire Alarm**, and Other
- Attach and preview JPEG, PNG, or WebP photos up to 1 MB
- View ticket details, photo, and optional GPS coordinates with a Google Maps link
- Filter requests by status and campus location
- Staff can change ticket status: Pending, In Progress, Completed
- Save tickets in browser `localStorage` across refreshes in the same browser and origin
- Responsive layout for phone and desktop browsers

## Run the application

1. Download or clone the repository.
2. Open `index.html` in Chrome or Edge. No editor, server, or dependencies are needed for ordinary features.
3. Enter a name and choose **Employee**; create a sample request.
4. Use **Switch user** and choose **Facilities staff** to review and update it.
5. Refresh the page to verify browser persistence.

**GPS note:** Browser geolocation requires permission and typically HTTPS or `localhost`. It may not work from a local `file://` page. GPS is optional.

## Project files

| Path | Purpose |
| --- | --- |
| `index.html` | Forms, views, navigation, dialog, and accessible markup |
| `styles.css` | Responsive layout and visual styling |
| `app.js` | JavaScript state, ticket actions, image handling, storage, and geolocation |
| `docs/PROJECT_OUTLINE.md` | Project purpose, scope, and development plan; ready for GitHub Wiki |
| `docs/LESSON_ALIGNMENT.md` | Lesson-to-code mapping and web/Android distinctions |
| `docs/TESTING.md` | Manual test plan and reported test history |
| `docs/GITHUB_SUBMISSION.md` | Upload, Wiki, README download, and submission instructions |

## Coursework alignment

| Lesson | Web implementation |
| --- | --- |
| 3 — Activities, Fragments, Intents | Login/app views and JavaScript navigation; **web analogy, not Android APIs** |
| 4 — User Interface | Inputs, selects, buttons, dialog, status labels |
| 5 — UI Design | Responsive CSS, labeled forms, layouts |
| 6 — Pictures and Menu Views | Photo picker/preview, detail image, navigation buttons |
| 7 — Data Persistence | `localStorage` with JSON serialization |
| 8 — Content Providers | User-selected file access via File API; **not an Android Content Provider** |
| 10 — Location-Based Services | Campus building/room fields, optional browser geolocation, Google Maps link |
| 11 — Networking | **Out of scope for this submission at student's request** |

See [lesson-to-code documentation](docs/LESSON_ALIGNMENT.md) for exact examples.

## Known limitations and safety

- The login is a **demo role selector**, not authentication. Anyone can choose the staff role.
- Browser storage is device/browser-specific, not shared or secure; clearing site data can erase tickets.
- Large photo attachments can exhaust browser storage. Use small sample photos.
- GPS is optional, permission-based, and may not be available on local file pages.
- Do **not** enter sensitive information or actual security/maintenance incidents. This is not a production system.
- No backend server, shared database, or networking is included in this version.

## Status

Version 1 and Version 2 feature testing was reported successful by the student. The Version 3 campus/location features should be rechecked before final submission; see `docs/TESTING.md`. This package is prepared for GitHub upload, **not yet published to the repository**.

## Repository

https://github.com/bazilefrancois/Facility-Maintenance-Request-App
