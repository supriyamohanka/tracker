# Supriya's 30-Day Job Switch Sprint Tracker

A simple single-page tracker for the next 30 days.

## What this is

- One `index.html` file
- No backend
- No login
- No database
- Saves your progress in your browser using localStorage
- Works on desktop and mobile

## How to deploy on GitHub Pages

### Option 1: New repository

1. Create a new GitHub repository, for example: `30-day-job-switch-tracker`.
2. Upload `index.html` to the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select your main branch and `/root` folder.
6. Save.
7. GitHub will give you a live website link.

### Option 2: Add to your existing website

1. Create a folder in your existing website called `tracker`.
2. Put this `index.html` file inside that folder.
3. Your tracker URL will usually become something like:
   `https://yourdomain.com/tracker/`

## Important note

Progress is saved in the browser you use. If you switch laptop/phone/browser, export a backup from the tracker and import it on the new device.

## Editing the plan

Open `index.html` in VS Code and search for:

```js
const plan = [
```

Edit the day-wise tasks there.
