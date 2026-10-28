# Food Verse AI — Indian Food Intelligence

A responsive, multi-view Indian food and nutrition frontend concept. Explore regional dishes, vegetarian meal planning, estimated nutrition, and an image-preview scanner interface.

> **Prototype:** Image recognition, live AI responses, and nutrition lookups are not connected. Nutrition values and recipe details are illustrative estimates. Uploaded photos are previewed locally in the browser.

## Features

- Home dashboard featuring an Indian thali and meal summary
- Image upload with local preview and clearly labelled demo analysis
- Nutrition overview with approximate serving values
- Weekly vegetarian, Jain, and vegan meal plan controls
- Searchable recipe explorer with Gujarati, South Indian, North Indian, Bengali, Maharashtrian, and Rajasthani filters
- Responsive navigation and layouts for desktop and mobile

## Technology

HTML5, CSS3, and vanilla JavaScript. No build step or package installation is required. Google Fonts and food photography load from external services.

## Project structure

```text
Food-Verse-AI/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── README.md
└── .gitignore
```

There are no local image assets currently, so the app retains its remote image references and does not include an empty `assets/images` directory.

## Run locally

Open `index.html` in a modern browser, or run a simple server from this folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`. Internet access is needed for remote fonts and food images.

## Deploy to Netlify

1. Push this folder to a GitHub repository.
2. In Netlify, choose **Add new site → Import an existing project** and connect the repository.
3. Set the publish directory to the repository root (`.`). Leave the build command empty.
4. Deploy the site.

Alternatively, use Netlify Drop to deploy this folder directly.

## Screenshots

Screenshots are not included yet. Add a dashboard capture here when available.

## Future improvements

- Connect a secure vision model for ingredient recognition
- Add a trusted nutrition database and serving-size confirmation
- Persist meal plans and preferences
- Add accessibility, browser-based interaction, and mobile QA

## License

No license has been selected. Until one is added, reuse and distribution permissions are not granted by this repository.
