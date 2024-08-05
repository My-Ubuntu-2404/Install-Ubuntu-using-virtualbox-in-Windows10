# Main page
## MotionDiffuse: Text-Driven Human Motion Generation with Diffusion Model
https://mingyuan-zhang.github.io/projects/MotionDiffuse.html


# GITHUB Repo URL: 
https://github.com/mingyuan-zhang/MotionDiffuse

#############################################
####### COMMANDS to run on Linux Ubuntu 24.04
#############################################
a. >>> Install new environment: motiondiffuse_v5a 

└─$ conda create -n motiondiffuse_v5a  python=3.7 -y

└─$ conda activate motiondiffuse_v5a 

└─$ conda install pytorch=1.9.1 torchvision cudatoolkit=10.1 -c pytorch

└─$ conda install -c conda-forge gcc

└─$ pip install mmcv==2.2.0 -f https://download.openmmlab.com/mmcv/dist/cu101/torch1.9/index.html

>>> lanuch anaconda navigator app

└─$ cd /root/anaconda3/bin

└─$ source activate root 

└─$ anaconda-navigator 

└─$ pip install matplotlib==3.3.1

└─$ pip install tqdm

└─$ pip install git+https://github.com/openai/CLIP.git

└─$ pip install scipy


motiondiffuse_v5a_revision1
