Local gyrification index (LGI) - provided by FREESURFER (https://surfer.nmr.mgh.harvard.edu/fswiki/LGI)

First, have to set path at MATLAB (LGI performed on MATLAB codes)

Then, perform the following steps on the recon-all performed data.

1. load FREESURFER
$> export FREESURFER_HOME=/usr/local/freesurfer
$> source $FREESURFER_HOME/SetUpFreeSurfer.sh

2. Set subject directory
$> export SUBJECTS_DIR=<path to subject data>

3. change the MATLAB path (can be performed at any step)
PATH=/Applications/MATLAB_R2017b.app/bin:$PATH

4. run LGI
recon-all -s <subj> -localGI
