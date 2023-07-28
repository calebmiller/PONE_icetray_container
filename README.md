# PONE_icetray_container
"temporary" container and icetray launcher for pone analyzes

================================================================

github contains .def file used to create .sif file and icetray enviroment script.

.sif available at: https://www.dropbox.com/s/22dgatvjtywijc2/ptray.sif?dl=0

================================================================

Instructions for use on cedar (may vary cluster to cluster):
```
$ module load apptainer
$ apptainer shell ptray.sif
> ./myenv.sh
```
this should load the icetray enviroment and allow for ipython-esque testing, dataio-shovel, and analyzes scripts to run
