# HPML-course-materials
Contains all course materials from the HPML group
Course environment: https://coursemgr.advisorssrcdemo.src.surf-hosted.nl/ 
- Login
- Click on "Jupyter"
- Memory: 4 GB
- CPU cores: 2
- Partition: GPU, shared
- time: e.g. 1:30:00 (1h30m)


## Course Overview  
- Hardware (e.g. Tensor cores) and software features (e.g. low level libraries for deep learning) for accelerated deep learning
- Packed data formats
- Profiling PyTorch with TensorBoard
- Parallel computing for deep learning

## Profiling
```bash
git clone --depth=1 https://github.com/SURF-ML/HPML-course-materials.git
python3 -m venv venv
source venv/bin/activate
pip install -r HPML-course-materials/requirements.txt


tensorboard --logdir HPML-course-materials/Day2/notebooks/logs/
```


## Other courses and resources
- AI Guide by LUMI: https://github.com/Lumi-supercomputer/LUMI-AI-Guide
- LLMs on supercomputers: https://gitlab.tuwien.ac.at/vsc-public/training/LLMs-on-supercomputers 
