# Share Your Screen — Zoom walkthrough

An animated, self-advancing walkthrough built for a 1:1 coaching student who
could not find the Zoom share control, and got stuck between the Zoom
Workplace app and the browser client.

- **Student link:** https://ericswegman.github.io/zoom-share-screen/
- Pure static HTML/CSS/JS. No login, no accounts, no data collected or stored.
- Two paths, chosen by the student on the first screen: **Zoom app** and
  **web browser**, because the picker dialog differs between them.
- Each path has two chapters: **sharing the whole screen**, then **sharing
  the TimeBack app window**. The app-window chapter exists because it is a
  different click with its own trap — Zoom and the browser only list apps
  that are *already open*, and in the browser they live under the **Window**
  tab, not Entire Screen or Chrome Tab. Both chapters close on the same
  fallback: sharing the whole screen always works.

Pushing to `main` redeploys via GitHub Pages.
