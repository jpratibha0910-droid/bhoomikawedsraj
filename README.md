# Bhoomika & Raj — Wedding Invitation 💍✨

An interactive, responsive digital wedding invitation celebrating **Bhoomika & Raj** (`#Bhoomikaraj`).

📅 **Wedding Date**: 16th December 2026  
📍 **Venue**: Khanvel Resort, Silvassa  

---

## 🌟 Features

* **Wax Seal Envelope Opening**: Realistic envelope with a bespoke **B & R** monogram stamped in gold wax that splits realistically when clicked to reveal the invitation.
* **Ambient Harp & Strings Audio**: Soft Web Audio API harp arpeggios and string pads with toggle control.
* **5 Celebration Video Cards**: Autoplaying, looping portrait videos:
  1. *Rang sari* (Carnival)
  2. *Nachde ne saare* (Sangeet)
  3. *Bhaat ki Reet* (Mayra)
  4. *Lagan la gyi re* (Shaadi)
  5. *Reception*
* **Watercolor Venue & Travel Guide**: Illustrated venue card for Khanvel Resort with direct Google Maps navigation and nearby airport, railway, and driving routes.
* **Interactive RSVP with WhatsApp Integration**:
  - Attend / Decline selection
  - Dynamic guest counter (+ / −)
  - Celebration event checkboxes
  - Interactive quiz ("Who will get emotional first?", "Wedding Mood")
  - Personal note & advice for forever
  - Formatted WhatsApp message ready to send to the family
* **Story Gallery & Drive Upload**: Photo carousel capturing couple memories, plus a direct link to upload guest photos to Google Drive.

---

## 📁 Project Structure

```
├── index.html             # Main website entry point
├── bhoomika.html          # Synchronized template page
├── images/                # Watercolors, floral decorations, photos & B&R monogram
│   ├── floral1.webp
│   ├── floral2.webp
│   ├── floral3.webp
│   ├── hero.webp
│   ├── monogram.png       # B & R gold monogram alpha mask
│   ├── story1-4.jpeg      # Our Story photo gallery
│   ├── venue-art.webp     # Khanvel Resort watercolor illustration
│   ├── venue.jpeg
│   └── wash-*.webp        # Pastel watercolor background washes
├── videos/                # Celebration portrait reels
│   ├── haldi1.mp4
│   ├── sangeet1.mp4
│   ├── mayra1.mp4
│   ├── varmala.mp4
│   └── reception.mp4
├── .gitignore             # Ignored temporary and OS files
└── README.md              # Project documentation
```

---

## 🚀 How to Run Locally

Open `index.html` in any modern web browser, or serve locally:

```bash
# Using Python
python -m http.server 8000

# Using Node / npx
npx serve .
```

Then visit `http://localhost:8000`.

---

## 🌐 Deploy to GitHub Pages

1. Push this repository to GitHub:
   ```bash
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```
2. In your GitHub repository:
   * Go to **Settings** > **Pages**
   * Under **Build and deployment** > **Branch**, select `main` and folder `/ (root)`
   * Click **Save**
3. Your wedding website will be live at `https://<your-username>.github.io/<your-repo-name>/`!
