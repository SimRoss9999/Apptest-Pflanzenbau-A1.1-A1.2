# Running on Replit

This is a static web app with no build step, backend, dependencies, or required secrets.

- Start command: `python3 -m http.server 5000 --bind 0.0.0.0`
- The Replit workflow **Start application** runs that command and serves the project root.
- Open the Replit Preview to use the app.

Keep the existing static structure. The application is implemented in `index.html`, with quiz content in `questions.js`.