# Project demo videos

Drop your screen-recording clips in **this folder** using these exact names.
A "▶ Watch demo" button automatically appears on a project card as soon as its
file exists here (and disappears if the file is missing) — so you can add them
one at a time.

| Project on the site        | File to add here (exact name) |
|----------------------------|-------------------------------|
| KimieBundle Ez-Shop System | `kimiebundle.mp4`             |
| ReSole — AI Bundle OS       | `resole.mp4`                  |
| RegisterUp                  | `registerup.mp4`              |

## Recommended specs (keep the site fast + within GitHub Pages limits)

- **Format:** MP4 (H.264 video + AAC audio) — best browser support
- **Length:** ~15–45 seconds (a tight highlight reel beats a long walkthrough)
- **Resolution:** 1080p or 720p
- **File size:** aim for **under ~15 MB** each (hard limit is 100 MB/file on
  GitHub Pages; smaller = faster load for visitors)
- **Filename:** all lowercase, no spaces (already handled by the names above)

Tip: if a raw recording is too big, compress it with HandBrake (free) using the
"Fast 1080p30" preset, or shorten/trim it first.

## After adding a video

Tell me and I'll commit + push it live, or run yourself from the
`Website Resume` folder:

```
git add videos/
git commit -m "Add <project> demo video"
git push
```

The button goes live ~1 minute later.
