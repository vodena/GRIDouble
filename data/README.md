Datasets provided are used to train ML models for forecasting electricity production on hourly basis.

Data_Cacak.csv file is a csv containing data from an existing industrial facilities in Cacak, Serbia. Data has been masked for anonymisation purposes by aggregating the 15-minute recordings into hourly values. Temporal range is Nov 2022 - Nov 2023 at hourly basis. 

The CSV file encompasses several key elements, detailed as follows:
Datetime - Date and Time(local)

AirTemperature - The air temperature in degrees Celsius (°C).

CloudOpacity - The amount of cloud cover in the sky expressed as a percentage (%). Higher cloud opacity values mean more cloud cover, which reduces the amount of sunlight reaching the solar panels. Lower values indicate clearer skies with more direct sunlight.

DHI - Diffuse Horizontal Irradiance (DHI) is the solar radiation received on a horizontal surface from the entire sky. It includes both direct and scattered sunlight. It is measured in kilowatts per square meter (kW/m²).

DNI - Direct Normal Irradiance (DNI) represents the solar radiation received directly from the sun on a surface perpendicular to the sun's rays. It is measured in kilowatts per square meter (kW/m²).

EBH - Extraterrestrial Horizontal Irradiance (EBH) is the amount of solar radiation that would be received at the Earth's surface if there were no atmosphere. It is measured in kilowatts per square meter (kW/m²).

GHI - Global Horizontal Irradiance (GHI) is the total solar radiation received on a horizontal surface, including both direct and diffuse components. It is measured in kilowatts per square meter (kW/m²).

Production – Location 1 - This variable represents the electricity production from solar panels at Location 1 in kilowatt-hours (kWh). It is provided as an hourly average, indicating the amount of electricity generated during each hour.

Production - Location 2 - This variable represents the electricity production from solar panels at Location 2 in kilowatt-hours (kWh). It is provided as an hourly average, indicating the amount of electricity generated during each hour.

Production - Location 3 - This variable represents the electricity production from solar panels at Location 3 in kilowatt-hours (kWh). It is provided as an hourly average, indicating the amount of electricity generated during each hour.

Source
Meteorological data has been retrieved from the Solcast platform, and the production data was collected from the measuring equipment installed at the user's locations.

License
Creative Commons Attribution 4.0 International License
