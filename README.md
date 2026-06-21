# St. Catherine FC Website

Official website for St. Catherine Football Club, Eraviputhenthurai - a historic football club established in 1953.

## Live Site

**URL:** https://jose-antony-02.github.io/st-catherine-fc-website/

## About

St. Catherine Football Club has been the heartbeat of football in the coastal village of Eraviputhenthurai for over 70 years. The club organizes the prestigious All India 5-a-side One Day Football Tournament annually.

## Website Features

### Pages
- **Home** - Hero section with countdown timer to the 39th Tournament (June 27, 2026)
- **About** - Club history, timeline, and values
- **Tournament Hub** - Tournament bracket, fixtures, results, and team information
- **Gallery** - Photo gallery (coming soon after June 27, 2026)
- **Contact** - Contact form and location map

### Key Features
- Responsive design using Tailwind CSS
- Live countdown timer to tournament day
- Interactive tournament bracket with real-time results, shared live across every visitor (not just the admin's own browser)
- Google Maps integration
- Mobile-friendly navigation

## Technology Stack

- HTML5
- Tailwind CSS (via CDN)
- Font Awesome Icons
- Vanilla JavaScript
- [Supabase](https://supabase.com) (Postgres + Realtime) — shared backend for tournament data (teams, bracket, results, gallery), so the admin's updates appear live on every visitor's screen
- ImgBB — image hosting for gallery/team logo uploads
- GitHub Pages for hosting

**Admin access**: gear icon in the footer of any page, password-gated (see `tournament.html`). Writes to Supabase are currently open (not auth-gated) — anyone with the page source could write directly via the API, which is an accepted trade-off for this site's scale rather than a real security boundary.

## Local Development

To run this website locally:

```bash
# Clone the repository
git clone https://github.com/jose-antony-02/st-catherine-fc-website.git

# Navigate to the folder
cd st-catherine-fc-website

# Open index.html in your browser
```

Or simply open the `index.html` file in any web browser.

## Tournament Information

**39th All India Tournament**
- Date: June 27, 2026
- Format: 5-a-side One Day Football Tournament
- Teams: 16 teams, single-elimination knockout (Knockout Stage → Quarterfinals → Semifinals → Final)
- Location: Eraviputhenthurai, Tamil Nadu, India

## Social Media

- **Instagram:** [@st.catherine.official](https://www.instagram.com/st.catherine.official)

## Credits

- Club: St. Catherine Football Club, Eraviputhenthurai
- Established: 1953
- Tagline: "One Team. One Dream." ⚽❤️

---

© 2026 St. Catherine FC. All rights reserved.
