# Whisper Speaker Diarization
Speaker Diarization

## Packages
- Docker
- Nvidia-Docker

## Setup
I prefer using the Docker because of simplicity

```
cd your-working-directory 
docker run --gpus all -d -it -p 8848:8888 -v $(pwd):/home/jovyan/work -e GRANT_SUDO=yes -e JUPYTER_ENABLE_LAB=yes --user root cschranz/gpu-jupyter:v1.4_cuda-11.6_ubuntu-20.04 
```

Default password is `gpu-jupyter`


## Usage
- Access the jupyter lab via http://localhost:8848 
- Start with jupyter notebook `01_Speaker_Diarizateion.ipynb`. 
