# T-LITE (Traknus Lithium Intelligence Evaluator)

*Smart Battery Sizing and Cost Simulator*

T-LITE is a web application for estimating forklift battery runtime and comparing battery ownership costs. It provides two analysis modules: **Lithium Battery Simulator** and **Total Cost of Ownership (TCO)**.

The start screen captures the customer company, work location, and salesperson. These details appear in the analysis summary and PDF report.

## Features

- Estimate battery runtime and remaining charge based on truck model, battery capacity, operating intensity, shift schedules, breaks, and charging opportunities.
- Compare Lead Acid and Lithium battery costs using the TCO calculator.
- View, share, and print analysis results as a PDF.
- Switch between Indonesian and English.

## Usage

1. Open the GitHub Pages URL in a browser.
2. Enter the customer company, work location, and salesperson.
3. Choose **Lithium Battery Simulator** or **TCO**.
4. Enter the required information and run the analysis.
5. Review, share, or print the results.

## Project Structure

- `index.html` — application interface and logic
- `catalog.json` — forklift model and battery specification data
- `manifest.webmanifest` — web app metadata
- `sw.js` — service worker
- `assets/` — images used by the application
- `icons/` — application icons

Keep these files and folders in the repository root so the application can load them correctly.

## GitHub Pages

1. Upload the complete contents of this folder to the repository root. Include `index.html`, `catalog.json`, `manifest.webmanifest`, `sw.js`, and the `assets` and `icons` folders.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose branch `main` and folder `/(root)`.
5. Click **Save**.
6. After GitHub finishes publishing, open the GitHub Pages URL in a browser.

T-LITE is a static HTML, CSS, and JavaScript application. Customers can use it in a browser without installing Python or Streamlit.

## Notes

- `catalog.json` is required for the model specifications to load.
- Keep the file and folder names unchanged unless you also update their paths in the application.
- Analysis results are estimates based on the information entered and specifications available in the application.
