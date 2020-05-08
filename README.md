# Reinforcement Learning environments and agents/policies used for the FNAL accelerator application

## Software Requirement
* Python 3.7 
* The environemnt framework is built of [OpenAI Gym](https://gym.openai.com) 
* Additional python packages are defined in the setup.py 
* For now, we assumes you are running at the top directory 

## Installing 
* Pull code from repo
```
git clone https://github.com/fermilab-accelerator-ai/control-for-accelerators-in-hep.git
```
* Install control-for-accelerators-in-hep (via pip):
```
cd control-for-accelerators-in-hep
pip install -e . --user
```

## Directory Organization
```
├── setup.py
├── scripts                           : a folder contains RL steering scripts  
├── dataprep                          : a folder with code to read and prep data
├── surrogates                        : a folder contains surrogate model code
├── agents                            : a folder contains agent codes
├── gym_accelerator                   : a folder containing the accelerator environments
├── cfg                               : a folder contains the agent and environment configuration
├── utils                             : a folder contains utilities
          
```
