# Chop Belleful — Food Brand Website

A complete, production-ready multi-page website for the **Chop Belleful** Nigerian food brand. Built with pure HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies, GitHub Pages ready.

## Pages

| File | Page | Purpose |
|------|------|---------|
| `index.html` | Homepage | Hero, marquee, why section, featured dishes, testimonials, CTA |
| `menu.html` | Menu | Full menu with filter by category (soups, rice, swallows, proteins, drinks) |
| `about.html` | About / Story | Brand origin story, stats, values, team |
| `order.html` | Order Now | Full order form + WhatsApp option, delivery info sidebar |
| `reviews.html` | Reviews | Rating summary, review cards, leave-a-review form |
| `contact.html` | Contact | Contact channels, message form, hours, FAQ accordion |

## File Structure

```
chop-belleful/
├── index.html
├── menu.html
├── about.html
├── order.html
├── reviews.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── images/          ← Add your food photos here
```

## How to Customise

### 1. Update your WhatsApp number
Search for `2348000000000` across all HTML files and replace with your actual number.

### 2. Update your email
Search for `hello@chopbelleful.com` and replace with your real email.

### 3. Add real food photos
- Add images to the `/images/` folder
- Replace the `.food-img` divs in each page with `<img src="images/your-photo.jpg" alt="..." />`
- Recommended: 800×600px for dish cards, 1200×900px for hero

### 4. Update prices
All prices are in the menu page (`menu.html`). Update `NGN X,XXX` to your actual prices.

### 5. Update delivery areas
In `order.html`, update the area dropdown options to match where you actually deliver.

### 6. Update phone/social links
In the footer and contact page, update the social media links with your actual handles.

## Deploying to GitHub Pages

1. Create a new GitHub repository (e.g. `chop-belleful`)
2. Upload all files maintaining the folder structure
3. Go to Settings → Pages → Source → Deploy from branch → `main` → `/ (root)`
4. Your site will be live at: `https://yourusername.github.io/chop-belleful/`

## Features

- Mobile-first responsive design
- Sticky floating WhatsApp button on every page
- Scroll reveal animations
- Menu category filters (no external libraries)
- FAQ accordion
- Order form with success state
- Counter animations on stats
- Marquee food name ticker on homepage
- Active nav link highlighting

## Design

- **Fonts**: Playfair Display (headings) + DM Sans (body) — loaded from Google Fonts
- **Colors**: Deep pepper red `#C0392B`, warm cream `#FAF6EE`, rich earth `#5D4037`, warm orange `#E67E22`
- **Aesthetic**: Warm Nigerian street-market energy — bold, generous, unafraid

## Production Notes

- The order form currently shows a success message but does not submit to a backend. To make it live, connect it to a service like [Formspree](https://formspree.io), a Google Sheet via Apps Script, or your own backend.
- Replace all placeholder food image divs with real photographs. Food photography is the single biggest conversion driver for food brands.
- Update the Google Analytics tag once you have one.

---

Built for Chop Belleful · Calabar, Cross River State, Nigeria
