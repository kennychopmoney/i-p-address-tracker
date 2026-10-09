# IP Atlas

A lightweight static web app for looking up public IP geolocation details.

## Features

- Enter any IPv4 or IPv6 address
- View approximate location, country code, ISP, ASN, timezone, and coordinates
- Open the result on OpenStreetMap
- Uses the public ipwho.is API for geolocation data

## Run locally

1. Open `index.html` in a browser, or
2. Serve the folder locally with a simple static server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to GitHub Pages

This project is configured for GitHub Pages via a GitHub Actions workflow.

## Note

IP geolocation can only provide approximate network-level information and is not always exact to a physical address.
