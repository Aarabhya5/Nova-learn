NOVA Functional MVP v5 — Midnight Navy Edition

SETUP
1. Extract the ZIP.
2. Open NOVA.html in a current Chrome or Edge browser.
3. Select Create account for a new local demo account, or Sign in for an existing one.
4. Open Settings from the sidebar to edit profile, theme, preferences, sign out or reset account data.

AUTHENTICATION NOTES
- This is a browser-only prototype. Accounts are saved in localStorage on this device.
- Passwords are SHA-256 hashed before being saved, but SHA-256 alone is not a production password-storage scheme.
- Do not use a real, reused, school, email or personal password.
- There is no server, secure session, email verification, password reset or cross-device account sync.
- For real public users, implement a backend authentication provider, salted password hashing (Argon2id/bcrypt), HTTPS, rate limiting, email verification and server-side authorization.

SETTINGS
- Profile name
- Light / dark theme
- In-app reminder preference
- Default study subject
- Sign out
- Reset this account's local demo data

OTHER FEATURES
- Learn subject-wise notes, assignments with urgent red deadlines, schedule, classroom notes/notices, library previews, practice quizzes, tests, exam planner, analytics and conditional achievements.
- Live Classes remains removed.
- Analytics use activity recorded in the current local account; no fabricated live data.


VISUAL UPDATE v5
- Premium Midnight Navy abstract gradient background
- Electric-blue and cyan ambient glow
- Subtle technical grid texture
- Dark glass-style cards and navigation
- Updated buttons, inputs and sign-in panel to match the theme
- Existing functionality and local demo account behaviour retained
