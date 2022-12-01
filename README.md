# WRF_HRLDAS
A tool for driving hrldas with wrfout file for higher resolution simulations.
## create_forcing.exe
A modified version of create_forcing.exe was provided to deal with wrfout-based files.  
## WRF2HRLDAS.R
Program to read and convert wrfout files to create_forcing.exe  
## namelist example  
In order to use this program, wrf should be configured with lat-lon projections, so an example was provided for wps. Besides, user should enable PREC_ACC_NC and PREC_ACC_C in wrf namelist.input by adding *prec_acc_dt = 60,* for each domain.
