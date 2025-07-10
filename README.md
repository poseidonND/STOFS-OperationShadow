# STOFS-OperationShadow
STOFS-2D Global Model (University of Notre Dame)
This repository contains the configuration used for the STOFS-2D Global Model operated at the University of Notre Dame. The model is a depth-averaged, hydrodynamic model that simulates global water levels, tides, and storm surge with high-resolution capabilities, especially focused around U.S. coastlines.

🌐 Model Overview:
The STOFS-2D Global Model (Surge and Tide Operational Forecast System – 2D) is designed for high-fidelity simulation of water levels across the globe. It incorporates barotropic and baroclinic physics and is capable of resolving storm surge, tides, and large-scale baroclinic effects from ocean stratification.

🔧 Forcing Inputs
Baroclinic Forcing: From NOAA's Global Real-Time Ocean Forecast System (RTOFS)

Applied to drive density-driven circulation in 2D mode with Baroclinic Pressure Gradients computed with RTOFS depth averaged temperature and salinity fields. 

Atmospheric Forcing: From GFS 13 km resolution (Global Forecast System)

Wind (10 m u/v components)

Atmospheric pressure (sea level)

Sea ice coverage and fraction

🗺️ Grid and Resolution:
Unstructured finite element mesh optimized for scalability and nearshore accuracy

Resolution:

~120 m in U.S. coastal waters, 60 m in Columbia, 200 m for the Japan coast

~2 km nearshore globally

~25 km in deep ocean basins

The mesh is designed to efficiently resolve storm surge and coastal processes in high-risk areas while maintaining computational tractability globally.

🏛️ Operated By:
This version of the STOFS-2D Global Model is maintained and operated by the University of Notre Dame in collaboration with NOAA and other stakeholders to improve operational forecasting and coastal risk assessment.
