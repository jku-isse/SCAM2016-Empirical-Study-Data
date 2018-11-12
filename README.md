# SCAM2016-Empirical-Study-Data


This is the data we extracted for our empirical study on structural feature interactions.
The study systems, with their respective sources, are listed below.

System Locations:
ArgoUML - http://argouml-spl.tigris.org/
AXTLS - http://axtls.sourceforge.net//
BUSYBOX - http://www.busybox.net/
LINUX - https://www.kernel.org/
OPENSSL - https://www.openssl.org/
UCLIBC - http://www.uclibc.org/
VOD - http://peace.snu.ac.kr/dhkim/java/MPEG/ - AND - http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6030060&tag=1


For each of the study systems there exists a directory with the calculated data in it.
We list the data-files below and briefly describe their contents.

Files:
#A.csv - number of Artifacts
#Ad.csv - number of Artifacts per depth level in tree
#Ado.csv - number of Artifacts per depth level in tree and order of modules
#Ao.csv - number of Artifacts per order of modules
#deadA.csv - number of dead Artifacts (in annotations that are always false)
#F.csv - number of Features
#M.csv - number of Modules
#MAC.csv - Afferent Coupling of Modules 
#MACa.csv - Afferent Coupling of a Module 
#MACo.csv - Afferent Coupling of Modules per order 
#MEC.csv - Efferent Coupling of Modules 
#MECa.csv - Efferent Coupling of a Module 
#MECo.csv - Efferent Coupling of Modules per order 
#MFMoCSV.csv - number of Modules per order in the variability model
#Mo.csv - number of Modules per order
#moduleCohesion.csv - Cohesion of Modules 
#moduleCohesionA.csv - Cohesion of a Module 
#moduleCohesionPerOrder.csv - Cohesion of Modules per order 
artifactCount.txt - number of Artifacts in an association
assocs.txt - associations and their modules
cohesion.txt - Cohesion on specified depth levels
coupling.txt - Afferent Coupling on specified depth levels
dependencies.txt - Dependencies between associations
effCoupling.txt - Efferent Coupling on specified depth levels
evaluation.txt - Status outputs during the experiment
exist.txt - list of modules found in source code
granularity.txt - granularity levels of code fragments in associations
notExist.txt - number of Modules not found in source code annotations per order
notInVariabilityModel.csv - number of Modules found in source code annotations, but not in variability model
notInVariabilityModelA.csv - number of Artifacts implementing Modules from notInVariabilityModel.csv
scattering.txt - Scattering of Modules of an Association, in different depth levels
sub.txt - Number of Direct Subset Modules of a Module, in respect to the maximum number of Direct Subset Modules
super.txt - Number of Direct Superset Modules of a Module, in respect to the number of Direct Superset Modules according to the variability model
tangling.txt - Tangling of Modules in Artifacts of specified depth levels


Furthermore we provide the variability models in form of "dimacs" files, and the presence conditions for source code files in "txt" files. 

For ArgoUML and VOD we do not have "dimacs" files of their variability models, for these two systems we represented the possible modules using their possible variants.
Therefore we provide the list of variants (=configurations) in "configs" files.



