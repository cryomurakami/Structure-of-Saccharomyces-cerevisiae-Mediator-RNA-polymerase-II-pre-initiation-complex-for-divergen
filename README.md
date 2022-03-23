# Structure-of-Saccharomyces-cerevisiae-Mediator-RNA-polymerase-II-pre-initiation-complex-for-divergent-transcription

Integrative Modeling for the Mediator Tail Module Dimer bound to UAS DNA and Activator

In this GitHub repository folder you will find two main directories:
-	modeling
-	analysis

In the modeling folder, all materials necessary to model the system using IMP version 2.13.0 are included. A breakdown of the files follows:
-	data:
o	topology file
o	FASTA sequence files
o	PDB structure files
o	crosslink dataset csv file
-	modeling script:
o	modeling_xls.py

In the analysis folder, scripts to perform analysis are included as are results from the analysis of 10 independent modeling runs. Specifically, the following are included:
-	scripts:
o	three scripts used to submit and analyze the datasets on our high-performance computation cluster using SLURM
-	statistics (results from using imp_sampcon on the modeling datasets):
o	structural cluster populations, precision estimates
o	score convergence, sampling precision stats
o	chi square, Kolmogodorov-Smirnov statistical test results
-	file used to specify regions to focus analysis (density_ranges.txt)
-	three structural clusters described by analysis (majority cluster being cluster.0)
o	mrc volume files output from analysis of individual regions in the system
o	a multiscale representation cluster_center_model.rmf3 file
o	a script for visualization of the system by ChimeraX (cluster_assessment.cxc)

if you have any questions, please contact Jose Gorbea or Kenji Murakami at:
    
    gorbea@pennmendicine.upenn.edu
    kenjim@pennmedicine.upenn.edu
    
Best regards,

Jose
