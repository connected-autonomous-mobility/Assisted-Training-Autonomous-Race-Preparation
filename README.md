# Assisted-Training-Autonomous-Race-Preparation
sample code for rC3 workshop, Dec 29th, 2020

## 1 Environment
```
(conda create --name sds7 --clone sds6)

conda env create -f install/envs/ubuntu.yml
conda activate donkey
```


## 2 Software
### 2.1 [Donkey: donkeycar](https://github.com/tawnkramer/gym-donkeycar)
```
updating version donkey v3.1.5
Usage: The available commands are:
['createcar', 'findcar', 'calibrate', 'tubclean', 'tubhist', 'tubplot', 'tubcheck', 'tubaugment', 'makemovie', 'createjs', 'consync', 'contrain', 'cnnactivations', 'update']


cd /home/rainer/dev/41-VirtualRacingRepos/donkeycar-sds6
source activate sds7
git checkout master
git pull
pip install -e .

```
### 2.2 [Gym: gym-donkeycar](https://github.com/Ottawa-Autonomous-Vehicle-Group/gym-donkeycar-pln)
```
cd /home/rainer/dev/41-VirtualRacingRepos/donkeycar-sds6/gym-donkeycar/
git checkout master
git pull
pip install -e .
```
### 2.3 Simulation environment: /media/rainer/_data/30-projects/mysims/mysim_sds7_1
```
donkey createcar --path=./rC3car
```

### 2.4 [Simulator Race Dec 14th, 2020](https://github.com/tawnkramer/gym-donkeycar/releases/tag/v20.11.17)


```
```
