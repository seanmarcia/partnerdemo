# Partner API demo

A standalone browser-based tester for the GitHub for Nonprofits partner API.

## Hosting

The demo is hosted at https://seanmarcia.github.io/partnerdemo/.
GitHub Pages publishes the repository root from the `main` branch. Changes to
[index.html](./index.html) go live after they are committed and pushed to `main`.

## API access

Live requests require the API at `https://nonprofits.github.com` to allow the
origin `https://seanmarcia.github.io` and the `Authorization` header through
CORS. GitHub Pages cannot grant that permission; it must be configured on the
API server.

The demo does not store API keys. Never commit a key to this repository.
