🏥 Optimal Hospital Site Selection in Fes, Morocco Using GIS and AHP


📌 Project Overview


This project aims to support healthcare infrastructure planning in Fes, Morocco, by identifying optimal locations for new hospitals and evaluating the suitability of existing hospital locations using Geographic Information Systems (GIS) and Multi-Criteria Analysis (MCA) techniques, specifically the Analytic Hierarchy Process (AHP).


By integrating spatial and non-spatial data within QGIS, this study provides a decision-support tool for urban planners, policymakers, and health authorities to improve accessibility to healthcare services.
🎯 Objectives

    📍 Determine the most suitable sites for new hospital establishments in Fes.

    🧭 Evaluate the locations of existing hospitals using weighted criteria.

    🗺️ Produce thematic spatial maps to support urban healthcare planning.

    💡 Deliver clear recommendations for future hospital development.

🛠️ Methodology
1. Criteria Definition

Key factors influencing hospital location suitability were selected:

    🚗 Accessibility (roads, transport)

    🏥 Proximity to existing medical services

    📐 Plot size and land availability

    🏗️ Infrastructure support (water, electricity, etc.)

    🧍 Community needs and population density

2. Weight Assignment using AHP

Each criterion's importance was evaluated using the Analytic Hierarchy Process (AHP), generating a consistent weighting matrix.
3. Spatial Analysis in QGIS

    Criteria maps were created and standardized.

    Weighted overlay analysis was conducted using the AHP weights.

    Suitability index maps were generated.

4. Multicriteria Analysis (MCA)

    MCA was performed to rank potential sites.

    Final maps visualize optimal zones for new hospital sites.

🧾 Dataset Description

    Population data (INSAF, WorldPop, etc.)

    Infrastructure layers: roads, utilities, public facilities

    Land use / land cover maps

    Current hospital locations

    High-resolution satellite imagery

🛠️ Tools & Technologies

    🧭 QGIS for spatial data processing and visualization

    📊 AHP (Python / Excel / AHP plugins) for weight derivation

    🖼️ Raster Calculator / Weighted Overlay in QGIS

    💾 GeoTIFF / Shapefile / CSV formats

📂 Project Structure

📁 hospital-site-selection-fes/

├── 📁 data/                 # Spatial and attribute data

├── 📁 scripts/              # Python scripts or AHP calculations

├── 📁 maps/                 # Generated suitability and evaluation maps

├── 📁 docs/                 # Reports and documentation

├── AHP_matrix.xlsx         # Pairwise comparison matrix

├── README.md               # Project overview

└── requirements.txt        # Python dependencies (if applicable)

🚀 Getting Started
📦 Requirements

    QGIS 3.x

    AHP plugin (optional)

    Python 3.8+ (if running custom scripts)

▶️ Steps to Reproduce

    Load all spatial layers into QGIS.

    Normalize raster layers representing criteria.

    Use AHP-calculated weights in Raster Calculator to perform weighted overlay.

    Generate final suitability map.

    Interpret and export maps as PNG or PDF.

📊 Results & Insights

    Thematic maps highlight the most and least suitable zones in Fes.

    Several high-potential areas identified for new hospital locations.

    Existing hospitals show varying degrees of suitability, with some requiring reconsideration or enhancement.

    Maps and analysis support evidence-based decision-making.

📌 Recommendations

    Focus investment in high-ranked zones identified by the model.

    Consider complementary infrastructure development in moderately suitable zones.

    Reassess hospital locations that scored low in the current evaluation.

🤝 Contributing

Contributions, suggestions, or data improvements are welcome!
Please open an issue or submit a pull request.
📄 License

📬 Contact

IDRISSI MOUNADI DOHA – Urban GIS Analyst / Researcher
📧 idrissimounadidoha@gmail.com
https://www.linkedin.com/in/doha-idrissi-mounadi-68b9801a4/
