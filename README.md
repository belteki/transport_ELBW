# Transport of extremely low birth infants on the first day of life

Jupyter Notebooks used for processing and analysis of clinical and ventilator parameters.


This repository contains the Python code used for data processing, statistical analysis and visualization described in the following paper:

**Stabilization, respiratory care and survival of extremely low birth weight infants transferred on the first day of life. Journal of Perinatology, in press**


Contact: gbelteki@aol.com; gusztav.belteki@nhs.net 

____


The outputs (numbers, tables, graphs) of the cells of the Jupyter Notebooks (.ipynb files) have been suppressed in order to comply with copyrights.
Some of the corresponding data and graphs can be found in the paper and its supplementary material.

This code can be viewed in any web browser. If the code is displayed (rendered) in Github, copy and paste the URL (web adress) of the Notebook into [nbviewer](https://nbviewer.jupyter.org) for a read-only display.

To run the code, you can use Jupyter installed locally on your computer or [Google Colab](https://colab.research.google.com).

Raw data are not shared but users can run the code on their own data obtained in the same format.

____

Packages required to run this Notebook: numpy, pandas, matplotlib, scipy. For versions of Python and the add-on packages see the Notebooks. 

I recommend downloading these packages using the freely availably Anaconda built: [https://anaconda.org](https://anaconda.org)

____

# Jupyter Notebooks


### 2. Initial processing of raw ventilator slow (0.5 Hz) data

Dictionaries containing the processed ventilation data exported as pickle archives: **data_pars_xxx_xxx.pickle** 
**xxx_vent_info.txt** text files containing the data about ventilator modes in the unedited recording are exported in the relevant DATA_DUMP subfolder.


1. [ventilator_data_1_150](ventilator_data_1_150.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **150 cases**
- 21 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **129 cases** remaining

Dictionary containing the processed ventilation data exported as pickle archive: **data_pars_1_150.pickle** 


2. [ventilator_data_151_300](ventilator_data_151_300.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **150 cases**
- 1 case (AL000257) was removed it was fragmented with multiple in data
- 32 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **117 cases** remaining

Dictionary containing the processed ventilation data exported as pickle archive: **data_pars_151_300.pickle** 


3. [ventilator_data_301_450](ventilator_data_301_450.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **150 cases**
-  19 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **131 cases** remaining

Dictionary containing the processed ventilation data exported as pickle archive: **data_pars_300_450.pickle**


4. [ventilator_data_451_600](ventilator_data_451_600.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **150 cases**
-  26 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **124 cases** remaining

Dictionary containing the processed ventilation data exported as pickle archive: **data_pars_451_600.pickle**


5. [ventilator_data_601_674](ventilator_data_601_674.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **74 cases**
-  7 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **67 cases** remaining

Dictionary containing the processed ventilation data exported as pickle archive: **data_pars_601_674.pickle**


6. [ventilator_data_601_750](ventilator_data_601_750.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **150 cases**
-  24 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **126 cases** remaining

Dictionary containing the processed ventilation data exported as pickle archive: **data_pars_601_750.pickle**


7. [ventilator_data_751_900](ventilator_data_751_900.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **150 cases**
-  28 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **122 cases** remaining

Dictionary containing the processed ventilation data exported as pickle archive: **data_pars_751_900.pickle**

8. [ventilator_data_901_1050](ventilator_data_901_1050.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **150 cases**
-  43 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **107 cases** remaining

Dictionary containing the processed ventilation data exported as pickle archive: **data_pars_901_1050.pickle**

9. [ventilator_data_1051_1100](ventilator_data_1051_1100.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **50 cases**
-  32 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **18 cases** remaining

Dictionary containing the processed ventilation data exported as pickle archive: **data_pars_1051_1100.pickle**

1. [ventilator_data_new_1_150](ventilator_data_new_1_150.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **146 cases**
-  19 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **127 cases** remaining


2. [ventilator_data_new_151_300](ventilator_data_new_151_300.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **150 cases**
-  24 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **126 cases** remaining


3. [ventilator_data_new_301_450](ventilator_data_new_301_450.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **150 cases**
-   33 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **117 cases** remaining


4. [ventilator_data_new_451_600](ventilator_data_new_451_600.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **150 cases**
-   14 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **136 cases** remaining


5. [ventilator_data_new_601_750](ventilator_data_new_601_750.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **150 cases**
-  22  cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **128 cases** remaining


6. [ventilator_data_new_751_900](ventilator_data_new_751_900.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **150 cases**
-   26 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **124 cases** remaining


6. [ventilator_data_new_901_1050](ventilator_data_new_901_1050.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **150 cases**
-  27  cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **123 cases** remaining


7. [ventilator_data_new_1051_1200](ventilator_data_new_1051_1200.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **150 cases**
-   34 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **116 cases** remaining


8. [ventilator_data_new_1201_1350](ventilator_data_new_1201_1350.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **149 cases**
-   32 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **117 cases** remaining

9. [ventilator_data_new_1351_1500](ventilator_data_new_1351_1500.ipynb): This notebook imports all ventilator data of these recordings (including ventilator parameters, settings, alarms (0.5Hz sampling rate) and waveform data (150Hz sampling rate).

- Total: **47 cases**
-   7 cases were removed as they were less than 15 minutes long (empty or partial recordings) 
- **40 cases** remaining




### 4. Processing clinical data


6. [clinical_data_1_1100](clinical_data_1_1100.ipynb)

- Total: **925 cases**
- Clinical data available in **850 cases**
- Only keep clinical data for cases where ventilation recordings (>15 minutes) are also available: **792 cases**

DataFrame containing the processed clinical data exported as **clin_df_1_1100.pickle** 


1. [clinical_data_new_1_1397](clinical_data_new_1_1397.ipynb)

- Total number of recordings: **1397**
- Ventilation recordings longer than 15 minutes: **1154 cases**
- Clinical data available in **1150 cases**
- Only keep clinical data for cases where ventilation recordings (>15 minutes) are also available: **1079 cases**

DataFrame containing the processed clinical data exported as **clin_df_new.pickle** 
Text files containing basic clinical data are also exported to the relevant DATA_DUMP subfolder as **xxx_clin_info.txt**


### 5. Processing of blood gases

5. [blood gases_1_1100](blood_gases_1_1100.ipynb)

- Total: **1100 cases**
- Clinical and appropriate ventilator data are available only for **792 cases**
- Blood cases not available in 55 cases; **737 cases remaining**

Dictionary containing the processed blood gas data exported as pickle archive: **blood_gases_1_1100.pickle**

1. [blood gases_new_1_1397](blood_gases_new_1_1397.ipynb)

- Total number of recordings: **1251**
- Ventilation recordings longer than 15 minutes: **1035 cases**
- Clinical data available in **1053 cases**
- Only keep clinical data for cases where ventilation recordings (>15 minutes) are also available: **987 cases**
- Blood gases available in **927 cases**

Dictionary containing the processed blood gas data exported as pickle archive: **blood_gases_new.pickle**




### 6. Further processing of slow (0.5Hz) ventilator data

##### From **AL000001-AL001100**: Clinical data and ventilator recordings (>15 minutes) are available for a total of: **242 + 217 + 220 + 104 = 783 cases**

6. [ventilator_data_processing_1_1100](ventilator_data_processing_1_1100.ipynb)

This Notebook performs all the actions done by the previous 5 Notebooks but contains updated code using later versions of the software.
In addition 'off' fields are not converted to np.nan because that has interfere with detecting periods when VG_state was 'off'.

1. [ventilator_data_processing_new_1_1305](ventilator_data_processing_new_1_1305.ipynb)

Imported: **data_pars_new_1_150.pickle**, **data_pars_new_151_300.pickle**, **data_pars_new_301_450.pickle**,
**data_pars_new_451_600.pickle**, **data_pars_new_601_750.pickle**, **data_pars_new_751_900.pickle**, **data_pars_new_901_1050.pickle**, **data_pars_new_1051_1200.pickle**, **data_pars_new_1201_1350.pickle**
**clin_df_new.pickle**

- Total number of recordings: **1305**
- Ventilation recordings longer than 15 minutes: **1076 cases**
- Clinical data available in **1082 cases**
- Only keep clinical data for cases where ventilation recordings (>15 minutes) are also available: **1015 cases**

Exported: dictionaries containing ventilation data as **data_pars_measurements_new_1_1305.pickle,  data_pars_settings_new_1_1305.pickle, data_pars_alarms_new_1_1305.pickle**

Reports and graphs are also generated about ventilator data before any manual trimming:
- Table about ventilator modes (exported as Excel file)

**ventilation_modes_unedited_new_1_1305.xlsx**, **ventilation_modes_unedited_new_1_1305.pickle**

- Individual time series graphs graphs about
    - MV_kg (if recording contains mechanical ventilation)
    - MAP
    - ventilator modes used.
 
  
 
### 7. Manual trimming of the recordings



### 9. Further processing of recordings with mechanical ventilation


1. [ventilator_data_processing_1_300_ventilated](ventilator_data_processing_1_300_ventilated.ipynb)

This notebook ventilator data to keep only periods of mechanical ventilation. Recordings have also been inspected and trimmed _manually_ to remove periods when the ventilator was working but the patient was not connected.

Imported: **data_pars_measurements_1_300.pickle,  data_pars_settings_1_300.pickle, data_pars_alarms_1_300.pickle**, **clin_df_1_300.pickle**

- Total: **242 cases**
- Containing >15 minutes of mechanical ventilation: **146 cases remaining**
- After removing periods when the patient was not connected, containing >15 minutes of mechanical ventilation: **145 cases**

Exported: 
**data_pars_measurements_ventilated_1_300.pickle,  data_pars_settings_ventilated_1_300.pickle, data_pars_alarms_ventilated_1_300.pickle, 
vent_modes_1_300.pickle, vent_modes_ventilated_1_300.pickle, 
ventilation_modes_1_300.xlxs, ventilation_modes_ventilated_1_300.xlsx**


2. [ventilator_data_processing_301_600_ventilated](ventilator_data_processing_301_600_ventilated.ipynb)

This notebook ventilator data to keep only periods of mechanical ventilation. Recordings have also been inspected and trimmed _manually_ to remove periods when the ventilator was working but the patient was not connected.

Imported: **data_pars_measurements_301_600.pickle,  data_pars_settings_301_600.pickle, data_pars_alarms_301_600.pickle**, **clin_df_301_600_pickle**

- Total: **217 cases**
- Containing >15 minutes of mechanical ventilation: **114 cases**
- **8 cases** removed as there was no flow sensor used (and hence no tidal volume measurement), **106 cases remaining**
- After removing periods when the patient was not connected, containing >15 minutes of mechanical ventilation: **106 cases**

Exported: **data_pars_measurements_ventilated_301_600.pickle,  data_pars_settings_ventilated_301_600.pickle, data_pars_alarms_ventilated_301_600.pickle, vent_modes_301_600.pickle, vent_modes_ventilated_301_600.pickle, 
ventilation_modes_301_600.xlxs, ventilation_modes_ventilated_301_600.xlsx**


3. [ventilator_data_processing_601_665_ventilated](ventilator_data_processing_601_665_ventilated.ipynb)

This notebook ventilator data to keep only periods of mechanical ventilation. Recordings have also been inspected and trimmed _manually_ to remove periods when the ventilator was working but the patient was not connected.

Imported: **data_pars_measurements_601_665.pickle,  data_pars_settings_601_665.pickle, data_pars_alarms_601_665.pickle**, **clin_df_1_665_pickle**

- Total: **52 cases**
- Containing >15 minutes of mechanical ventilation: **22 cases**
- **1 case** removed as there was no flow sensor used (and hence no tidal volume measurement), **21 cases remaining**
- After removing periods when the patient was not connected, containing >15 minutes of mechanical ventilation: **21 cases**

Exported: **data_pars_measurements_ventilated_601_665.pickle,  data_pars_settings_ventilated_601_665.pickle, data_pars_alarms_ventilated_601_665.pickle, vent_modes_601_665.pickle, vent_modes_ventilated_601_665.pickle, 
ventilation_modes_601_665.xlxs, ventilation_modes_ventilated_601_665.xlsx**


4. [ventilator_data_processing_601_900_ventilated](ventilator_data_processing_601_900_ventilated.ipynb)

This notebook ventilator data to keep only periods of mechanical ventilation. Recordings have also been inspected and trimmed _manually_ to remove periods when the ventilator was working but the patient was not connected.

Imported: **data_pars_measurements_601_900.pickle,  data_pars_settings_601_900.pickle, data_pars_alarms_601_900.pickle**, **clin_df_601_900_pickle**

- Total: **220 cases**
- Containing >15 minutes of mechanical ventilation: **94 cases**
- **2 cases** removed as there was no flow sensor used (and hence no tidal volume measurement), **92 cases remaining**
- After removing periods when the patient was not connected, containing >15 minutes of mechanical ventilation: **91 cases**

Exported: **data_pars_measurements_ventilated_601_900.pickle,  data_pars_settings_ventilated_601_900.pickle, data_pars_alarms_ventilated_601_900.pickle, vent_modes_601_900.pickle, vent_modes_ventilated_601_900.pickle, 
ventilation_modes_601_900.xlxs, ventilation_modes_ventilated_601_900.xlsx**


5. [ventilator_data_processing_901_1100_ventilated](ventilator_data_processing_901_1100_ventilated.ipynb)

This notebook ventilator data to keep only periods of mechanical ventilation. Recordings have also been inspected and trimmed _manually_ to remove periods when the ventilator was working but the patient was not connected.

Imported: **data_pars_measurements_901_1100.pickle,  data_pars_settings_901_1100.pickle, data_pars_alarms_901_1100.pickle**, **clin_df_901_1100_pickle**

- Total: **104 cases**
- Containing >15 minutes of mechanical ventilation: **50 cases**
- **3 cases** removed as there was no flow sensor used (and hence no tidal volume measurement), **47 cases remaining**
- After removing periods when the patient was not connected, containing >15 minutes of mechanical ventilation: **46 cases**

Exported: **data_pars_measurements_ventilated_901_1100.pickle,  data_pars_settings_ventilated_901_1100.pickle, data_pars_alarms_ventilated_901_1100.pickle, vent_modes_901_1100.pickle, vent_modes_ventilated_901_1100.pickle, 
ventilation_modes_901_1100.xlxs, ventilation_modes_ventilated_901_1100.xlsx**


##### Ventilated cases: from **AL000001-AL001100**: Clinical data and ventilator recordings (>15 minutes) are available for a total of: **145  + 106 + 91 + 46  = 388  cases**

6. [ventilator_data_processing_1_1100_ventilated](ventilator_data_processing_1_1100_ventilated.ipynb)
   This Notebook performs all the actions done by the previous 5 Notebooks but contains updated code using later versions of the software.

In this notebook recordings are inspected and trimmed _manually_ to remove periods when the ventilator was working but the patient was probably not connected (based on inspection of pressure and tidal volume curves.

1. [ventilator_data_trimming_new_1_1305](ventilator_data_trimming_new_1_1305.ipynb)

Imported: **data_pars_measurements_new_1_1305.pickle,  data_pars_settings_new_1_1305.pickle, data_pars_alarms_new_1_1305.pickle**, **clin_df_new.pickle**

- Total: ** cases** with more than 15 minutes of ventilator data and avaialable clinical data (before trimming)

Exported: 
**data_pars_measurements_trimmed_new_1_1305.pickle,  data_pars_settings_trimmed_new_1_1305.pickle, data_pars_alarms_trimmed_new_1_1305.pickle, 
vent_modes_trimmed_new_1_1305.pickle, ventilation_modes_trimmed_new_1_1305.xlxs**, 




### 2. Disease specific ventilator data analysis

**A. ELBW (<1000 g birth wieight) infants transferred during the first 24 hours of their life.**

Consider recordings `AL000001 - AL001100` and `AT000001 - AT000818`.

1. [ELBW_analysis_ventilation](ELBW_analysis_ventilation.ipynb): Analysis of ventilator data of ELBW infants (born with <1000 g birth weight) who were transferred ventilated ex utero in the first 24 hours of life.

2. [ELBW_analysis_clinical](ELBW_analysis_clinical.ipynb): Analysis of manually collected clinical data for the above group, in relation to to the respiratory care of the patients.
