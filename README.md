# Acton Avenue room listing

Private listing page for a room to sublet in Acton, near Acton Town station.

The page is a single HTML file with a password gate. Unlock it to see the room, house, photos, location, and WhatsApp contact.

## Preview locally

Open `room-listing.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000/room-listing.html](http://localhost:8000/room-listing.html).

## Files

```
.
├── room-listing.html   # Listing page, styles, and password gate
├── images/             # Photos used on the page
└── README.md
```

Photos live in `images/` and are referenced from `room-listing.html`. The hero uses `images/avenue_living1.jpeg`.

## Notes

- The listing password is set in the script at the bottom of `room-listing.html`.
- If you publish this repo, anyone who can see the source can also see that password.
