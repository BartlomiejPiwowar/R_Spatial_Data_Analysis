🗺️ **Spatial Data Analysis (Cracow)**
*(Spatial Clustering of Urban Data Using R)*
R-based project that analyzes and clusters spatial data from Cracow using advanced density-based algorithms. The project demonstrates practical spatial techniques in R, focusing on real-world urban operations like mapping city districts and clustering urban violations.

The goal of the project is to apply spatial analysis principles while practicing practical implementations of clustering algorithms such as DBSCAN and HDBSCAN.

🧩 **Key Features**
- Load and visualize spatial shapefiles (districts and violation points).
- Transform coordinate systems to ensure accurate data overlay.
- Prepare point-based datasets for clustering.
- Perform spatial clustering using DBSCAN and HDBSCAN algorithms.
- Assign and visualize clusters on maps for comparison.

🔧 **Technologies Used**
- Language: R
- Spatial Libraries: sf, dbscan
- Techniques: Spatial Data Analysis, Clustering, Data Visualization

📁 Project Structure
- Spatial Data Loading → Reading shapefiles (osiedla.shp, zestaw5_XYTableToPoi_Project.shp).
- Data Transformation → CRS alignment for accurate spatial analysis.
- Clustering Algorithms:
  - DBSCAN → Density-based clustering with fixed neighborhood radius.
  - HDBSCAN → Hierarchical clustering with adaptive density detection.
- Visualization → Maps showing cluster formation across different parameter settings.
- Comparison & Conclusions → Evaluation of DBSCAN vs HDBSCAN performance in real-world data.
