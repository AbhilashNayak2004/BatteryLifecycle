# BatteryLifecycle
Machine learning program for determining the lifecycle of battery using regression model
Although i also give access information in Python, the analysis was first carried out in MATLAB. This data is kept as a struct in MATLAB files (.mat). This information is kept in nested dictionaries in the python files (.pkl).

I advised creating a fresh Python environment with packages that matched the requirements.txt file in order to run the Python code. Conda may be used to do this. the command to produce the file requirements.txt.

Each battery's (cell's) data can be divided into one of three categories: descriptors, summaries, and cycles.

(1) Each battery is described by its charging procedure, cycle life, barcode, and channel. Be aware that the pkl files do not presently contain barcode or channel information.

(2) Information on a per-cycle basis is included in the summary statistics, including cycle number, discharge capacity, charge capacity, internal resistance, maximum temperature, average temperature, lowest temperature, and charge time.

(3) Data about a cycle, such as time, charge capacity, current, voltage, temperature, and discharge capacity, are referred to as cycle data. We also provide the generated vectors for the discharge parameters dQ/dV, Qdlin for the linear interpolation of the discharge capacity, and Tdlin for the linear interpolation of the temperature.

The LoadData files demonstrate how to load the data and which cells were examined in the study.

