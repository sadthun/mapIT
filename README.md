

---

## 🗺️ Interactive Map of Italy

This project features a **fully interactive SVG map of Italy** that allows users to select a region and navigate to a corresponding page.

### ✨ Features

- **Clickable Regions**: Each Italian region is clickable via SVG. When a region is selected, it is highlighted in dark green and its name appears in a styled info box.
- **Search Button**: After selecting a region, users can click the **"Search"** button to be redirected to a dedicated HTML page for that region (e.g., `lazio.html`, `sardegna.html`).
- **Responsive Layout**: The map container is centered and responsive, adapting smoothly to different screen sizes.
- **Real-time Feedback**: If the user clicks "Search" without selecting a region, an alert notifies them to make a selection first.

### 🧩 Technologies Used

- **HTML5** and **CSS3** for layout and styling
- **JavaScript** for dynamic interaction with the SVG map
- **SVG file (`/img/it.svg`)** to render the interactive regions

### 🧭 How It Works

1. The SVG map is embedded via an `<object>` tag.
2. JavaScript listens for clicks on individual `<path>` elements inside the SVG.
3. Upon selection, the region is visually highlighted and stored.
4. Clicking the **"Search"** button redirects to a page named after the selected region.

---
