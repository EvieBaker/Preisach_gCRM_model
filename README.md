# Preisach_gCRM_model
A model of gCRM acquisition using Preisach theory for synthetic Preisach distributions written in Python 

The following files contain the functions needed for the model to run:
general.py, plots.py and BF_arai_AF_HT.py

Different main files are used for room temperature TRM and CRM acquisition (Arai.main.py), CRM and TRM acquisition for the 3D angle case (Arai_main_a.py), this also requires the use of angles.py instead of BF_arai_AF_HT.py), for high temperature CRM and TCRM acquisition the file TCRM_Arai_main.py needs to be ran. 

Within each main file, the variable of interest to be changed can be selected 

file file plots.py is used to make the plots (e.g. Arai plots) using the output files from the model
