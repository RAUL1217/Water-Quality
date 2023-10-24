# Water-Quality

## About Dataset

### Context
Access to safe drinking-water is essential to health, a basic human right and a component of effective policy for health protection. This is important as a health and development issue at a national, regional and local level. In some regions, it has been shown that investments in water supply and sanitation can yield a net economic benefit, since the reductions in adverse health effects and health care costs outweigh the costs of undertaking the interventions.

### Content
The water_potability.csv file contains water quality metrics for 3276 different water bodies.

### 1. pH value:
PH is an important parameter in evaluating the acid–base balance of water. It is also the indicator of acidic or alkaline condition of water status. WHO has recommended maximum permissible limit of pH from 6.5 to 8.5. The current investigation ranges were 6.52–6.83 which are in the range of WHO standards.

### 2. Hardness:
Hardness is mainly caused by calcium and magnesium salts. These salts are dissolved from geologic deposits through which water travels. The length of time water is in contact with hardness producing material helps determine how much hardness there is in raw water. Hardness was originally defined as the capacity of water to precipitate soap caused by Calcium and Magnesium.

### 3. Solids (Total dissolved solids - TDS):
Water has the ability to dissolve a wide range of inorganic and some organic minerals or salts such as potassium, calcium, sodium, bicarbonates, chlorides, magnesium, sulfates etc. These minerals produced un-wanted taste and diluted color in appearance of water. This is the important parameter for the use of water. The water with high TDS value indicates that water is highly mineralized. Desirable limit for TDS is 500 mg/l and maximum limit is 1000 mg/l which prescribed for drinking purpose.

### 4. Chloramines:
Chlorine and chloramine are the major disinfectants used in public water systems. Chloramines are most commonly formed when ammonia is added to chlorine to treat drinking water. Chlorine levels up to 4 milligrams per liter (mg/L or 4 parts per million (ppm)) are considered safe in drinking water.

### 5. Sulfate:
Sulfates are naturally occurring substances that are found in minerals, soil, and rocks. They are present in ambient air, groundwater, plants, and food. The principal commercial use of sulfate is in the chemical industry. Sulfate concentration in seawater is about 2,700 milligrams per liter (mg/L). It ranges from 3 to 30 mg/L in most freshwater supplies, although much higher concentrations (1000 mg/L) are found in some geographic locations.

### 6. Conductivity:
Pure water is not a good conductor of electric current rather’s a good insulator. Increase in ions concentration enhances the electrical conductivity of water. Generally, the amount of dissolved solids in water determines the electrical conductivity. Electrical conductivity (EC) actually measures the ionic process of a solution that enables it to transmit current. According to WHO standards, EC value should not exceeded 400 μS/cm.

### 7. Organic_carbon:
Total Organic Carbon (TOC) in source waters comes from decaying natural organic matter (NOM) as well as synthetic sources. TOC is a measure of the total amount of carbon in organic compounds in pure water. According to US EPA < 2 mg/L as TOC in treated / drinking water, and < 4 mg/Lit in source water which is use for treatment.

### 8. Trihalomethanes:
THMs are chemicals which may be found in water treated with chlorine. The concentration of THMs in drinking water varies according to the level of organic material in the water, the amount of chlorine required to treat the water, and the temperature of the water that is being treated. THM levels up to 80 ppm is considered safe in drinking water.

### 9. Turbidity:
The turbidity of water depends on the quantity of solid matter present in the suspended state. It is a measure of light emitting properties of water and the test is used to indicate the quality of waste discharge with respect to colloidal matter. The mean turbidity value obtained for Wondo Genet Campus (0.98 NTU) is lower than the WHO recommended value of 5.00 NTU.

### 10. Potability:
Indicates if water is safe for human consumption where 1 means Potable and 0 means Not potable.

## Solution:
* Data Collection and Understanding
* EDA
* Data Cleaning
* Preprocessing
* Feature Engineering
* Applying the model

# EDA
### Pairplot
![Screenshot 2023-10-24 202648](https://github.com/RAUL1217/Water-Quality-Prediction-Analysis/assets/142076300/3cf2377c-f0cb-483d-bd71-5d15696ce780) 

### Heatmap
![Screenshot 2023-10-24 202714](https://github.com/RAUL1217/Water-Quality-Prediction-Analysis/assets/142076300/7acb2f96-6bb3-44b4-acd5-02e45a1ee5c8)

### Countplot
* Potability
![Screenshot 2023-10-24 203106](https://github.com/RAUL1217/Water-Quality-Prediction-Analysis/assets/142076300/3d953c53-e553-4a44-ad8d-0979c0e15b6d)

### Distplot
* ph
![image](https://github.com/RAUL1217/Water-Quality-Prediction-Analysis/assets/142076300/8365c110-4657-46ff-96b6-22c02cf79aa1)

* Hardness
![image](https://github.com/RAUL1217/Water-Quality-Prediction-Analysis/assets/142076300/b187c32c-9f43-4109-b7ba-ab8c71e3c2c7)

* Solids
![image](https://github.com/RAUL1217/Water-Quality-Prediction-Analysis/assets/142076300/74931372-c791-4f92-909d-fe5b43106a1b)

* Chloramines
![image](https://github.com/RAUL1217/Water-Quality-Prediction-Analysis/assets/142076300/70d34e22-abac-4302-83fb-0c4bf971a8a9)

* Sulfate
![image](https://github.com/RAUL1217/Water-Quality-Prediction-Analysis/assets/142076300/f097801a-c7be-4d2b-9c54-4e129a71148f)

* Conductivity
![image](https://github.com/RAUL1217/Water-Quality-Prediction-Analysis/assets/142076300/f48a1082-4abc-47ac-9664-6fcc11ef186d)

* Organic_carbon
![image](https://github.com/RAUL1217/Water-Quality-Prediction-Analysis/assets/142076300/e6000f9e-58a2-4a44-a42d-b3f1060e9191)

* Trihalomethanes
![image](https://github.com/RAUL1217/Water-Quality-Prediction-Analysis/assets/142076300/c3b1cc60-5f4b-4cb0-a25d-397cafac94a6)

* Turbidity
![image](https://github.com/RAUL1217/Water-Quality-Prediction-Analysis/assets/142076300/ae8925f8-0912-44de-ab60-f5daf7e7ecf4)
