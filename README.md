# Punch

Punch is a local-first emotional support web app built as a single-page HTML/CSS/JavaScript project.

It helps users:

- Save private daily check-ins
- Write journal entries
- Use a guided breathing exercise
- Use 5-4-3-2-1 grounding prompts
- View saved entries in a calendar
- Export selected entries to PDF through the browser print dialog
- Store a trusted contact and personal safety plan locally on the device

## Privacy

Punch stores data in the browser using `localStorage`. The app does not send journal entries, check-ins, safety plan text, or trusted contact information to any server.

Important: because data is stored only in the browser, clearing browser storage or opening the app on another device/browser will not automatically transfer saved records.

## Safety note

Punch is not a medical product, therapy service, crisis service, or replacement for professional care. If someone is in immediate danger or may hurt themselves, they should contact local emergency services or a crisis line right away.

## How to run locally

1. Download or clone this repository.
2. Open `index.html` in a web browser.

No installation is required.

## How to publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload these files to the repository:
   - `index.html`
   - `README.md`
   - `LICENSE`
   - `.gitignore`
   - `.nojekyll`
3. Go to **Settings** → **Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Click **Save**.
6. Wait for GitHub Pages to generate your site link.

Your app will be available at a URL like:

```text
https://your-username.github.io/your-repository-name/
```

## Suggested repository description

A local-first mental wellness check-in and journaling web app built with HTML, CSS, and JavaScript.

## Tech stack

- HTML
- CSS
- Vanilla JavaScript
- Browser `localStorage`

## Project structure

```text
punch/
├── index.html
├── README.md
├── LICENSE
├── .gitignore
└── .nojekyll
```

## Future improvements

- Add optional password protection
- Add data import/export as JSON
- Improve mobile layout for very small screens
- Add language options
- Split HTML, CSS, and JavaScript into separate files

## License

This project is licensed under the MIT License.
