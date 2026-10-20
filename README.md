# Englify info — Netlify site (englifyinfo.netlify.app)

| Page | Link to send |
|---|---|
| Englify info | https://englifyinfo.netlify.app/ |
| Jo‘shqin | https://englifyinfo.netlify.app/joshqin  (short: /j) |
| Bo‘talog‘im | https://englifyinfo.netlify.app/botalogim  (short: /b) |
| Speaking | https://englifyinfo.netlify.app/speaking  (short: /s) |
| Individual 1:1 | https://englifyinfo.netlify.app/individual  (short: /i) |
| IELTS | https://englifyinfo.netlify.app/ielts  (short: /ie) |

## Manager's Telegram in the link (new)
Add `?m=` + the manager's Telegram username or phone to any link:
- https://englifyinfo.netlify.app/?m=aziza_englify
- https://englifyinfo.netlify.app/joshqin/?m=+998901234567

With `?m=`, the student's «Telegram orqali yuborish» button opens a chat with that manager, with the question already typed.
Without it, Telegram's share screen opens and the student picks the manager's chat.
The page remembers the manager on that phone, so links opened later without `?m=` still go to the same manager.

**Link builder for managers:** https://englifyinfo.netlify.app/havola/ (short: /h) — type your Telegram, pick a page, copy or send the link.

## Deploy
- **GitHub (Englifyinfo repo):** copy everything in this folder to the repo root, commit, push. Netlify redeploys automatically.
- **Drag & drop:** Netlify → englifyinfo → Deploys → drag this WHOLE folder (not single files).

## Link previews (Telegram)
Each page has Open Graph tags pointing to `/og/*.jpg`. Image URLs use https://englifyinfo.netlify.app —
if the site name or domain changes, update the URLs (search for `englifyinfo.netlify.app`).
Telegram caches previews: after changing a preview, send the link to @WebpageBot to refresh it.
