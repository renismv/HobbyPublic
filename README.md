# Fathayya Star Quest

A kid-friendly, single-page schedule and reward app hosted as a static site via GitHub Pages. It runs fully client-side, stores progress in localStorage, and includes a parent-unlock reward shop plus backup export/import.

## 🌟 Hosted URL

Once GitHub Pages is enabled, open:

```
https://renismv.github.io/HobbyPublic/starquest/
```

## ✅ GitHub Pages setup (Option A: repo root)

1. Go to **Settings → Pages** in this GitHub repo.
2. Under **Build and deployment**, choose:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or your default) and `/ (root)`
3. Click **Save**. GitHub Pages will publish the site.
4. After it builds, the Star Quest app is at:
   `https://renismv.github.io/HobbyPublic/starquest/`

> Option B (if you prefer `/docs`): move the `starquest/` folder into `/docs/starquest/` and select `/docs` as the Pages source. Option A is simpler.

## 📱 Add to iPad Home Screen

1. Open the GitHub Pages URL in **Safari** on the iPad.
2. Tap the **Share** icon.
3. Select **Add to Home Screen**.
4. Name it **Star Quest** and tap **Add**.
5. It will launch like a standalone app.

> Note: localStorage is per device + browser profile. Clearing Safari data resets progress. Use **Backup → Export** to keep a JSON copy and **Import** to restore.

## 💾 Backup & Restore

- **Export Backup** downloads a JSON file of stars, completions, rewards, and parent settings (hash only).
- **Import Backup** restores that JSON on the device.

## 🧠 Data & Parent Mode

- All data is stored locally in the browser (no backend).
- Parent code is stored as a SHA-256 hash.
- Parent unlock lasts 10 minutes.
