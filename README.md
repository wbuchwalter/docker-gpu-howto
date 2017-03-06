# docker-gpu-howto

## 1. Why Docker + GPU?

## 2. State of GPU support on the different orchestrators 
### 2.1. Swarm 
### 2.2. Kubernetes  
### 2.3. DC/OS  
  
## 2.5. Alternative: Azure Batch Shipyard 

## 3. Walkthrough: Creating a cluster supporting GPU workloads
### 3.1. Using ACS-Engine to create the clusters
### 3.2. Installing the drivers
#### 3.2.x. Soon: Hook in ACS-Engine Template

## 4. Scheduling GPU workloads
### 4.1 kubernetes: Exposing the drivers to the container
  
## 5. DevOps practices enabled by Docker + GPU
### 5.1 Uploading logs and checkpoint files to azure blob storage
### 5.2 Multi-Hyopthesis parallel training
### 5.3 Daily scheduled retraining on new data

## 6. Next
### 6.1 Autoscaler for GPU VM
