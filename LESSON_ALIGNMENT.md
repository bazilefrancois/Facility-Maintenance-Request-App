# Lesson Alignment — FacilityFix Web Application

This project uses **web technologies**. It demonstrates related design and programming concepts, but does not implement Android-specific APIs.

| Lesson | Where to find it | Explanation / evidence |
| --- | --- | --- |
| **3: Activities, Fragments, Intents** | `index.html`: `loginView`, `appView`, `app-nav`; `app.js`: `showApp()` and navigation listeners | Separate views and navigation model similar user flow; **not Android Activity, Fragment, or Intent classes**. |
| **4: Android User Interface** | `index.html`: `loginForm`, `requestForm`, `statusFilter`, `buildingFilter`, `detailDialog` | Forms, buttons, labels, selects, and dialogs; **HTML controls rather than Android widgets**. |
| **5: Designing User Interface** | `styles.css`; `index.html` viewport metadata and semantic sections | Responsive design, labels, card layout, and small-screen adaptation. |
| **6: Displaying Pictures with Menu Views** | `index.html`: `photo`, `photoPreview`, `app-nav`; `app.js`: file preview and `showDetails()` | Select, preview, and display photos; menu-style navigation. |
| **7: Data Persistence** | `app.js`: `STORAGE_KEY`, `loadRequests()`, `saveRequests()` | JSON serialization to `localStorage`; browser-specific, not a shared database. |
| **8: Content Providers** | `index.html`: file input; `app.js`: `FileReader` and image validation | User-selected image access via browser File API; **not an Android Content Provider**. |
| **10: Location-Based Services** | `app.js`: `CAMPUS_LOCATIONS`, `populateLocations()`, `mapLink()`, geolocation click listener; `index.html`: `building`, `floor`, `room`, `gpsBtn` | Campus selection, optional permission-based GPS, and Google Maps link. |
| **11: Networking** | Not implemented | Deliberately excluded from this submission. No API or shared-server claims. |

## Demonstration script

1. Open `index.html` and enter as an Employee.
2. Create a ticket for **Kirk Hall**, include a room and choose **Grounds** or **Fire Alarm**.
3. Optionally attach a small sample image; preview and submit.
4. Open **View details** to inspect location and photo.
5. Switch to Facilities staff, filter by Kirk Hall, and update status.
6. Refresh the browser and verify that the ticket remains.
7. If served over HTTPS or localhost, optionally test GPS permission and map link.

## Important academic distinction
If the instructor requires actual Java/Android Activities, Fragments, Intents, or Content Providers, this web implementation **does not meet those exact requirements**. It should be submitted as a web-based analogue only if the instructor permits that approach.
