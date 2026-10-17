# builtenv-code

Conding 2026: building-aware coding experiments and prototypes for the built environment.

<p align="center">
  <img src="assets/backdrop.svg" alt="Conding 2026 backdrop" width="1200" />
</p>

A modern open-source project focused on building data, urban context, and prototype-ready workflows. This repository is designed for experimentation, exploration, and developer-friendly tooling around the built environment.

## Why this project?

builtenv-code brings together:

- building-aware coding experiments
- lightweight data and modeling workflows
- prototype-ready visual tooling
- open-source collaboration for built-environment ideas

It is intentionally simple, flexible, and designed to be extended by contributors working on architecture, urban systems, spatial analysis, and computational design.

## Project focus

This project is centered around the built environment, including:

- building metadata and attributes
- footprint and spatial datasets
- prototype data cleaning and transformation workflows
- small-scale analysis and visualization tooling
- research and educational case studies

## Quick start

### 1. Clone the repository

```bash
git clone https://github.com/stel79/builtenv-code.git
cd builtenv-code
```

### 2. Create a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate
```

On Windows:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the sample script

```bash
python src/sample_building_logic.py --name "Example Tower" --floors 12 --area 5400 --year 2026 --json
```

Example output:

```json
{
  "name": "Example Tower",
  "floors": 12,
  "area_m2": 5400.0,
  "year_built": 2026,
  "description": "Example Tower is 12-story 5400.0 m² built in 2026."
}
```

## Project structure

```text
builtenv-code/
├── README.md
├── LICENSE
├── prototype.html
├── download.html
├── requirements.txt
├── .gitignore
├── assets/
│   └── backdrop.svg
├── src/
│   ├── sample_building_logic.py
│   └── electron/
│       └── main.js
├── build/
│   └── icon.png
├── dist/
│   └── (build outputs)
├── docs/
│   └── (optional future docs)
└── tests/
    └── (optional future tests)
```

## Prototype and download page

This project includes:

- `prototype.html` — interactive mockup/prototype for a dashboard-style landing page
- `download.html` — link page with instructions for opening the prototype and downloading a PNG or HTML copy

Open the prototype in a browser to interact with the mockup and export screenshots directly from the page.

## Roadmap

Planned work includes:

- expanded building data utilities
- spatial analysis examples
- stronger docs and tutorials
- richer prototype screens and app interfaces
- installer and packaging support for macOS, Windows, and Linux

## Contributing

Contributions are welcome.

If you would like to contribute:

1. Fork the repository.
2. Create a feature branch.
3. Add your code or improvements.
4. Open a pull request with a clear summary.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions, suggestions, or collaboration ideas, open an issue in the repository or reach out through the project discussion channels.

---

Built for open exploration of the built environment in 2026.
