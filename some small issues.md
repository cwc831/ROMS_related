# Something has to be noticed
- [Common issues for all versions](#common-issues-for-all-versions)
- [ROMS32 version with bio module modification](#roms32-version-with-bio-module-modification)

## Common issues for all versions
* note the reference time in all input *.nc file and in the *.in file  

* varinfo.dat ( do not confuse the different versions)
  
## ROMS32 version with bio module modification
* must define the diagnostic output
  
* 'NDIA' in *.in file must be a nonzero value error  
  >   forrtl: severe (71): integer divide by zero

* 'RIVER_OM' : if you cannot undef this mode
  >   ROMS/Unility/inp_par.F: 3764 lost ifdef RIVER_OM




