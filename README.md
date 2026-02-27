# SightingsNodeApp

A simple Node.js web application for recording and viewing user-submitted "sightings" (e.g. UFOs, wildlife, etc.).

## Features

- Static HTML pages served from the `public/` directory
- Data stored in a local JSON file (`data/data.json`)
- Route handling and events in `handlers/` and `events/`
- Utility modules for input parsing, sanitization, and responses

## Getting Started

1. Ensure you have Node.js installed (v14+ recommended).
2. Clone or download the repository.
3. Install dependencies:
   ```bash
   npm install
   ```
4. Launch the server:
   ```bash
   node server.js
   ```
5. Open a browser and navigate to `http://localhost:3000` (default port).

## Project Structure

```
package.json
server.js
public/          # frontend files (HTML, CSS, JS, images)
data/            # JSON storage and story helper
handlers/        # routing logic
events/          # custom event emitters
utils/           # utility functions for various tasks
```

## Contributing

Feel free to submit issues or pull requests. This is a lightweight educational example.

## License

MIT License
