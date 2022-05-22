# sim2real_challenge

This repository is related to the 2022 CoG Robomaster Sim2Real Challenge which is organized by CASIA DRL Team.In this repository, It contains code written according to the specific track 1 and official documents from https://github.com/DRL-CASIA/COG-sim2real-challenge.



## 0. Run it

### For first use:

**Step 1**: Give the simulator executable permission to the given env. Here is the example for linux_v1

``chmod +x linux_v1/cog_sim2real_env.x86_64``

**Step 2**: Create env in anaonda or miniconda

``conda env create -f environment_*.yml  ``

**Step 3**: Install the COG_API package with command

``pip install CogEnvDecoder``

**Step 4**: Run the api_test.py.



### already configured：

**Step 1**: ``conda activate sim2real``

**Step 2**:  Run api_test.py