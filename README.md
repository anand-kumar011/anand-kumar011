<h1 align="center">Hi, I'm Anand 👋</h1>

<p align="center">
  Data Science & Artificial Intelligence undergraduate at IIT Guwahati<br>
  I build things that turn messy real-world data into decisions people can act on.
</p>

<p align="center">
  <a href="https://linkedin.com/in/anandk0040"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

---

### About me

- 🛰️ Working on **UHI-India** — measuring and simulating urban heat islands across 47 Indian cities from satellite data
- 🧪 Interested in the place where **physics and machine learning meet**: models that respect what we already know rather than ignoring it
- 🔍 I care about work being *checkable*. Models get validated against independent data, and outputs say what they can't tell you
- 🏛️ Previously interned at the **Indian Cyber Crime Coordination Centre (I4C)**, Ministry of Home Affairs

---

### Tech stack

**Machine learning & data**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![SHAP](https://img.shields.io/badge/SHAP-6E40C9?style=for-the-badge&logo=python&logoColor=white)

**Geospatial**

![Google Earth Engine](https://img.shields.io/badge/Earth%20Engine-4285F4?style=for-the-badge&logo=googleearth&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=for-the-badge&logo=leaflet&logoColor=white)
![geemap](https://img.shields.io/badge/geemap-2E8B57?style=for-the-badge&logo=python&logoColor=white)

**Building & shipping**

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

### Projects

**[UHI-India](https://github.com/anand-kumar011/uhi-india)** — urban heat intelligence for Indian cities

Measures, explains and simulates urban heat islands across 47 cities using Landsat 8, ECOSTRESS and ERA5 data. A physics-informed Random Forest takes a surface-energy-balance estimate as an input feature, so the model learns corrections to the physics instead of replacing it. SHAP explains why each city is hot; a genetic-algorithm optimizer plans cooling interventions within a given budget.

The part I'd point at: validation runs against ECOSTRESS, an independent NASA satellite, rather than the training data — so the error numbers mean something. And the optimizer reports quantities, not land parcels, because the data can't support that precision.

`Python` · `Flask` · `Earth Engine` · `scikit-learn` · `SHAP` · `pymoo` · `Leaflet`

**[Digital Footprint Checker](https://github.com/anand-kumar011/digital-footprint-checker)** — bulk investigation tooling

Built during my I4C internship to replace a manual, one-number-at-a-time process: an Excel list of mobile numbers goes in, a formatted per-platform presence report comes out. The public version is a safe re-implementation — the platform checkers are stubs returning simulated results, and the sample data is fictional. Everything around them is the real pipeline.

`Python` · `Flask` · `pandas` · `openpyxl`

---

### GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=anand-kumar011&show_icons=true&hide_border=true&theme=tokyonight" alt="Anand's GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=anand-kumar011&layout=compact&hide_border=true&theme=tokyonight" alt="Most used languages">
</p>

---

<p align="center">
  Open to internships and research collaborations in ML, remote sensing and climate tooling.
</p>
