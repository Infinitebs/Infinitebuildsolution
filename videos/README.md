# Videos Folder

Place site walkthroughs, project reels, and engineering vlog video files (`.mp4` or `.webm`) in this directory (`videos/`).

## How to publish a vlog on the Blogs & Vlogs page

1. Save your video file in `videos/`, for example `videos/villa-tour.mp4` (and optionally a thumbnail image in `images/`).
2. Add an entry to the `VLOGS` array in `js/script.js`:

```js
var VLOGS = [
  {
    t: 'Turnkey Villa Site Walkthrough — Mysuru',
    c: 'RESIDENTIAL CIVIL',
    d: 'A guided tour covering RCC framing, waterproofing, and custom interior finishes.',
    src: 'videos/villa-tour.mp4',
    poster: 'images/villa-mandya.jpg',
    duration: '3 min watch',
    date: 'November 2026'
  }
];
```

Once at least one item is in `VLOGS`, the Vlogs tab on `blogs.html` automatically displays the video cards instead of the "Coming Soon" message.
