# Lucky Portal (GitHub Pages demo)

This repository is configured for GitHub Pages using the `/docs` folder.

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Extract this ZIP file on your computer.
3. Upload the extracted files and folders to the repository's **root** (the `docs` folder must remain at the root).
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch `main` and folder `/docs`, then click **Save**.
7. Wait for GitHub Pages to finish publishing. The URL will be shown in Settings → Pages.

## Demo login
- Customer reference code: `LUCKY2026`
- Admin username: `portaladmin`
- Admin password: `Lucky@2026`

Open the three-dot menu to access the admin panel.

## Important limitations
This is a **static frontend demo**, not a secure production lottery or prize service:
- The admin credentials and reference-code check are implemented in browser JavaScript and can be inspected or bypassed.
- Settings and uploaded images are not stored in a server/database and will not sync between visitors or devices.
- Do not collect sensitive personal information or payment details.
- Do not represent this as an official lottery or a verified prize system.

GitHub Pages hosts static files only. For secure admin login, shared settings, and persistent image uploads, add a backend/API, database, server-side authentication, password hashing, and upload validation.
