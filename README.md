# Ritambhara Ma — Luxury Spiritual Portfolio & Sanctuary Website

A luxury, aesthetic, responsive personal portfolio website for **Ritambhara Ma**, Spiritual Counsellor and Meditation Guide.

The website communicates **All-embracing Love**, **Uncaused Happiness**, **Effortless Awareness**, **Fulfilling Peace**, and **Spiritual Awakening**.

---

## 🌟 Visual Identity & Design Direction

- **Atmosphere**: A digital spiritual sanctuary inspired by Himalayan sunrise landscapes, ethereal light, sacred lotus blossoms, and quiet contemplation.
- **Palette**:
  - **Warm Ivory** (`#FAF7F2`) & **Soft Cream** (`#FDFBF7`)
  - **Champagne & Antique Gold** (`#C5A059`, `#E0CFA7`, gradient)
  - **Muted Sage Green** (`#6D7F67`, `#44543F`)
  - **Subtle Blush Pink** (`#E8C8C1`, `#FAF2F0`)
  - **Deep Earth Charcoal Brown** for typography (`#2C2621`, `#5C554E`)
- **Typography**:
  - Headings: `Cormorant Garamond` & `Playfair Display`
  - Body & UI: `Plus Jakarta Sans` / `Inter`
  - Accents: `Pinyon Script`
- **Sacred Symbolism**: Custom geometric lotus emblems, delicate gold ornamental dividers, and aura indicators.

---

## 🏛️ Website Sections & Architecture

1. **Header & Sticky Navigation**:
   - Sacred lotus emblem with wordmark "Ritambhara Ma — Connecting With Love".
   - Links: Home, About, Spiritual Counselling, Meditation, Inspirations, Reflections, Contact.
   - Built-in **Tibetan Singing Bowl Soundscape Toggle** (synthesized in real-time via Web Audio API, 0 external mp3 dependencies).
   - "Talk with Me" gentle quick CTA.
   - Mobile responsive slide-in drawer menu.

2. **Hero Section ("The Digital Sanctuary")**:
   - Ultra-high resolution photograph of the realistic Nepali Himalayas at vivid golden dawn (Machapuchare / Fishtail, Annapurna massif, and deep rolling emerald-green mist-filled foothills).
   - Golden dust motes particle canvas simulating sacred sunlight.
   - **Living Sacred Aura & Brand Crest**: Gentle breathing golden halo, celestial orbital ring, and sacred lotus crown emblem.
   - Headline: *"Ritambhara Ma"* styled with champagne-gold sunrise gradient typography, high-editorial tracking, and a tapered gold star divider.
   - Role badge directly below: *"Spiritual Counsellor & Meditation Guide"*.
   - Tagline: *"Awaken to the Beauty Within."*
   - Supporting text: *"A sacred journey devoted to All-embracing Love, Uncaused Happiness, Effortless Awareness, Fulfilling Peace & Spiritual Awakening."*
   - **"Gentle Loud" Sacred Booking / Talk Invitation**: Luminous frosted glass badge (*"Private Sessions Open · Talk with Me in Stillness →"*) with animated breathing golden halo primary CTA (*"Talk with Me in Stillness"*).
   - CTAs: *"Explore My Journey"* & *"Talk with Me in Stillness"*.
   - **Sanctuary Micro-Pills**: Ethereal frosted glass path indicators (*Inner Stillness · Heart Awakening · Conscious Living*).
   - Animated scroll indicator.

3. **Sacred Aura Bar**:
   - Subtle intention ticker: *All-embracing Love ✦ Uncaused Happiness ✦ Effortless Awareness ✦ Fulfilling Peace ✦ Spiritual Awakening*.

4. **About Me ("A Journey Within")**:
   - Authentic portrait of Ritambhara Ma framed with an editorial arch, gold trim, and floating sanctuary badge.
   - Personal philosophy and exact introductory narrative rooted in All-embracing Love, Uncaused Happiness, Effortless Awareness, Fulfilling Peace & Spiritual Awakening.
   - 5 Guiding Pillars: *All-embracing Love*, *Uncaused Happiness*, *Effortless Awareness*, *Fulfilling Peace*, *Spiritual Awakening*.

5. **Spiritual Counselling ("Guidance for the Soul")**:
   - 5 beautifully designed offering cards:
     1. Inner Truth & Self-Discovery
     2. Emotional Clarity & Inner Peace
     3. Spiritual Awakening
     4. Self-Love & Acceptance
     5. Mindfulness & Conscious Living
   - Interactive modal viewer with core practice pillars and auto-filling inquiry button.
   - Ethical wellness disclaimer (non-medical, spiritual guidance disclosure).

6. **Meditation & Mindfulness ("Return to Stillness")**:
   - **Interactive Guided Breathwork Sphere**: Real-time 4-4-4-4 Box Breathing visualizer (Inhale, Hold, Exhale, Rest) with Tibetan singing bowl chime sound effect.
   - 5 visual practice cards with curated serene photography:
     1. Guided Meditation
     2. Mindfulness Practices
     3. Breath & Inner Truth (Pranayama)
     4. Inner Stillness
     5. Self Love

7. **Philosophy & Inspirations ("Wisdom for the Soul")**:
   - Curated timeless teachings on All-embracing Love, Uncaused Happiness, Effortless Awareness, Fulfilling Peace & Spiritual Awakening.
   - Verified quotations with attributions: Pathik (Patron of Pathik Foundation Nepal), Sri Ramana Maharshi, Jalāl al-Dīn Rūmī, Lao Tzu, Sri Nisargadatta Maharaj, and Ritambhara Ma.
   - Interactive theme filter tabs (All, Love, Peace Within, Truth & Awakening, Sages).

8. **Voices of the Heart ("Seeker Reflections")**:
   - Dedicated praise & testimonial section featuring 6 heartfelt experiences from seekers across Nepal and the world.
   - Elegant avatar badges, star ratings, and thematic pillar tags.

9. **Sacred Reflections Journal**:
   - Weekly contemplation newsletter integrated directly with Ritambhara Ma's Substack publication (`lovethewayhome.substack.com`).

10. **Contact Section ("Let's Connect")**:
    - Contact channels: Email (`ritambharaposts@gmail.com`), Substack (`lovethewayhome.substack.com`), YouTube (`@LoveTheWayHome`), Facebook (`@LoveTheWayHome`), and Google Blogger (`lovethewayhome.blogspot.com`).
    - Functional contact form ("Send a Heartfelt Note") with "Your Name" field, client-side validation, and confirmation view.
    - Path of Interest selector mapped to counselling modalities.

11. **Footer & Floating Sanctuary Controls**:
    - Complete luxury footer with brand statement, navigation anchors, session hours, and copyright.
    - Floating "Talk with Me" sanctuary action pill & back-to-top button.

---

## 💻 Tech Stack & Performance

- **HTML5**: Semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`).
- **CSS3**: Pure custom design system using CSS custom properties (tokens), responsive Flexbox & Grid, frosted glassmorphism (`backdrop-filter`), keyframes, and reduced-motion media query support.
- **Vanilla JavaScript**: Pure zero-dependency script handling active scrollspy, interactive breathwork sphere, Web Audio API soundscape, daily quote rotator, filter tabs, modal dialogs, and form validation.
- **Audio**: Web Audio API pure mathematical synthesis (432 Hz Solfeggio frequency + Tibetan bowl harmonic overtones) — no audio files to buffer or fail to load.
- **SEO & Accessibility**: Complete Open Graph metadata, Twitter card, Schema.org Person JSON-LD, ARIA roles, and high contrast text ratios.

---

## 🚀 How to Run Locally

Open a terminal in this directory and start any local static server:

```bash
# Using Python 3 (built-in on macOS)
python3 -m http.server 8000
```

Then visit:
```
http://localhost:8000/
```

Or simply open `index.html` directly in any web browser!

---

## 📁 Directory Structure

```
rita-rai-website/
├── index.html                  # Master sanctuary HTML document
├── README.md                   # Documentation & setup guide
├── assets/
│   ├── css/
│   │   └── styles.css          # Master luxury stylesheet & tokens
│   ├── js/
│   │   └── main.js             # Interactive engine & soundscape
│   └── images/                 # Optimized photographic & portrait assets
│       ├── rita-portrait-main.jpg
│       ├── rita-portrait-serene.png
│       ├── rita-portrait-seated.png
│       ├── hero-sunrise.jpg
│       ├── meditation-lake.jpg
│       ├── forest-sunbeams.jpg
│       ├── still-water.jpg
│       ├── zen-stones.jpg
│       └── candle-peace.jpg
```

---

*“Awaken to the Beauty Within.”* — Ritambhara Ma
