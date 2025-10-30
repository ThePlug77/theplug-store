
Simple static shop (HTML/CSS/JS) with PayPal + Stripe buttons

What you have:
- index.html : main page with PayPal + Stripe buttons
- styles.css : styles including minimalist black/white buttons
- products.json : product data (add your PayPal/Stripe links here)
- images/     : placeholder product images
- README.txt : instructions

Quick edits:
- Replace `paypal_link` and `stripe_link` in products.json with your real checkout URLs.
- Replace placeholder images in images/ with your product photos.
- Edit brand name, colors, and text in index.html and styles.css as needed.

Hosting:
- Free: GitHub Pages or Netlify. Upload the folder and publish.
- Your site URL can then be pasted in your Depop bio.

Example product in products.json:
{
  "title": "White Leather Trainers",
  "price": "60.00",
  "sizes": ["6","7","8","9"],
  "desc": "Clean white trainers, lightly used.",
  "image": "images/trainers.jpg",
  "paypal_link": "https://www.paypal.com/yourlink",
  "stripe_link": "https://buy.stripe.com/yourlink"
}
