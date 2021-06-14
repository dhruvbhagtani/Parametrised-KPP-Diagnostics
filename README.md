# Parametrised-KPP-Diagnostics
Tests for checking whether parametrised KPP mixing layer is in agreement with the control run.

List of notebooks (in alphabetical order) and their functions:
* a60_KPP_Param.ipynb: Compares the control and two parametrised KPP runs, where the ustar^2 coefficient are respectively 80 and 60, i.e., a = 80 and a = 60, keeping other parameters constant.
* Bulk_Rc_Diags.ipynb: Profiles of velocity shear and buoyancy. An initial analysis of Richardson number for different regions after identifying that it is the resolved velocity shear that is causing errors in KPP mixing layer.
* Corr_data.ipynb: Defined parameters for approximating resolved velocity shear, and outputted data in the form of .csv files for further comparisons and correlations.
* Creating_database.ipynb: Created a database with the name 'cc_database_nostress_cont_param_kpp.db'. This database consists of two runs - control and parametrised KPP.
* Param_Bulk_Rc.ipynb:
* Param_KPP_Comparison.ipynb: Compares the control and parametrised KPP run, where the ustar^2 coefficient is 80, i.e., a = 80.
* Param_KPP_diff.ipynb:
* Revsd_exp.ipynb: Compares the control, a = 80 parametrisation and the modified exponential function. The notebook concludes that this modified exponential function corrects a lot of deviations that existed in a = 80 run.
* Revsd_exp2.ipynb: Compares the control and the modified exponential function for 10 years.
* Vel_shear_diagnostics.ipynb:
* Year_1900_diff.ipynb: Comparisons between the control and parametrised KPP in terms of KPP mixing layer, surface temperature and salinity, freshwater fluxes and surface heat fluxes. This is only for the first year (Year 1900).
* Year_1970s.ipynb: Compares the control and corrected parametrisation in terms of circulation metrics, tracers like KE, PE after 75 years. 
