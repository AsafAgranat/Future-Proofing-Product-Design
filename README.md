# Product Designer Skills Analysis - Duotone Infographic

This repository contains a single-page HTML infographic that creatively visualizes a "Product Designer Skills Analysis." The analysis focuses on strategic skills and marketing for product designers looking towards 2025-2030, based on insights from reports like the WEF Future of Jobs Report 2025 and tailored to a product designer's career path.

The infographic itself is designed with a unique, "out-of-the-box" visual style.

## Key Features

* **Dynamic Duotone Palette:** On every page load, a new random duotone color palette (one background color, one foreground color) is generated using JavaScript. These two colors are used for *all* visual elements on the page, including text, backgrounds, and chart elements.
* **Creative Visuals:** The design intentionally steps away from conventional UI elements like cards and shadows, aiming for a more artistic and poster-like presentation.
* **Chart.js for Data Visualization:** Charts are rendered using Chart.js on HTML Canvas elements.
* **Canvas Patterns for Differentiation:** To adhere to the strict duotone palette, chart datasets are differentiated using dynamically generated canvas patterns (lines, crosshatch, dots) drawn with the foreground color, instead of multiple solid colors.
* **Custom Legend Swatches:** The chart legends are customized to display these canvas patterns in the swatches, providing clear visual correspondence.
* **No SVG or Mermaid JS:** All graphics and diagrams are achieved using HTML/CSS (Tailwind CSS for layout) and Canvas rendering.
* **Responsive Design:** The layout is responsive and aims to adapt to different screen sizes.
* **Font:** Uses "IBM Plex Sans" for all text, loaded from Google Fonts.
* **Self-Contained:** The entire infographic is a single `index.html` file with embedded CSS and JavaScript.

## Content Focus

The infographic visualizes key aspects of the "Product Designer Skills Analysis," including:

* The evolving skillset for product designers (core, growing, and emerging skills).
* The importance of human-centric and meta-skills.
* Strategic skill focus areas like AI in design, data-informed design, and understanding developer platforms.
* Guidance on marketing these future-ready skills.
* Data points and insights are drawn from the provided "Product Designer Skills Analysis" document, which synthesizes information relevant to the field.

## How to View

1.  **Clone the repository (optional):**
    ```bash
    git clone <repository-url>
    cd <repository-name>
    ```
2.  **Open `index.html`:**
    Simply open the `index.html` file (from the `creative_duotone_skills_infographic_v1` artifact) directly in any modern web browser.

Each time you refresh the page, you'll see a new duotone color scheme.

## Source Material

The content and data for this infographic are based on the "Product Designer Skills Analysis" document provided by the user, which in turn references insights from sources like the World Economic Forum Future of Jobs Report 2025.

## Technologies Used

* HTML5
* CSS3 (with Tailwind CSS loaded via CDN)
* JavaScript (ES6+)
* Chart.js (loaded via CDN)
* Google Fonts (IBM Plex Sans)

---

This project was generated to showcase a creative approach to data visualization under specific aesthetic and technical constraints.
