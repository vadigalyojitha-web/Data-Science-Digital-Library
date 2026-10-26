# Data Science Digital Library

A student-focused library for Data Science course modules, learning tools, resources, assignments, lab experiments, and student profiles.

## Run locally

Serve this folder over HTTP so PDF.js can load the local PDF files. From this directory, run:

```powershell
python -m http.server 8000
```

Then open <http://127.0.0.1:8000/>.

## Publish with GitHub Pages

In the repository settings, open **Pages**, select **Deploy from a branch**, choose `main` and `/ (root)`, then save. The site will be served from the repository root.

Student profile edits are stored in the browser's local storage for the current site address and browser. Data saved on the local preview is separate from data saved on the GitHub Pages site. The public starter profile intentionally omits student ID, email, and private resume details.
