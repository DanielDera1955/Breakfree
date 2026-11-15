# Deploy in about 10 minutes

1. Open index.html and edit the CONFIG block (search "const CONFIG"). Replace every "REPLACE" item.
2. Put testimonial images in /testimonials (t1.jpg ... t6.jpg) or change the filenames in CONFIG.
3. Add og.jpg (1200x630) in the root for WhatsApp/Facebook link previews.
4. Edit the REPLACE lines in privacy.html and terms.html.
5. Create the client's checkout links (Selar or Paystack payment page) in NGN and USD and paste them into CONFIG.
6. Push the folder to a new GitHub repo, then on vercel.com choose Add New > Project > Import the repo > Deploy. No build settings needed.
7. Add the client's domain in Vercel > Settings > Domains.
8. Test: pay a small amount on the live link, open on a phone, and check the WhatsApp preview.

Seat counter: change seatsTaken in CONFIG after each confirmed sale, then redeploy.
