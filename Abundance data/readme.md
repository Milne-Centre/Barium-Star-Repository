This is the repository of abundance data for stars. 

A master list of all stars contained in the database will be added in the future. Currently 10 objects are provided as an example. These are:
BD-083194
BD-094337
BD-142678
CD-272233
CD-298822
CD-308774
CD-38585
CD-422048
CD-538144
CD-611941


The data for these has been taken from De Castro et al. (2016), MNRAS, 459, 4299.


Instructions for adding data:
Each star should be entered as its own datafile, with a filename "<Object ID>.dat". Please check if the object already exists -- if it does add a suffix of "_n" where n is the current number of files for that object +1. The first row of the file should begin with "#" and give a bibliographic reference for where the data comes from. Each entry should be supplied on a separate row, with error bars if possible. Make sure you minimally supply the stellar parameters log g, T_eff and [Fe/H], as well as the abundance data.