# Base Dockerfile for the GPU based stand models

## Installation and build

1. Install Docker according the instructions:
   
   https://docs.docker.com/install/linux/docker-ce/ubuntu/
   
2. Install nVIDIA Docker according the instructions:

   https://github.com/NVIDIA/nvidia-docker
   
3. Clone the repo and `cd` to project root:
    ```
    git clone https://github.com/deepmipt/stand_docker_cuda.git
    cd stand_docker_cuda
    ```
4. Build Docker image:
    ```
    sudo docker build -t stand/docker_cuda .
    ```