##  Urban Heat Island (UHI) Prediction

This project aims to model and predict **Urban Heat Island (UHI)** intensity using machine learning. UHI refers to elevated temperatures in urban areas compared to surrounding rural zones, driven by human activity, infrastructure, and land use. Understanding and mitigating UHI is essential for building more sustainable and livable cities.

The notebook walks through the complete workflow: from **setting up the environment**, **loading and cleaning data**, to **feature engineering** and **model training**. It uses relevant features such as temperature, humidity, land cover type, and elevation.

Multiple models are tested—ranging from baseline linear regression to more advanced tree-based methods. Their performance is evaluated using appropriate regression metrics. The best-performing model is selected to forecast UHI intensity across different urban conditions.

Visualizations are provided throughout to interpret the data and explain the model outputs. This work supports evidence-based urban planning and environmental risk management.

### Tools & Libraries
- **Data & ML**: `pandas`, `numpy`, `scikit-learn`, `tqdm`  
- **Geospatial**: `geopandas`, `rioxarray`, `xarray`, `rasterio`, `pyproj`, `pystac`, `planetary_computer`, `odc.stac`  
- **Visualization**: `matplotlib`, `seaborn`  
