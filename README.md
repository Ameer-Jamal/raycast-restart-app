# Restart App

Search your running Mac apps in Raycast and press Return to quit and reopen the selected app.

- **Restart** asks the app to quit normally, so it can prompt you to save your work.
- **Force Restart** is in the Actions panel (`⌘K`). Use it when an app is frozen. It asks for confirmation because unsaved changes can be lost.
- **Quit** is in the Actions panel and closes the selected app normally.

Use the arrow keys to move between apps and press Return on each one, or type to filter the list. Raycast keeps your search when an app restarts in the background.

App discovery and restarts run locally. The extension makes no network requests.

[See the command in Raycast](metadata/restart-app-1.png)

## Install locally

Requires Raycast on macOS and Node.js 22.22.2 or later for development. Clone this repository and run:

```bash
npm ci
npm run dev
```

Open Raycast and search for **Restart App**.

## Develop

```bash
npm run lint
npm run typecheck
npm test
npm run build
```

[MIT License](LICENSE)
