# GitHub Pages Deployment Guide

A quick path to host the deck on GitHub Pages so the URL is shareable.

---

## When to use GitHub Pages vs local file

| Hosting | Pro | Con |
|---|---|---|
| **GitHub Pages** | Single shareable URL, easy to update, works from any device | Some Filtrona corporate / plant networks block github.io domains |
| **Local file (`index.html`)** | Works offline, no network dependency, no external block | URL-sharing harder; each viewer needs the folder |

**Recommendation for the 19 May session:** prepare **both**. GitHub Pages is the primary; the local copy is your Plan B.

---

## Step 1 — Create the repository

1. Go to `github.com/new`
2. Name it: `filtrona-ai-lunch` (or whichever name works for you)
3. Visibility: choose **Private** if the deck contains internal references; **Public** is fine if everything is generic
4. **Do not** initialise with a README (you already have one)
5. Click *Create repository*

## Step 2 — Upload the folder

From the new repo's page, click **Add file → Upload files**, then drag the entire `filtrona-ai-lunch-v2/` folder contents in:

```
index.html
assets/
  filtrona-logo-placeholder.svg
docs/
  speaker_script.md
  audience_handout.md
  mentimeter_setup.md
  use_case_form_questions.md
  ai_resources_page.md
  presenter_checklist.md
  github_deployment_guide.md
README.md
```

Commit the upload.

## Step 3 — Enable Pages

1. In the repo, go to **Settings → Pages**
2. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: `main` · folder: `/ (root)`
3. Save
4. Wait ~1 minute for the first build
5. GitHub shows your URL at the top of the Pages settings, like `https://yourusername.github.io/filtrona-ai-lunch/`

## Step 4 — Configure the deck

Open `index.html` and find the `CONFIG` block at the bottom of the `<script>`. Update each placeholder:

```js
const CONFIG = {
  mentimeterJoinUrl: "https://www.menti.com/YOUR-CODE",          // From Mentimeter
  feedbackFormUrl:   "https://forms.office.com/r/...",           // Post-session feedback
  useCaseFormUrl:    "https://forms.office.com/r/...",           // The new use-case form
  intranetUrl:       "https://filtrona.sharepoint.com/sites/AIFiltrona",
  teamsCommunityUrl: "https://teams.microsoft.com/l/channel/...",
  logoUrl:           "assets/filtrona-logo-placeholder.svg",     // Replace with official logo
  sessionMinutes:    40
};
```

Commit. GitHub Pages rebuilds automatically (~30 seconds).

## Step 5 — Test from a phone

Open the Pages URL on your phone using **mobile data, not the corporate Wi-Fi**. This is how attendees will see it. Confirm:

- All slides render
- Fonts load (Fraunces + DM Sans)
- Mentimeter URL displays
- The keyboard hint at the top-right is visible

## Step 6 — Plan B (local file)

Download the repo as a ZIP (**Code → Download ZIP**) and keep an unzipped copy on a USB stick and on your laptop. To run:

```
Open index.html in any modern browser.
```

Local file mode has **no network dependency** (other than Google Fonts, which fall back to system sans-serif if blocked). Keyboard nav, timer, music, and notes all work locally.

---

## Updating the deck post-deployment

For small changes: edit `index.html` in the GitHub web UI, commit. Pages rebuilds in ~30 seconds.

For larger changes: clone, edit locally, push.

---

## Custom domain (optional)

If you'd rather not use the `github.io` subdomain:

1. Buy or use an existing domain
2. In repo **Settings → Pages → Custom domain**, enter it
3. Update your DNS provider with the GitHub Pages CNAME or A records
4. Wait for HTTPS to provision

Not required for the 19 May session.

---

## Troubleshooting

| Symptom | Likely cause | Fix |
|---|---|---|
| Pages URL returns 404 after publishing | Build still in progress | Wait 1–2 minutes; refresh |
| Fonts look generic | Google Fonts blocked by network | This is expected on some plant networks — design degrades gracefully |
| Mentimeter URL shows the placeholder | `CONFIG.mentimeterJoinUrl` not updated | Edit `index.html`, commit |
| Timer doesn't start | Pressed `T` while focus was inside a text field | Click anywhere on the deck first |
| Music feedback on Teams call | `M` toggled music on during screen share | Press `M` again to mute |
