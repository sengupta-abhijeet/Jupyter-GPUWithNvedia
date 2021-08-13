# Jupyter-GPUWithNvedia
To enable GPU calculations in Jupyter notebooks, this project takes the NVIDIA CUDA image as the base image and installs their tool stack on top of it. This Project remove the complexity behind setting CUDA driver and tune for jupyter notebook. 

### Requirement.
1. A system with an NVIDIA GPU either physical h/w or any cloud GPU instamces in AWS/Azure/GCP
2. Latest Docker and Docker compose installation on host system.
3. The CUDA toolkit is not required on the host system, as it will be installed within the Docker containers using NVIDIA-docker.




