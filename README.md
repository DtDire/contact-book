# 📒 Contact Book App

A browser-based contact management app that connects to a live REST API. Built to demonstrate real-world API integration, CRUD operations and client-side state management.

## Features

- **View contacts** — fetches and displays all contacts from a live API on load
- **Add contact** — form to create new contact entries with avatar support
- **Edit contact** — update existing contact details
- **API key authentication** — prompts for an API key on first visit, stores securely in localStorage
- **Auto-redirect** — unauthenticated users are redirected to the API key entry page

## How It Works

The app uses the **ITVarsity Contact Book API** as its backend. On first load, it checks for a stored API key. If none is found, the user is redirected to enter one. Once authenticated, all contacts are fetched and rendered dynamically.

## Tech Stack

- HTML5 · CSS3 · Vanilla JavaScript
- REST API (fetch)
- localStorage for session management

## Pages

| File | Purpose |
|---|---|
| `index.html` | Contact list view |
| `add-contact.html` | Add new contact form |
| `edit-contact.html` | Edit existing contact |
| `enter-api-key.html` | API key setup screen |
| `config.js` | API base URL and auth logic |

---

> Built with HTML · CSS · JavaScript · REST API
