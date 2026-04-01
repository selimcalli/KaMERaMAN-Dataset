# KaMERaMAN-Dataset
KAMERaMAN dataset includes karst sprig discharge dataset from the mountain regions surrounding Euro-Mediterranean region.

README: KaMERaMAN

General Information Dataset Title: Karst Mountains of Euro Mediterranean: Modeling, Analysis, and Network

Principal Investigator: Süleyman Selim Çallı

Affiliation: Ankara Üniversitesi, Department of Geological Engineering, Ankara, Türkiye

Contact Information: scalli@ankara.edu.tr

Date of Data Publication: 1 April 2026

DOI: 


1. License Information

This dataset is a compilation and harmonization of multiple public data sources.
This aggregate dataset is licensed under Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).

Reason for License Choice: This license was selected to comply with the restrictive requirements of the constituent data sourced from Austria (licensed under CC BY 4.0 NC), which prohibits commercial redistribution.

Usage Constraints: Users are free to share and adapt this material for non-commercial purposes, provided appropriate credit is given to the authors and the original data providers cited herein.

2. Data Sources & Citations

All raw data used to generate this dataset are publicly available. 
Detailed citations for each regional source (Alps, Atlas, Taurus, Zagros, etc.) are provided in the accompanying manuscript.

Original License Austria "ehyd.gv.at" / CC BY-NC 4.0 

All Other Regions Public Domain / CC BY 4.0 (or equivalent public license)

3. File Overview
Kameraman_metadata.csv: Contains site-specific information as below:

Region		Country	#	Spring Name/Station Name	Literature			Lat	Lon	Elev (m)	Recharge Area (km2)	Start Date	End Date	Resolution	Data Source	Data License	Contact For License
Alps		Austria		Aubachquelle			Cinkus et al. (2023)		47.36	10.172	1078		NA			1.1.1999	31.12.2022	Daily		ehyd.gv.at	CC BY NC 4.0	Simon Seelig, Jutta Eybl
		...		...

Apennines	Italy		Castelsantangelo		NA...	


Atlas		Algeria		Ain Youkous			Chemseddine et al. (2015)...
...



Hydrograph data: The hydrograph data folder includes 118 discharge time series which are named according to:

[3-digit Region code]_[ID Number 01-99]_[2-digit Country ISO code]@Spring name.csv

Each csv file includes metadata information as comment lines: (e.g. spring name / lat lon / start-end dates / available literature / license / contact person)

#-------------------------------------------------------
Examples: 

# Alps region (incl. 50 karst springs):
ALP_01_AT@Aubachquelle.csv
ALP_02_AT@Blaue_Quelle.csv
...
ALP_50_DE@Bergmannsquelle.csv

#-------------------------------------------------------
# Apennines (incl. 8 karst springs):
APE_01_IT@Castelsantangelo.csv
...
APE_08_IT@Bagnara.csv

#------------------------------------------------------
# Atlas (incl. 2 karst springs):
ATL_01_DZ@Ain Youkous.csv
ATL_02_MA@Ras El Ma.csv

#--------------------------------------------------------
# Balkans (incl. 4 karst springs):
BAL_01_BG@Yazo.csv
...
BAL_04_BG@Mugla.csv

#-------------------------------------------------------
# Betics (incl. 4 karst springs):
BET_01_ES@Cueva del Gato.csv
...
BET_04_ES@Natividad.csv

#--------------------------------------------------------
# Carpathians (incl. 8 karst springs):
CAR_01_SK@Dolna Lehote Vrabec 2.csv
...
CAR_08_CZ@Punkva_Skalní Mlýn.csv

#---------------------------------------------------------
# Dinarides (incl. 11 karst springs):
DIN_01_BA@Vrelo Bosne.csv
...
DIN_11_HR@Vrbica Ricice.csv

#---------------------------------------------------------
# Hellenides (incl. 3 karst springs):
HEL_01_GR@Almyros.csv
...
HEL_03_AL@Selita.csv

#---------------------------------------------------------
# Jura Mountains (incl 4 karst springs):
JUR_01_FR@Doubs.csv
...
JUR_04_FR@Verneau.csv

#---------------------------------------------------------
# Levant Mountains (incl 6 karst springs):
LEV_01_SY@Fageh.csv
...
LEV_06_LB@Qachqouch.csv

#---------------------------------------------------------
# Pyrenees (incl. 4 karst springs):
PYR_01_ES@Garces.csv
...
PYR_04_FR@Aliou.csv

#---------------------------------------------------------
# Taurus Mountains (incl. 6 karst springs):
TAU_01_TR@Kapuzbasi.csv
...
TAU_06_TR@Tacin.csv

#---------------------------------------------------------
# Zagros Mountains (incl 8 karst springs):
ZAG_01_IR@Barme-Jamal.csv
...
ZAG_08_IQ@Sarchawi Saraw.csv

#-----------------------------------------------------------



4. Data Processing & Harmonization

The data has been processed from various raw formats into a standardized, machine-readable structure suitable for hydrological modeling and machine learning applications (e.g., LSTM/CNN architectures).

Temporal Resolution: The majority of the dataset consisting of daily discharge data. In Atlas and Zagros regions, monthly data is also provided, where daily discharge data is scarce.

Unit Standardization: The discharge data are available in native format of the data provider (l/s and m3/s). 

Quality Control: Quality control is made by the regional experts (mentioned inside the manuscript). Gaps are not filled by artificial data.
		

5. Usage Notes

For those intending to use this data for academic research:
Please cite the primary Scientific Data paper associated with this DOI.

If your research focuses exclusively on a specific sub-region, we encourage you to also cite the original regional data provider listed in Section 2.

Non-Commercial Clause: Ensure your application of this data does not constitute commercial use, as per the CC BY-NC 4.0 agreement.


For further questions, please contact to Süleyman Selim Çallı: scalli@ankara.edu.tr

