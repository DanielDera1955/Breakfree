# Deploy

1. Edit the CONFIG block near the bottom of index.html (search "var CONFIG"). Replace every REPLACE item. Yellow dashed boxes on the page are copy you must replace.
2. Images: put testimonial screenshots in /testimonials and list them in CONFIG.results. Put payment proof in /proof and list in CONFIG.proof. Trainer photo: img/trainer.jpg. Video poster: img/poster.jpg. Link preview image: og.jpg (1200x630) in the root.
3. Only use images that belong to the client's own business.
4. Paste the client's NGN and USD checkout links into CONFIG.
5. Push to GitHub, import in Vercel, deploy. No build settings needed.
6. Test a small live payment from a phone and check the WhatsApp link preview.
