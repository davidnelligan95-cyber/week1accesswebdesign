# Copilot Instructions for AI Agents

## Project Overview
This is a simple static website project for an introductory web design and development course. The structure is minimal and intended for educational purposes.

## Structure
- `index.html`: Main HTML file for the website. Entry point for the site.
- `res/`: Resource directory containing all assets and supporting files.
  - `styles/style.css`: Main stylesheet for the site. All CSS should be placed here.
  - `scripts/`: (Currently empty) Place all JavaScript files here if needed.
  - `img(1)/`: Contains image assets (e.g., `alien1.jfif`, `alien2.jfif`).
  - `img/`, `img(2)/`, `img(3)/`: Additional image folders (currently empty or for future use).

## Key Conventions
- All styling should be done in `res/styles/style.css`. Do not use inline styles in HTML unless absolutely necessary for demonstration.
- Place all images in the appropriate `img*` folders under `res/`.
- If adding JavaScript, create files in `res/scripts/` and link them in `index.html`.
- Keep the HTML structure simple and semantic for accessibility and learning clarity.
- No build tools, frameworks, or package managers are used. This is a pure HTML/CSS/JS project.

## Developer Workflow
- Open `index.html` directly in a browser to view the site. No build or serve step is required.
- To add new pages, create additional `.html` files at the root level and link them from `index.html`.
- To update styles, edit `res/styles/style.css`.
- To add images, place them in the appropriate `img*` folder and reference them with relative paths in HTML/CSS.

## Examples
- To add a new image: Place it in `res/img(1)/` and reference as `<img src="res/img(1)/alien1.jfif" alt="Alien">`.
- To add a new style: Edit `res/styles/style.css` and link the class in your HTML.

## No External Dependencies
- There are no external libraries or dependencies. All code should be self-contained.

## Additional Notes
- This project is intended for learning and demonstration. Keep code clear and well-commented for educational purposes.
- If you add new folders or files, update this instruction file to help future contributors and AI agents.
