# pyCGM

This is a work in progress document.  

Read about this code and if you find it useful in your work please cite:

The effect of subject measurement error on joint kinematics in the conventional gait model: Insights from the open-source pyCGM tool using high performance computing methods
http://journals.plos.org/plosone/article/comments?id=10.1371/journal.pone.0189984

Bibtex:
@article{schwartz2018effect,
  title={The effect of subject measurement error on joint kinematics in the conventional gait model: Insights from the open-source pyCGM tool using high performance computing methods},
  author={Schwartz, Mathew and Dixon, Philippe C},
  journal={PloS one},
  volume={13},
  number={1},
  pages={e0189984},
  year={2018},
  publisher={Public Library of Science}
}


Python Module for the Conventional Gait Model, calculates kinematics.

This is a python module for calculating conventional gait model.  It can read a .c3d file (thanks to https://pypi.python.org/pypi/c3d/0.2.1)  or .csv file generated from Vicon Nexus under the Export ASCII settings.  It is validated against Nexus 1.8, and file types are known from Nexus 1.8.  Newer C3D files may not work. 

The goal of this project is to release an easy to understand conventional gait model that users can implement in their own projects via a single python file.  We have included a runpycgm.py file to demonstrate how the pycgm file can be called. 

Our aim is to provide researchers and students a tool that can aid in understanding and developing modifications to the conventional gait model through python without much more. 

Requirements:
Python 2.7, Numpy, C3D

Requirements for HPC:
Python 2.7, Numpy, C3D, MPI, Preferably Linux (MPI is not as simple to setup on windows)

Uses:

See runpycgm.py

Credits:

Developed in the Digital Human Research Center http://dhrc.snu.ac.kr at the 

Advanced Institutes of Convergence Technology (AICT) http://aict.snu.ac.kr

Project Lead: Mathew Schwartz (umcadop at gmail) For issues, use github or email me directly

Contributors: Philippe C. Dixon,  Seungeun Yeon (연승은),Filipe Alves Caixeta, Robert Van-Wesep
