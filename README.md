## 🕉️ Jyotirlinga Spiral Map – Interactive Visualization

This project is a Python-based interactive map visualizing the **12 sacred Jyotirlingas** of Lord Shiva across India in an **anti-clockwise spiral path**, symbolizing energy flow and pilgrimage tradition.

### 🙏 Acknowledgements

*   Special thanks to [Dr. Anadi Sahoo](https://www.linkedin.com/in/dranadisahoo/) for his insightful LinkedIn post and perspective on the Jyotirlinga spiral pattern.

*  Gratitude also to the open-source contributors of the [GeoHacker India Map Project](https://github.com/geohacker/india/tree/master/state) for providing the geospatial data that made this visualization possible.


---

### ✨ Key Features

1. **🗺️ Interactive Map using Folium:**

   * Built with `folium`, allowing zoom, pan, and detailed views of each location.
   * Clean and minimal base tiles (`CartoDB Positron`) for clarity.

2. **🔴 Red Number Markers:**

   * Each temple is marked with a bold, red-numbered circle for easy identification.
   * Numbers correspond to the sequence in the spiritual spiral journey.

3. **🌀 Animated Spiral Path (Anticlockwise):**

   * Smooth animated spiral created using spline interpolation (`scipy.interpolate.splprep`).
   * `AntPath` shows animated golden flow, symbolizing divine energy.

4. **🕍 Temple Name Labels:**

   * Each temple's name appears next to its marker with index and name.
   * Dynamically positioned to prevent overlapping.

5. **📜 Informative Popups:**

   * Clicking a marker opens a popup with:

     * Temple name
     * State location
     * Mythological or historical background info

6. **🟣 Spiritual Center Highlight:**

   * A subtle purple dot marks the geographic center of all Jyotirlingas, suggesting a central point of energy.

---

### 🔧 Technologies Used

* **Python 3**
* **Folium** – Interactive maps
* **NumPy & SciPy** – Spline interpolation for smooth spiral path
* **HTML/CSS in DivIcons** – Custom marker styling

---

### 🚩 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/raz455/Geometrical-Magic-and-Ancient-Secrets-of-12-Jyotirlingas
   cd jyotirlinga-spiral-map
   ```

2. Install requirements:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the script:

   ```bash
   python spiral_map.py
   ```

4. Output `map.html` will be generated. Open it in a browser.

---

### 🙏 About Jyotirlingas

The **12 Jyotirlingas** are the most revered shrines of Lord Shiva. Each represents a unique manifestation and is deeply rooted in Vedic, Puranic, and spiritual lore. Pilgrimage to these shrines is considered one of the holiest acts in Shaivism.



