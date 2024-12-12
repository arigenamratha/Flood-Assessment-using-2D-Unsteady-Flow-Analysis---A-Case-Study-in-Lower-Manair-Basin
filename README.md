# 🌊 Flood Risk Assessment Using 2D Unsteady Flow Analysis  
**A Case Study in Lower Manair Basin**  

---

## 🚨 **Important Notice**
## 🚨 **Looking for Project Files or Guidance on Flood Risk Assessment?** 
The project files are **not included in this repository**. If you would like access to the files or need assistance with this project, feel free to reach out:  

📱 **WhatsApp:** [+91 6300785953](https://wa.me/916300785953)  
📧 **Email:** [namratha.arige@gmail.com](mailto:namratha.arige@gmail.com)  

💡 **Why Connect?**  
- Access comprehensive models, simulation data, and flood mapping tools used in this project.  
- Learn how to use HEC-RAS, HEC-HMS, and QGIS effectively for flood risk assessment.  
- Collaborate on academic, research, or professional hydraulic modeling projects.  

👉 **Don't hesitate – let’s bring your ideas to life!**  

---

## 📑 **Overview**
This project leverages advanced hydraulic modeling and geospatial tools to assess flood risks in the Lower Manair Basin, a region prone to recurrent flooding. The study integrates **HEC-RAS**, **HEC-HMS**, and **QGIS** to simulate 2D unsteady flow conditions and produce actionable insights for flood management and urban planning.

---

## 🚀 **Key Highlights**
- **Study Area:** Lower Manair Basin in Telangana, India  
- **Tools Used:**  
  - [HEC-RAS](https://www.hec.usace.army.mil/software/hec-ras/) - 2D Unsteady Flow Analysis  
  - [HEC-HMS](https://www.hec.usace.army.mil/software/hec-hms/) - Rainfall-Runoff Modeling  
  - [QGIS](https://qgis.org/en/site/) - GIS and Terrain Preprocessing  
  - Python Scripts for automated data processing  
- **Data Sources:**  
  - DEM: USGS Earth Explorer  
  - Rainfall Data: Indian Meteorological Department (IMD)  
  - Discharge Data: Central Water Commission (CWC)

---

## 📂 **Project Structure**
```plaintext
├── data/                 # Raw and processed datasets
├── scripts/              # Python scripts for data processing
│   ├── rainfall_extraction.py
│   └── data_preprocessing.py
├── models/               # HEC-RAS and HEC-HMS model files
├── results/              # Simulation outputs (Flood maps, hydrographs)
├── docs/                 # Project report and documentation
│   └── Project_Report_Final.pdf
└── README.md             # This file
```

---

## 📊 **Methodology**
1. **Data Collection:**  
   - Precipitation, discharge, and land-use data were sourced from IMD, CWC, and USGS.  
   - Digital Elevation Models (DEM) with 30m resolution were used for terrain modeling.

2. **Data Processing:**  
   - Used QGIS for preprocessing terrain data and delineating watersheds.  
   - Applied the Thiessen Polygon method for rainfall distribution.

3. **Flood Modeling:**  
   - Simulated unsteady flow conditions in **HEC-RAS**.  
   - Developed flood inundation maps, velocity profiles, and depth analyses.

4. **Simulation Validation:**  
   - Validated model outputs with historical flood data from the 2016 floods.

5. **Analysis and Results:**  
   - Identified vulnerable areas.  
   - Developed recommendations for flood risk mitigation and infrastructure planning.

---

## 🌟 **Results**
- **Flood Maps:** Comprehensive maps showing inundation depths, velocities, and water surface elevations.
- **Key Insights:** Identified high-risk zones in the Lower Manair Basin, enabling targeted disaster management.
- **Future Applications:** Scalable methodology for assessing flood risks in other regions.

---

## 📌 **Key Features**
- Integration of hydrological and hydraulic models for comprehensive flood assessment.
- Use of open-source tools (QGIS) alongside specialized software (HEC-RAS, HEC-HMS).
- Application of 2D modeling for detailed spatial and temporal flood analyses.

---

## 🔍 **Future Scope**
- Real-time integration with weather APIs for dynamic flood predictions.
- Expansion to other basins to develop comparative flood risk assessments.
- Incorporation of climate change scenarios for long-term disaster preparedness.

---

## 🛠️ **Setup and Usage**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/flood-risk-assessment.git
   ```
2. Navigate to the project directory:
   ```bash
   cd flood-risk-assessment
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Explore the **`docs/`** folder for detailed project documentation.  
5. Run Python scripts in **`scripts/`** for data preprocessing or simulations.  

---

## 🤝 **Contributors**
- **Arige Namratha** (1005-20-732006)  
- **Bolle Srinath** (1005-20-732013)  
- **Devagoni Vijayalaxmi** (1005-20-732017)  
- **Gannoji Vaishnavi Sai Prasanna** (1005-20-732020)  
- **Supervisor:** Prof. P. Raja Sekhar  

---

## 📬 **Contact**
For inquiries or collaborations, please reach out to the contributors or open an issue in this repository.

---

## 🌐 **Acknowledgments**
Special thanks to:
- **Prof. P. Raja Sekhar**, for his guidance and support.  
- **Central Water Commission** and **Indian Meteorological Department** for providing critical data.  
- **University College of Engineering (Autonomous), Osmania University** for academic support.

---

## 🖼️ **Preview**
### **Simulated Depths at Different Time Series (2018)**
![Simulated Depths 2018](https://github.com/user-attachments/assets/63785e48-c6c9-4b95-ad16-d830071c2d45)

### **Simulated Depths at Different Time Series (2019)**
![Simulated Depths 2019](https://github.com/user-attachments/assets/156b0119-3fd7-47da-9407-a122b7132761)

### **Simulated Velocity (2019)**
![Simulated Velocity 2019](https://github.com/user-attachments/assets/f7894d39-07b7-44ca-8527-13a919a98cfb)

### **Simulated Water Surface Elevation (WSE) (2019)**
![Simulated WSE 2019](https://github.com/user-attachments/assets/de47451d-f316-4932-83b7-817f83ae21ea)

---

Feel free to customize the file further for your specific GitHub repository!

```  

This template ensures clarity and professionalism, making the project accessible to viewers and potential collaborators. Let me know if you'd like any further adjustments!
