META RECOVERIST — LOCAL LOGIN SETUP

1. Install Node.js 18+.
2. In this folder, set the environment variables:
   ADMIN_EMAIL=your login email
   ADMIN_PASSWORD=your login password
   PORT=3000
3. Start:
   node server.js
4. Open:
   http://localhost:3000

Security note: do NOT put a real password in index.html/login.html or publish .env in a public repository. The login is server-side and uses an HttpOnly session cookie.
