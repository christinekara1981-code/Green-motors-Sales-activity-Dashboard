# Green Motors GitHub Pages Dashboard

This version is designed for GitHub Pages.

## Architecture

- GitHub Pages hosts the user form/dashboard.
- Google Apps Script acts as the API.
- Google Sheets is only used for storing data.

## Setup

1. In Apps Script, replace `Code.gs` with `apps_script_api/Code.gs`.
2. Run `setupInitialData()` once.
3. Deploy Apps Script as a Web App.
4. Copy the Web App URL ending in `/exec`.
5. Paste that URL into `config.js`.
6. Upload `index.html` and `config.js` to a GitHub repository.
7. In GitHub, go to Settings > Pages and deploy from the main branch.

## Usage

Open the GitHub Pages URL. Do not open the local `file:///` file.
Sales executives use the form; Google Sheet remains the database.
