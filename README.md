# Pilot Daily Log — independent static PWA

This is a **standalone recreation**, not a byte-for-byte export of the original Lovable/TanStack application. It implements flight entry, REV/MX times, history, deletion, totals, aircraft management, fast decimal, light/dark mode, local device storage, and offline PWA caching. The iPhone dictation normalization is a best-effort workaround and must be tested on a real iPhone.

## Publish to GitHub Pages for free

1. Open https://github.com/Rockyf07/pilot-daily-log and choose **Add file > Upload files**.
2. **Unzip this archive first**, then upload the files inside the `pilot-daily-log` folder into the **repository root**. Ensure `index.html` is at the top level (not in a subfolder).
3. Commit the files.
4. Open repository **Settings > Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Once deployment finishes, open https://rockyf07.github.io/pilot-daily-log/ in Safari. Share that URL with friends. Safari Share > Add to Home Screen installs the PWA.

## Important

- Existing history in the old Lovable URL **does not automatically transfer**. This standalone app stores its own history locally under a different storage key. Its Settings menu supports backup/export and import for *this version only*.
- Data on one person's phone is not synced with friends' devices.
- Don't delete the old Home Screen app or clear Safari website data until you're sure you've retained any history you need.
- Static GitHub Pages hosting needs no Lovable credits.
