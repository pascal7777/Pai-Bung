# Pai-Bung
Tourist app for sites in Lao PDR 

Based on a Colt Steele's Yelpcamp (Bootcamp 2023), UI tweaked to Lao context.

Two main bugs persisted:
1 - Login and returnTo is not functioning as it should. A login for a new site returns the login page with a success flash (welcome back). Login on Homepage commented out because the /login in Homepage navbar has similar bug.
2 - tried several ways to make sure that reviews and images (cloudinary) are deleted when a site is deleted but this does not seem to be working.
