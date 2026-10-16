FEROZO BITES — WEBSITE + ADMIN PACKAGE

WHAT IS INCLUDED
- index.html: original Ferozo Bites storefront preserved, with an additional live-products area that reads active products from Supabase. Existing product/packaging imagery and contact links are not intentionally changed.
- admin.html: Supabase email/password login, product add/edit/delete, image upload, review moderation and order view.
- admin-config.js: existing Supabase project URL is filled in; public anon/publishable key is still a placeholder because it is not present in the supplied package.
- supabase-schema.sql: tables, row-level security and storage setup.
- sitemap.xml and robots.txt.

IMPORTANT HONEST STATUS
This package cannot be fully live-secure until the real Supabase publishable/anon key is inserted and the SQL is run in the Supabase project. The browser key is intended to be public; NEVER place a service_role/secret key in these files. Admin login also requires the owner account to exist in Supabase Auth and have app_metadata.role=admin. The SQL script promotes owaisferozi505@gmail.com if that exact account exists.

DEPLOY
Upload the extracted FILES (not the ZIP itself) to the ROOT of the GitHub repository connected to Netlify. Netlify will deploy automatically if that repository is configured.

ADMIN URL
https://ferozobites.netlify.app/admin.html

GOOGLE SEARCH CONSOLE
No real Google verification token was included in the available package, so a valid token cannot be invented. Use the exact HTML meta token or HTML file Google gave you, then deploy it. Submit https://ferozobites.netlify.app/sitemap.xml after verification. Google indexing and business registration are separate processes and are not automatically completed by uploading website code.

PRODUCTS
The original product cards remain intact. New active products created in the admin dashboard are shown in the added “New arrivals & extra favourites” section once Supabase is configured. Image uploads accept JPG/PNG/WebP/AVIF up to 5 MB.