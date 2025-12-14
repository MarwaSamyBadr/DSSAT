DSSAT
1. Create Weather File for DSSAT
DSSATweatherFile.ipyn generates a .WTH weather file that is used for DSSAT simulations.
Requirements:
- Python ≥ 3.0.0
- Excel file (.xlsx) containing the following columns:
['DATE', 'TMIN', 'TMAX', 'WIND', 'RAIN', 'SRAD']
Units:
Temperature in °C
WIND in m/s
RAIN in mm
SRAD: Net downward solar radiation in J/m²

3. Create Soil File for DSSAT
DSSATsoilFile.ipyn generates a .SOL soil data file that is used for DSSAT simulations.
Requirements:
- Python ≥ 3.0.0
- Excel file (.xlsx) containing soil data. Example: sharqiaSoil.xlsx
Note: Descriptions of variables in the soil file can be found in the SOIL.CDE file, which can be opened with a text editor (e.g., Notepad).
