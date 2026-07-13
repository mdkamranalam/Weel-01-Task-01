# FlyRank AI — Week 01 | Task 01: Minimal Express API

A tiny Express.js backend for Week 1, Task 1 of the FlyRank AI Backend Engineering Internship. Provides two minimal JSON endpoints for learning and testing.

## Quick Start

Prerequisites: Node.js 14+ and npm.

Install dependencies:

```bash
npm install
```

Run the server (default script):

```bash
npm start
```

Run in development (auto-reload if configured):

```bash
npm run dev
```

By default the server listens on port `3000` (override with `PORT` env variable).

## Available Scripts

- `npm start` — start the server for production
- `npm run dev` — start the server for development (if present)

## Endpoints

- GET / — Health / welcome message
- GET /profile — Simple profile JSON

Example responses:

Home:

```json
{ "success": true, "message": "Hello from my backend!" }
```

Profile:

```json
{
  "name": "Kamran",
  "role": "Backend Engineering Intern",
  "learning": "Express.js"
}
```

Example curl commands:

```bash
curl http://localhost:3000/
curl http://localhost:3000/profile
```

## Project Structure

```
.
├── src/server.js         # Express server and route handlers
├── package.json
├── .gitignore
└── README.md
```

## Environment

You can set `PORT` to change the listening port, e.g.:

```bash
PORT=4000 npm start
```

## Contributing

Small project — open an issue or submit a PR. Keep changes focused and include a short description.

## License & Notes

This repository was created for educational purposes as part of the FlyRank AI internship. See `LICENSE` if included in the repo for specific terms.

---

Author: Md. Kamran Alam — https://github.com/mdkamranalam
