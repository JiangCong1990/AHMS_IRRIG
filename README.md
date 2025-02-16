
The Atmospheric and Hydrological Modelling System (AHMS) is a fully coupled atmospheric and hydrological modelling system (Jiang et al., 2020; Xia, 2019; Xia et al., 2022). Specifically, AHMS couples the Weather Research and Forecasting (WRF) modelling system (Skamarock & Klemp, 2008) with the physically-based distributed regional Hydrological Model System HMS (Yu et al., 2006) through the Noah-Multiparameterziation Land Surface Model (Noah-MP; Chen & Dudhia, 2001; Niu et al., 2011). Furthermore, the module in WRF-Hydro (Gochis et al., 2013) is employed for downscaling and upscaling of variables between the grids of land surface model and hydrological model. 

AHMS can either be run online, i.e., coupled with the full WRF model for atmospheric dynamics, or offline – which is the situation adopted in the present study – by using prescribed near-surface atmospheric forcing variables. A schematic diagram identifying the main components of the online and offline AHMS simulations is displayed in Fig. 1. As shown in this figure, while the online AHMS can be employed to study the dynamic feedback between the atmosphere, surface and subsurface, the offline AHMS can be used to effectively calibrate and validate hydrological models.

![image](https://github.com/JiangCong1990/AHMS-IRRIG/assets/43998223/94239afa-3d6b-41da-9e2e-6d3e7c0aa725)
 
Figure 1: Simplified schematic of the online AHMS (frame with blue dot-dashed line) and offline AHMS (frame with red dashed line). Modified after Wagner et al. (2016b).



This study aims to develop an irrigation model that applies to arid and semi-arid regions, which is different from the previous work of Xia et al. (2022) combined the land surface hydrological model with the Global Crop Water Model (GCWM) to study hydrological processes in the water-rich areas of China. To this end, we extend AHMS to incorporate and modify a dynamic irrigation scheme (Xu et al., 2019) in Noah-MP, allowing us to quantify the dynamic irrigation water requirements of dryland crops based on the soil moisture deficit method. Furthermore, we incorporate the water uptake applicable to irrigation districts located in arid and semi-arid regions into the channel routing model and groundwater model of HMS. Specifically, we develop a channel routing model that considers long-distance water supply processes in irrigation areas characteristic of arid and semi-arid regions, such as those in the Yellow River Basin. Figure 2 displays a schematic diagram of the hydrological cycle represented in AHMS-IRRIG. 

 ![image](https://github.com/JiangCong1990/AHMS-IRRIG/assets/43998223/2229feda-91be-42e2-af5a-1ef4c359637a)

Figure 2: Sketch of the hydrologic cycle modelled in AHMS-IRRIG.


