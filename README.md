# 📸 Photography Reference Guide

---

## **Section 1: Photography Genres (43 Slots)**

| Category | Genres |
|----------|--------|
| **People & Portraits** | Portrait, Lifestyle, Fashion, Glamour, Boudoir, Wedding, Family/Newborn, Candid |
| **Nature** | Landscape, Seascape, Wildlife, Macro, Underwater, Astrophotography, Bird, Cloudscape |
| **Urban** | Architecture, Real Estate, Interior, Street, Cityscape, Urbex |
| **Commercial** | Product, Food, Still Life, Advertising, Jewelry, Stock |
| **Action** | Sports, Concert/Event, Documentary, Photojournalism, War/Conflict, Adventure |
| **Artistic** | Fine Art, Abstract, Long Exposure, Infrared, B&W, Double Exposure, Minimalist, Composite, Drone |

---

## **Section 2: Composition Techniques (42 Slots)**

| Category | Techniques |
|----------|-----------|
| **Structure** | Rule of Thirds, Golden Ratio, Golden Spiral, Centered Symmetry, Horizontal/Vertical Symmetry |
| **Geometry** | Leading Lines, Converging Lines, Diagonals, Horizontals, Verticals, S-Curves, Triangles, Pattern, Breaking Pattern |
| **Depth** | Overlapping, Layering, Frame-in-Frame, Atmospheric Perspective, Forced Perspective, Shadow/Highlight, Diminishing Scale |
| **Focus** | Point of Interest, Simplification, Negative Space, Isolation, Color Contrast, Value Contrast, Rule of Odds, Figure-to-Ground |
| **Dynamic** | Dutch Angle, Motion Blur, Juxtaposition, Fill the Frame, Headroom, Lead Room, Rule of Space, High Angle, Low Angle, POV, Radial Balance, L-Composition, Golden Triangle |



## 🚀 Features

- **Dual-Tab Interface:** Easily switch between Photography Genres and Composition Techniques.
- **Interactive Frames:** Click any placeholder to preview a photo from your local device instantly.
- **Hybrid Storage:**
    - **Code-Based:** Add permanent image URLs or local paths directly into the `photoDatabase` object.
    - **Browser-Based:** Uploaded images persist via `localStorage` (so they stay there even if you refresh).
- **Dark Mode UI:** A sleek, minimalist aesthetic designed to make your photography "pop."
- **Responsive Design:** Works seamlessly on desktops, tablets, and smartphones.

## 🛠 Setup & Installation

Since this is a single-file application, setup is instant:

1.  Download or copy the `index.html` code.
2.  Save it into a dedicated folder (e.g., `Documents/Photography_Project/`).
3.  Open `index.html` in any modern web browser (Chrome, Firefox, Safari, Edge).

## 🖼 How to Add Your Photos

There are two ways to add your images to the dashboard:

### Method 1: The "Permanent" Way (Editing the Code)
Recommended for your final shots. This ensures your photos stay in the dashboard forever.
1. Create an `images/` folder in the same directory as your HTML file.
2. Open the HTML file in a text editor (VS Code, Notepad, etc.).
3. Locate the `const photoDatabase` object at the top of the `<script>` section.
4. Add your file path or a web URL next to the corresponding title:
   ```javascript
   "Portrait": "images/my_best_portrait.jpg",
   "Rule of Thirds": "https://yourwebsite.com/photo.jpg",
   ```

### Method 2: The "Quick" Way (Browser Upload)
Great for testing or temporary tracking.
1. Open the dashboard in your browser.
2. Click on any placeholder card.
3. Select an image from your computer.
4. The image will be stored in your browser's memory (`localStorage`). *Note: Clearing your browser cache may remove these images.*

## 📋 Content Roadmap

The dashboard includes placeholders for the following **85 categories**:

### Photography Genres (43)
- **People:** Portrait, Lifestyle, Fashion, Glamour, Boudoir, Wedding, Family/Newborn, Candid.
- **Nature:** Landscape, Seascape, Wildlife, Macro, Underwater, Astrophotography, Bird, Cloudscape.
- **Urban:** Architecture, Real Estate, Interior, Street, Cityscape, Urbex.
- **Commercial:** Product, Food, Still Life, Advertising, Jewelry, Stock.
- **Action:** Sports, Concert/Event, Documentary, Photojournalism, War/Conflict, Adventure.
- **Artistic:** Fine Art, Abstract, Long Exposure, Infrared, Black & White, Double Exposure, Minimalist, Composite, Drone/Aerial.

### Composition Techniques (42)
- **Structural:** Rule of Thirds, Golden Ratio, Golden Spiral, Symmetry (Centered/Horizontal).
- **Geometry:** Leading Lines, Converging, Diagonals, S-Curves, Triangles, Patterns, Pattern Breaking.
- **Depth:** Overlapping, Layering, Frame-in-Frame, Atmospheric Perspective, Forced Perspective, Shadows.
- **Attention:** Point of Interest, Minimalism, Negative Space, Subject Isolation, Color/Value Contrast, Rule of Odds.
- **Advanced:** Dutch Angle, Motion Blur, Juxtaposition, Fill the Frame, Headroom, Lead Room, POV, Radial Balance, Golden Triangle.

## 📝 Technical Details
- **Language:** HTML5, CSS3, JavaScript (Vanilla).
- **Icons/Fonts:** Uses "Inter" system fonts for a clean look.
- **Storage Limit:** Browser `localStorage` usually limits storage to 5MB. For high-resolution galleries, **Method 1 (Code-based paths)** is highly recommended.

---
*Capture the world, one frame at a time.*
