# BOSSstars
Work with stellar data from the BOSS XDQSO selection

The columns in the XDQSO_data_full.txt dataset are *objid*, *galactic latitude (rad)*, *galactic longitude (rad)*, *line of sight velocity (km/s)*, *psfMag_r*, *psfMag_i*, *psfMag_g*, *ext_r*, *ext_i*, *ext_g*, and *chunk number*.

Only stellar data from the observation with the best spectrum (scienceprimary = 1) are used and we have restricted to stars with |b| > 30 deg.

All the data values are from the BOSS dr12 dataset, but they've been matched to objects identified as stars that were targeted / would have been targeted as quasars using the XDQSO algorithm (data from http://data.sdss3.org/sas/dr8/groups/boss/photoObj/xdqso/xdcore/) that selected for a uniform distribution for quasars.

