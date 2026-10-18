# FacilityFix Manual Testing

## Reported prior results

The student reported that **all seven Version 1 tests passed**: open app, enter as employee, submit ticket, view dashboard, switch to staff, update status, and retain ticket after refresh. The student also reported **Version 2 worked**, including photo and navigation enhancements. These are user-reported results, not automated test certificates.

## Final submission checklist — test in your own browser

- [ ] `index.html` opens without an error.
- [ ] Employee can create a ticket at **Kirk Hall** with floor and room.
- [ ] **Music Building** and **Security** are separate location choices.
- [ ] **Wellness Center** and **Benedictine** are separate location choices.
- [ ] **Grounds** and **Fire Alarm** appear as categories.
- [ ] Optional image can be selected, previewed, and seen in ticket details.
- [ ] Staff can filter by campus location and update ticket status.
- [ ] Tickets remain after refresh in the same browser/origin.
- [ ] App is usable on a narrow browser window or phone.
- [ ] GPS works when allowed over HTTPS/localhost, or shows a graceful error if unavailable.
- [ ] No real confidential campus incident information is entered.

## Known testing limitations

`file://` geolocation may fail. Browser `localStorage` is not synchronized between different devices or origins. Image storage is size-limited. Demo role selection is not secure authentication.

## Evidence for submission

Capture screenshots of (1) welcome screen, (2) new request form with campus locations, (3) dashboard showing tickets, and (4) request details with sample photo. Add them to `docs/screenshots/` if required by your instructor; do not fabricate screenshots or use sensitive data.
