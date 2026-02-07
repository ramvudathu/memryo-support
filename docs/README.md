# Memryo website (GitHub Pages)

This folder contains the full Memryo marketing website. It is designed to be published with **GitHub Pages**.

## Enable GitHub Pages

1. Open your Memryo repo on GitHub.
2. Go to **Settings** → **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **main** (or **master**) and folder **/docs**.
5. Click **Save**. The site will be available at:
   - **https://\<your-username\>.github.io/Memryo/**

(Replace `Memryo` with your repo name if different.)

## Add screenshots

To show app screenshots on the site, add these files under `docs/images/`:

| File | Description |
|------|-------------|
| `home.png` | Home screen / categories and activities |
| `remember-it.png` | Screen with the “Remember it” button |
| `timeline.png` | Timeline / event history view |
| `notes.png` | Event notes or edit screen |

Use PNG or JPEG. Phone aspect ratio (e.g. 1080×1920 or 9∶19) works best. Capture from the Android or iOS app or simulator.

## Contents

- **index.html** – Main landing page (features, screenshots, usability, description, download links).
- **privacy.html** – Privacy policy (use this URL for Play Store and App Store).
- **support.html** – Support and FAQ.
- **css/style.css** – Styles.
- **images/** – App icon and optional screenshots.

## Update store links

In `index.html`, update the download buttons with your real store URLs:

- **App Store:** replace `https://apps.apple.com/app/memryo/idXXXXXXXXX` with your app’s URL.
- **Google Play:** `https://play.google.com/store/apps/details?id=com.memryo.app` is already correct; update if your package ID is different.

## Privacy policy URL for stores

After enabling Pages, your privacy policy URL is:

**https://\<your-username\>.github.io/Memryo/privacy.html**

Use this in Google Play Console and App Store Connect.
