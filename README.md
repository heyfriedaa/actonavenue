# Acton Avenue room listing

Private listing page for a room to sublet in Acton, near Acton Town station.

The page is a single HTML file with a password gate. Unlock it to see the room, house, photos, location, and WhatsApp contact.

Live site: [https://heyfriedaa.github.io/actonavenue/](https://heyfriedaa.github.io/actonavenue/)

## Preview locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000/](http://localhost:8000/).

## Files

```
.
├── index.html          # Listing page (required for GitHub Pages)
├── room-listing.html   # Same page, kept for the old URL
├── images/             # Photos used on the page
└── README.md
```

Photos live in `images/` and are referenced from the HTML. The hero uses `images/avenue_living1.jpeg`. GitHub Pages needs `index.html` at the site root; `room-listing.html` alone made `https://heyfriedaa.github.io/actonavenue/` return 404.

## Notes

- The listing password is set in the script at the bottom of `room-listing.html`.
- If you publish this repo, anyone who can see the source can also see that password.
