# Toyota Sequoia Pumpkin Packing Challenge 🎃🚗

A responsive 3D web game and email marketing campaign built for website embedding and CRM email newsletters.

![Sequoia Pumpkin Challenge](https://pinheij.github.io/pumpkin-game/preview.png)

## 🎮 Game Rules & Features

- **Sequoia Cargo Trunk**: Pack a pile of unique pumpkins (various shapes, sizes, colors, and point values) into the rear cargo area of a Toyota Sequoia.
- **3D Axis Rotation**: Rotate chosen pumpkins along the X, Y, or Z axis before placing them into the trunk.
- **Locked Placement**: Once placed, pumpkins lock in position and score points based on size and shape.
- **3 Retries**: Player receives 3 retries per round. Using a retry empties the trunk and rebuilds the pile.
- **Close Hatch Test**: To clear a level, the rear hatch on the Toyota Sequoia must close without colliding with any placed pumpkins.
- **Increasing Difficulty**: Clearing a round advances to higher levels with larger, odd-shaped, and more challenging pumpkin piles!

---

## 🌐 Live Demo & GitHub Pages URL
Access the live web game at:
👉 **[https://pinheij.github.io/pumpkin-game/](https://pinheij.github.io/pumpkin-game/)**

---

## 💻 Embedding on Your Website

### Option A: Clean Responsive iFrame Embed
Paste this HTML snippet directly onto your web page, landing page, or CMS:

```html
<div style="position: relative; width: 100%; max-width: 1000px; height: 650px; margin: 0 auto; border-radius: 16px; overflow: hidden; box-shadow: 0 12px 40px rgba(0,0,0,0.5);">
  <iframe 
    src="https://pinheij.github.io/pumpkin-game/" 
    style="width: 100%; height: 100%; border: none;" 
    allow="autoplay"
    title="Toyota Sequoia Pumpkin Packing Challenge">
  </iframe>
</div>
```

---

## ✉️ Using in Email Campaigns

Email clients (Gmail, Outlook, Apple Mail) do not allow inline JavaScript or 3D canvas rendering. To run this in email:

1. **Use `email.html`**: Open the included `email.html` file in this repository and copy the source HTML into your email marketing platform (Mailchimp, CRM, ActiveCampaign, DealerInspire, VinSolutions, etc.).
2. **Direct CTA Button**: The email template includes a CTA button pointing to your hosted game at `https://pinheij.github.io/pumpkin-game/`.

---

## 📁 Repository Structure

- `index.html` — Full 3D Interactive Web Game (Three.js WebGL + Web Audio API).
- `email.html` — Email-safe HTML newsletter template with teaser card and CTA.
- `README.md` — Integration & deployment guidelines.
