# Data Analysis Web Application

This web application allows users to load and view a sample of data processed from an Excel file converted to CSV. It demonstrates integration of static data files with a Bootstrap-styled frontend.

## Files included:
- `index.html`: Main web application with Bootstrap 5 styling.
- `LICENSE`: MIT License.
- `data.csv`: Data converted from `data.xlsx`.
- GitHub Actions workflow for CI/CD.

## Usage
- Open `index.html` in a modern browser.
- Click the "Load Data" button to fetch and display a sample of the data.

## Automation & CI/CD
- The GitHub Actions workflow automates code linting with Ruff, runs the Python script `execute.py` to produce `result.json`, and publishes results via GitHub Pages.

---

## License
This project is licensed under the MIT License. See `LICENSE` for details.
