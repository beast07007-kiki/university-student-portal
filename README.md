# University Student Portal

An interactive university portal built with HTML, CSS, and JavaScript.

## Run

Download or clone the repository and open `index.html` in a modern browser. Keep `style.css` and `app.js` in the same folder.

## Features

- Student dashboard with academic indicators and upcoming deadlines
- Course overview, syllabus progress, and sample study guide downloads
- Assignment tracker with filters, completion controls, and new assignments
- Weekly timetable with calendar export
- Academic transcript and credit-weighted what-if GPA simulator
- Tuition ledger, statement export, and simulated payments
- Digital student ID with visual QR and NFC demonstrations

Changes to assignments, projected grades, and simulated payments are stored in browser local storage. Clear site data to reset the demo. Browser storage behavior for locally opened files may vary by browser.

## Demo data

All student records, announcements, courses, and deadlines are samples. The semester reference date is October 17, 2026. This application is not connected to a university, Google Drive, a payment processor, or a campus access system. Payments do not transfer money. The ID card cannot grant access. Calendar exports use campus time (Africa/Harare, UTC+2).

Google Fonts is used for typography, with local fallback fonts when unavailable.

## Demo login and About page

Open `login.html` (opening `index.html` redirects there until signed in). Use student ID `NB-2024-00842` and demo password `Northbridge2026!`. Sign out from the portal header. Credentials are public samples; this is not secure authentication. Do not use real passwords. Session state uses sessionStorage; no password is stored. Production authentication needs a backend or identity provider.

The public About page is `about.html`; an About section is also available in the portal sidebar. Keep all HTML, JavaScript and CSS files together.

## Usability update

The dashboard prioritizes the nearest incomplete deadline and the next scheduled class. Dates and deadline statuses use Africa/Harare campus time. Timetables and calendar exports use the displayed week (the next Monday on weekends), with recurring classes limited to the sample semester. Historical academic records and announcements remain sample data. Text contrast, touch targets, and compact mobile layouts have been improved. Secure real accounts and institutional records remain an integration requirement.
