# Custom Auth ![status](https://img.shields.io/badge/status-deprecated-yellow)

OAuth2-style authentication system for Firebase Spark plan.

## How to Create My Own Custom Auth

To create your Custom Auth, follow these steps:

1. Create the following files:
   - `auth.html`
   - `apps.html`
   - `login.html`
   - `register.html`
   - `firebase-config.js`

2. Add your Firebase Web App configuration.
3. Ensure Firebase Auth is properly enabled in your project.
4. Place your Firebase client config inside `firebase-config.js`.
   (Do NOT use Admin SDK credentials in frontend code.)
5. Import and connect all modules correctly.
6. Enjoy your project!

## Important

- This system is deprecated and no longer maintained.
- SkunkPlatform is no longer maintaining Custom-Auth.
- SkunkPlatform uses SPA (Modern SkunkPlatform Account) for SP2026.
- SkunkPlatform Developers are integrated into SP2026.

⚠️ Warning:
Storing passwords manually in a custom auth system is insecure. Always prefer Firebase Authentication.
