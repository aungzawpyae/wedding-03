# Wedding Invitation — Hein Wai Oo & Mo Mo Aung Win

Static digital wedding invitation (single `index.html`, no build step).

- Open `index.html` directly or serve the folder with any static host (Nginx, GitHub Pages, Vercel).
- Personalise the cover: `index.html?to=Guest+Name`
- Background music: `music/background-music.mp3` (128 kbps). It starts when the guest taps "ဖိတ်ကြားလွှာ ဖွင့်ရန်"; browsers block sound before the first tap. Replace the file to change the song.
- Event date/time and calendar are set in the `CONFIG` object at the top of the script in `index.html`.
