# Preisach_gCRM_model

This repository contains a Preisach-based (grain-growth chemical remanent magnetisation) gCRM model for modeling gCRM acquisition and the Thellier protocol on gCRMs and TRMs in synthetic Preisach distributions. The model is written in Python.

The following files contain the functions needed for the model to run:
general.py, plots.py and BF_arai_AF_HT.py

Different main files are used for room temperature TRM and gCRM acquisition, and the Thellier protocol on the TRM and gCRMs (Arai.main.py), gCRM and TRM acquisition for the 3D variable angle case (Arai_main_a.py), this also requires the use of angles.py instead of BF_arai_AF_HT.py, for high temperature CRM and TCRM acquisition the file TCRM_Arai_main.py needs to be ran. 

Within each main file, the variable of interest to be changed can be chosen along with the chosen values to test

The file plots.py is used to make the plots (e.g. Arai plots) using the output files from the model
