BEAUTY MASS SALOON - UPDATED DEMO

Open index.html in a browser to preview the salon website and admin demo.

Features retained:
- Existing public salon website, admin login, dashboard, billing, customer records,
  appointment management, feedback, settings and gallery controls.
- Existing data keys and browser data are retained.

Features added in this update:
- Workers & Salaries admin section: add/edit staff profiles, phone, skill/department,
  joining date, status, notes and monthly salary; record dated salary payments and
  review salary payment history.
- Appointment booking displays active services grouped under their departments,
  so clients can choose one or more services. Admins can manage the names shown in the client's
  “Preferred by” dropdown in Admin > Settings, without adding worker or salary
  records. Use “Add person” to create a name field for each person, then save
  settings.
- Department is selected whenever a new service is created; service records support
  an uploaded image (up to 1.5 MB) or an image URL.
- Public service cards display a service image, with department-based fallback images
  when a custom image has not been uploaded.
- Beard services use the supplied beard-style image at assets/beard-service.png
  unless a custom service image is set.
- Footer includes contact details and polished Facebook, Instagram and TikTok links.
  Set the actual social profile URLs in Admin > Settings.
- Google Maps embed defaults to Beauty Mass Mens Hair Saloon, Sheikhupura, Punjab,
  Pakistan. Edit the map search text in Admin > Settings if the pin/search result
  needs to be made more precise.
- Receipt heading and sales report branding use BEAUTY MASS SALOON.

IMPORTANT BACKEND NOTE:
This supplied project is a standalone HTML/JavaScript demo. It stores workers,
appointments, salary payments, feedback, gallery uploads and admin data in browser
localStorage. Data is available in the same browser/origin only and is not shared
securely between different customers/devices. Connect a hosted backend/database
(e.g. Supabase/Firebase or the application's API) for shared multi-device records,
secure authentication and persistent image storage. Do not publish demo admin
credentials in a production deployment.
