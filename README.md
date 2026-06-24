# to-day Help Documentation

This folder contains public-facing help documentation for to-day.

## Preview locally

Install MkDocs if it is not already installed:

```sh
python3 -m pip install mkdocs
```

Then run:

```sh
cd Public_Documentation
mkdocs serve
```

Open the local address shown by MkDocs, usually `http://127.0.0.1:8000`.

## Publishing

When the documentation is ready, this folder will be manually copied to the separate public GitHub repository. No external publishing service is required for local previews.
To build site:
'mkdocs build'

To push straight to GitHub:
'mkdocs gh-deploy'

## Content rules

- Keep the writing user-facing and suitable for public release.
- Do not add private development notes, internal plans, debug information, or unreleased feature details.
- Screenshots will be captured manually from the iOS Simulator.
- Screenshots must not include names, tasks, notes, accounts, notifications, or other personal data.
