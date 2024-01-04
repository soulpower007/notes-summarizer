# notes-summarizer

Implemented 2 types of ML Ops Pipeline

### 1
 - Orchestrated and implemented the data ingestion, validation, transformation, model training, and evaluation.
 - Containerized the code with Docker and AWS EBS. Served the inference and training endpoints on AWS EC2 with the backend by FastAPI. Automated deployments and CI/CD with Github Actions.
### 2
  - Preprocessed Raw data and stored clean data in S3 bucket. Used Lambda to trigger an event driven model training job using Hugging Face Deep Learning Container and EC2 then deployed to a sagemaker endpoint.
  - The sagemaker training pipeline and deploymnet pipeline as shown in the bottom half of the architecture diagram shown below was integrated into a full-stack web application.
  - 
![alt-text](https://github.com/soulpower007/notes-summarizer/blob/main/Architecture_Diagram_Sagemaker.drawio.png?raw=true)

312383794249.dkr.ecr.us-east-1.amazonaws.com/text-s
