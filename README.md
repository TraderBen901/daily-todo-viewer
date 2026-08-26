# Daily To-do Viewer

Generic static viewer for a private daily to-do payload carried in the URL fragment.

- The repository contains no personal task data.
- URL fragments (`#...`) are not sent to GitHub Pages.
- The fragment is removed from the address bar before rendering.
- JSON values are rendered through DOM `textContent`; arbitrary HTML is not executed.
- Checkboxes and manual additions are stored in browser `localStorage`.
- Unfinished tasks from the immediately preceding day roll over automatically; completed tasks do not.

This viewer is intentionally standalone and has no analytics or external dependencies.
