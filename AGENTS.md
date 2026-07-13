## Frontend QA Rules

- Before reporting a website/page fix as done, test the actual rendered page in a browser.
- For GitHub Pages work, test the canonical URL without cache-bust query parameters.
- Test both desktop and mobile viewport behavior when the change affects layout, navigation, tabs, headers, or responsive UI.
- Do not rely only on local HTML inspection or source-code checks; verify visible UI state, console health, and at least one interaction.
- If a password-protected page cannot be fully tested because the password is unavailable, say that explicitly before final delivery.
