This python code require some older version of python libraries


please install the below versions of the libraries before execution

keras==2.3.1
imutils==0.5.3
numpy==1.18.2
opencv-python==4.2.0.*
matplotlib==3.2.1
argparse==1.1
scipy==1.4.1
scikit-learn==0.23.1
pillow==7.2.0

When using Anaconda, we can install the needed version of python by creating a separate environment

$ conda create --name My_env python=3.7

to activate it,

$ conda activate My_env

after this install the needed version of all libraries in this environment. it will not affect the original version of the libraries.
eg:

$ conda install numpy 

#will install numpy in My_env not in base environment

$ conda deactivate # used to exit this environment after work

 
