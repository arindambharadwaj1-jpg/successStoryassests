# successStoryassests

Image assets for the academy site / Success Stories app.

## Layout

```
assets/
  brand/     logo and app icon
  covers/    portal and mobile cover images
  gallery/   general gallery / event photos
  heroes/    page and section hero images (incl. the mh* variants)
  people/    individual student & staff portraits
```

## Notes

- Files were moved out of the repo root into `assets/` so application code can
  live alongside them without clutter. History is preserved (`git log --follow`).
- A few filenames containing spaces or parentheses were slugified so they are
  safe to use directly in URLs:
  - `ChatGPT Image Sep 5, 2026, 01_08_30 PM (1).png` -> `assets/covers/portalcover-alt.png`
  - `WhatsApp Image 2026-09-04 at 4.47.55 PM.jpeg` -> `assets/gallery/whatsapp-2026-09-04-1.jpeg`
  - `WhatsApp Image 2026-09-04 at 4.47.56 PM.jpeg` -> `assets/gallery/whatsapp-2026-09-04-2.jpeg`
  - `WhatsApp Image 2026-09-05 at 10.38.20 AM.jpeg` -> `assets/gallery/whatsapp-2026-09-05-1.jpeg`
  - `IMG-20260819-WA0028.jpg` -> `assets/gallery/img-20260819-wa0028.jpg`
  - `SuccessStories_Hero_Space.png` -> `assets/heroes/successstories-hero-space.png`
