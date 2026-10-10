# Do Not Press

A tiny interactive story about a red button, a nervous building, and 50 increasingly questionable decisions. Each press advances the plot, changes the control room, and adds an incident to the log. The story ends with a quiet little payoff; press the button again to start over.

**Live site:** [hhgoawispr-seven.vercel.app](https://hhgoawispr-seven.vercel.app/)

## Run locally

This is a dependency-free static site. Open `index.html` in a browser, or serve the folder with any static web server:

```sh
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Deploy

The GitHub repository is connected to Vercel, so pushes to `main` deploy automatically:

- GitHub: [jainwinshubhi/hhgoa_wispr](https://github.com/jainwinshubhi/hhgoa_wispr)
- Vercel: [hhgoawispr-seven.vercel.app](https://hhgoawispr-seven.vercel.app/)

No build command or environment variables are required. Vercel can serve the repository root as a static site.

## Project files

- `index.html` — the complete responsive experience, styling, and 50 story beats
- `.gitignore` — excludes local secrets and Vercel working files
