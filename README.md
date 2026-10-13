# cherry-cola — Our Forever Messenger ♡

A cozy, private messenger just for two. Real-time, forever saved in the cloud, never deletes when you close the link.

**Live code:** `cherry-cola`

### Features
- Forever cloud storage via Pantry (GET/POST) — messages stay even after closing
- Works across two different phones with same couple code
- Cozy design: blush pink bubbles, handwritten notes, polaroid photos
- Quick buttons: Hug 🤗 Kiss 💋 Coffee ☕ Miss you 💌 Goodnight 🌙
- Photo sharing as polaroids
- Polling every 3s for live sync, offline backup to localStorage

### How to deploy (2 mins)
1. Create a new GitHub repo named `cherry-cola` (Public)
2. Upload `index.html` to the repo root
3. Also upload empty file `.nojekyll` (tells GitHub not to break it)
4. Go to Settings > Pages > Source: Deploy from branch, Branch: main / root > Save
5. Wait 1-2 mins, your site will be live at `https://YOUR_USERNAME.github.io/cherry-cola/`

Share that link + code `cherry-cola` with him.

### Make it fully private (optional)
The file uses a shared demo Pantry ID `3fce793c-17b9-4691-9376-3e334aefeae4`. 
For your own private database:
1. Go to https://getpantry.cloud/ -> enter email -> copy your Pantry ID
2. In `index.html`, replace `const PANTRY_ID = "..."` with yours
3. Re-upload

Now only you two can access that Pantry.

Made with ♡ for Cheryyy
