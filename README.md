# robertwoodllc.com Site Archive and Rebuild

Private preservation/rebuild repo for Bob Wood's robertwoodllc.com site before the Focused/LeadConnector subscription ends.

## Purpose

Preserve the site design, copy, page structure, screenshots, and downloadable assets so the site can be referenced or rebuilt later without depending on the original hosted platform.

## Structure

- `raw-capture/` - direct capture from the live site and downloaded assets
- `reference/` - screenshots/PDFs for visual reconstruction
- `site/` - first static rebuild seed from captured HTML pages

## Current Status

This is an archival seed. Many dynamic features such as appointment scheduling, registration, login, embedded video behavior, and forms depend on external services and may need replacement if rebuilt for production.

## Recommended Rebuild Path

1. Preserve raw capture exactly.
2. Rebuild the homepage cleanly in `site/index.html` with local CSS/assets.
3. Convert key pages one by one.
4. Replace external forms/booking links only if needed.
5. Publish later only after review.
