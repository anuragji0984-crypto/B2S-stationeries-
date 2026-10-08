B2S LIVE VERSION
=================
Supabase Project URL:
https://poajvfviifkcbfrnwdlw.supabase.co

This package uses the publishable key in the browser. Never put a secret/service-role key in these files.

ONE-TIME SETUP:
1. Open Supabase -> SQL Editor.
2. Paste the entire `supabase_setup.sql`.
3. Run it.
4. Go to Authentication -> Users and create the admin user (email + password).
5. Open admin.html and login with that admin email/password.
6. Upload the website files to your hosting.

CUSTOMER:
- Sends name, phone, list, delivery/pickup and optional photos.
- Order is stored online in Supabase.
- Photos upload to the private `order-photos` bucket.
- Pickup shows UPI: 9421573354@fam.
- Delivery is pay-on-delivery.

ADMIN:
- Authenticated Supabase login.
- Reads online orders.
- Changes status.
- Deletes orders.

NOTE:
The admin page in this live version intentionally does NOT use the old hard-coded `admin / B2S@2026` login because that would not be secure for a real public website.
