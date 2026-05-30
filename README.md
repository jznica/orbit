<div align="center">

# ✦ Orbit

### *Where minds find each other.*

A cross-college collaboration platform for students who build.
Find teammates for hackathons, research, and side projects — across campuses, fields, and borders.

<br/>

`Vanilla JS` · `CSS` · `Supabase` · `Claude API` · `PWA`

<br/>

**[ Live Demo ](#)** · **[ Features ](#-features)** · **[ Run Locally ](#-run-it-locally)**

</div>

---

## ✦ The Problem

The best collaborators are rarely on your own campus. A brilliant ML engineer at IIT Madras, a designer at NID, a backend wizard at BITS — they're all building in parallel, never meeting. Students stay stuck inside their own college walls, forming teams from whoever happens to sit nearby.

**Orbit dissolves the walls.** It's an archive of student ambition where you discover people by what they're building, not where they study.

---

## ✦ Features

| | |
|---|---|
| **The Feed** | Post a listing when you need teammates. Browse what others are building across the country. Two streams — Listings and Events. |
| **The Map** | Discover students matched to your interests, skills, and the hackathons you're chasing. Sorted by fit. |
| **Letters** | A quieter way to reach out. No cold DMs — just letters between people who want to build together. |
| **Sage** | An AI companion that suggests collaborators, drafts your listings, refines your bio, and brainstorms project directions. |
| **Sigils** | Earn marks as you build, share, and connect. A profile that grows with you. |
| **Admin Panel** | Founder-grade moderation — reports, user management, content review, and live activity logs. |

---

## ✦ Design

Orbit wears an aesthetic called **Midnight Scholastic** — dark academia meets modern magic. Candlelit navy, antique gold, parchment cream. A floating constellation, drifting gold dust, an orbiting brand mark.

```
Navy     #0F1424      Gold        #C9A961
Burgundy #6B1F2A      Gold Bright #E8B547
Cream    #F4E8D0      Moonlight   #F8F4EC
```

*Typefaces — Cormorant Garamond, Crimson Pro, Manrope.*

> Try typing `lumos` anywhere in the app. ✦

---

## ✦ Built With

- **Vanilla JavaScript** — no framework, a hand-rolled component + state-render system
- **CSS** — custom design system, flexbox app-shell, hand-animated SVG (including a satellite that orbits the logo)
- **Supabase** — authentication (Google / Apple OAuth), with room to grow into real-time data
- **Anthropic Claude API** — powers Sage, the in-app assistant
- **PWA-ready** — installable to the home screen, custom favicon and app icon

Everything ships as a **single `index.html`** — no build step, no dependencies to install.

---

## ✦ Run It Locally

```bash
# clone the repo
git clone https://github.com/YOUR_USERNAME/orbit.git
cd orbit

# open it — that's the whole setup
open index.html        # macOS
# or just double-click index.html
```

To enable real Google sign-in, add your Supabase keys near the top of `index.html`:

```js
const SUPABASE_URL = "your-project-url";
const SUPABASE_KEY = "your-anon-public-key";
```

Without keys, Orbit runs in **demo mode** with seeded data — fully explorable.

---

## ✦ Roadmap

- [x] Full frontend — feed, map, letters, profiles, admin
- [x] Auth flow with Google / Apple / email OTP
- [x] AI assistant (Sage)
- [x] Profile photo upload with canvas cropping
- [x] Real OAuth via Supabase
- [ ] Shared database — posts and letters across all users
- [ ] Real-time messaging
- [ ] Custom domain + App Store / Play Store builds

---

## ✦ About

Built solo by **Jenica A** — B.Tech AI/ML student, Saveetha School of Engineering.
Designed, coded, and shipped as a study in what one student can build alone.

<div align="center">

<br/>

*✦ An archive for the curious. ✦*

</div>
