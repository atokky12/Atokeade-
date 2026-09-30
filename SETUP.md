# ATOKKY real online shop setup

This package provides:
- Public ATOKKY storefront
- Email/password admin login
- Product database
- Product image uploads
- Add/delete products

## Supabase
Create a Supabase project, run schema.sql in SQL Editor, create a Storage bucket named products, and create your admin account with Nurudeenosenat807@gmail.com.

Choose your password privately. Do not send it to ChatGPT.

Then put your Supabase project URL and publishable/anon key in config.js. Never put a service_role/secret key in browser code.

## Publish
Host these static files on a web host. Customer site: /index.html. Admin: /admin.html.
