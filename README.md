Compositional Spectral Balances for Random Forest Prediction of Spring Wheat Yield in Commercial Fields Using Sentinel-2 Imagery. 

Wilfried Dossou-Yovo1, Balwinder Kumar1, Haben Asgedom Tedla2, Haider Habbas1 

1 Lakeland College, Vermilion, Alberta, Canada.       
2 Agriculture and Agri-Food Canada (AAFC), Saskatoon, Saskatchewan, Canada.        

**Highlights**

    Eight ILR balances represent relative reflectance across nine Sentinel-2 bands. 

    ILR balances showed less uniform redundancy than conventional vegetation indices. 

    ILR improved internal-testing RF performance across four preprocessing approaches. 

    The lowest ILR validation RMSE was 23% below the lowest vegetation-index RMSE. 

    ALE revealed nonlinear yield responses to interpretable spectral balances. 

**Abstract** 

Satellite-based crop yield prediction commonly relies on vegetation indices derived from multispectral reflectance, but these indices often contain overlapping spectral information. This study compared conventional vegetation indices with compositional isometric log-ratio (ILR) spectral balances for random forest prediction of spring wheat yield. Yield-monitor and Sentinel-2 data were obtained from commercial fields across six growing seasons (2019–2024). Eight ILR balances were derived from nine spectral bands using sequential binary partitioning. Predictor redundancy and multivariate structure were examined using correlation analysis and principal component analysis (PCA). Random forest models were evaluated using four preprocessing approaches: original predictors, PCA, correlation filtering, and correlation filtering followed by PCA. Models were developed using 2019–2023 observations and evaluated on an internal test set and a separate 2024 validation dataset. Vegetation indices exhibited extensive correlations, whereas ILR balances showed less uniform redundancy and a more multidimensional structure. Across all preprocessing approaches, ILR models achieved higher internal-testing R² (0.91–0.93) and lower RMSE (6.13–6.72 bu ac⁻¹) than vegetation-index models (R² = 0.82–0.91; RMSE = 6.78–9.69 bu ac⁻¹). In 2024 validation, ILR achieved lower prediction errors under three of the four approaches. Correlation filtering followed by PCA produced the lowest ILR validation RMSE (5.51 bu ac⁻¹), approximately 23% below the lowest vegetation-index RMSE (7.15 bu ac⁻¹). Accumulated local effects linked model responses to red-edge/NIR–visible/SWIR contrasts and variation within the red-edge region. ILR balances offer a promising complementary representation for yield prediction, although their validation advantage depended on preprocessing. 

**Keywords**: compositional data analysis; isometric log-ratio; Sentinel-2; spring wheat; random forest; yield prediction; precision agriculture



<img width="4800" height="3000" alt="ILR_ELA_plot" src="https://github.com/user-attachments/assets/8c66378a-49ef-4d08-a844-7518de885b57" /> 

 **Figure 1**: Accumulated local effects (ALE) of eight ILR spectral balances on spring wheat yield predicted by the baseline random forest model.

 <img width="6000" height="3000" alt="corr_plot" src="https://github.com/user-attachments/assets/823b59c8-369a-479e-834a-052412ebba59" />   
 
**Figure 2**: Pairwise correlation structure of (A) conventional vegetation indices and (B) isometric log-ratio (ILR) spectral balances derived from Sentinel-2 imagery. Values represent Pearson correlation coefficients.


