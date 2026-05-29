# Expo Registration System

A lightweight, client-side registration and attendee management web app for events and expos. Built with plain HTML, CSS, and JavaScript and designed to run from a static web server (uses LocalStorage for persistence).

## Features

- Attendee registration form
- Admin dashboard and registration desk views
- Attendee directory and search
- LocalStorage-based storage with simple sync utilities

## Quick Start

Prerequisites: [Node.js](https://nodejs.org/) and `npm` (optional, for the included dev server).

1. Install dependencies (optional):

```bash
npm install
```

2. Run the local static server:

```bash
npm run dev
```

3. Open the app in your browser at:

```
http://localhost:8000/register.html
```

## Project Structure

- `register.html` — attendee registration page
- `register.js` — registration form logic
- `registration-desk.js` — registration desk UI
- `admin.js` — admin dashboard logic
- `directory.js` — attendee directory view
- `display.js`, `search.js` — listing and search helpers
- `storage.js` — LocalStorage helpers
- `css/style.css` — site styles
- `package.json` — project metadata and `npm run dev` script

## Usage

- Use `register.html` for attendees to sign up.
- Use the admin and desk pages for staff to view, check in, and manage attendees.
- Data is stored in the browser's LocalStorage; export/import tools may be available in the UI.

## Contributing

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes and push: `git push origin feature/your-feature`
4. Open a pull request.

## Publishing to GitHub

If you haven't already, create a repository on GitHub and then run:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<blake332>/<Registeration-Linyi>.git
git push -u origin main
```

Replace `<blake332>/<Registeration-Linyi>` with your GitHub details.

## License

MIT

## Author

Antigravity
