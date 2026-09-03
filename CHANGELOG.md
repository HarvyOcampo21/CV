# Changelog

All notable changes to this project are documented here. Format: plain-language, dated entries in reverse-chronological order (newest first). Version numbers follow `MAJOR.MINOR.PATCH`.

## v1.1.0 — Responsive redesign, Aspiring Web Developer branding, working Contact section
The site is now fully responsive with no fixed-pixel layout containers — pages resize cleanly from small phones up through large desktop monitors, including a new tablet-range breakpoint that previously didn't exist. Added subtle CSS-only entrance animations on page load and refined hover states on navigation, buttons, cards, and social icons; all motion is disabled automatically for visitors who have reduced motion enabled in their system settings.

Branding updated from "FRONT-END" to "ASPIRING WEB DEVELOPER" across the navigation and profile card on both pages, and the About Me bio was rewritten to match. Added a working Contact section (reachable from the nav) with tap-to-call and tap-to-email links, and made the existing footer contact info clickable the same way. LinkedIn is now linked to the real profile; Facebook, TikTok, and Instagram are clearly marked as coming soon since no URLs were supplied for those yet — including correcting a pre-existing footer link that pointed a Facebook icon to a YouTube URL. Also fixed a small pre-existing HTML markup error (an unclosed container element on the Resume page) while working in that area of the layout.

No changes were made to the Projects section/page or its navigation link, and no backend or form service was added — the Contact section is links only, matching the static nature of the site.

## v1.0.0 — Baseline
Baseline snapshot of the project as received: existing "About Me" (`index.html`) and "Resume" (`resume.html`) pages, shared `style.css`, and associated icon/image/PDF assets. No functional or visual changes were made in this entry — this version marks the starting point for all future tracked changes.
