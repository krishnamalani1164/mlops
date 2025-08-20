# MLOps Learning Repository

## What is MLOps?

Machine learning operations (MLOps) are a set of practices that automate and simplify machine learning (ML) workflows and deployments. It is the development and use of machine learning models by development operations (DevOps) teams. MLOps adds discipline to the development and deployment of machine learning models, making the development process more reliable and productive.

## MLOps Core Components

MLOps combines three key areas:
- **ML Design** - Problem definition, data requirements, model architecture
- **Model Development** - Data preparation, feature engineering, model training
- **Operations** - Model deployment, monitoring, maintenance

## MLOps vs Traditional Development

**Dev (Development)**
- Code development and testing
- QA Team involvement
- Focus on software functionality

**Ops (Operations)** 
- Delivery and deployment
- Infrastructure monitoring
- Production maintenance

## MLOps Workflow

Understanding Problem/Usecase → EDA → Pre-Processing → Feature Engineering → Feature Selection → Model Training & Hypertuning → Model Evaluation → App Building/UI → Deploy

## MLOps Implementation Areas

### 1. Code Standards
- **OOPS Concept**: Object-oriented programming principles for better code structure
- **Modular Coding**: Breaking code into reusable, maintainable modules
- **Logging Module**: Systematic logging for better debugging and monitoring
- **Artifact Management**: Managing components and pipeline artifacts effectively

### 2. Code Versioning
- **Git & GitHub**: Source code version control and collaboration
- **Bitbucket**: Alternative Git-based version control platform
- **GitLab**: Integrated DevOps platform with Git repository management

### 3. Data/Model Versioning & Pipeline Management
- **DVC (Data Version Control)**: Track data and model versions
- **MLflow**: Experiment tracking, model registry, and deployment
- **Neptune**: ML experiment management and model store
- **Seldon**: Model deployment and serving platform
- **Kubeflow**: ML workflows on Kubernetes
- **ZenML**: MLOps framework for reproducible pipelines

### 4. CI/CD Tools
- **GitHub Actions**: Automated workflows integrated with GitHub
- **CircleCI**: Cloud-based continuous integration and delivery
- **Travis CI**: Hosted continuous integration service

### 5. Containerization
- **Docker**: Application containerization for consistent environments
- **Docker Hub**: Cloud-based registry for Docker images
- Ensures code reliability across different environments

### 6. Scalability & Monitoring
- **Kubernetes**: Container orchestration for scalable deployments
- **Prometheus**: Monitoring and alerting toolkit
- **Grafana**: Analytics and interactive visualization platform

### 7. AWS Services
- **IAM (Identity and Access Management)**: User access control
- **ECR (Elastic Container Registry)**: Docker container registry
- **S3 (Simple Storage Service)**: Object storage for data and artifacts
- **EC2 (Elastic Compute Cloud)**: Virtual servers for computing

### 8. All-in-One ML Services
- **AWS Sagemaker**: End-to-end ML platform
- **Google Vertex AI**: Unified ML platform
- **Azure ML**: Microsoft's cloud ML service

## Software Development Life Cycle (SDLC) Integration

MLOps follows SDLC principles:
- **Requirement Analysis**: Understanding ML problem requirements
- **Design**: Architecture and system design
- **Coding**: Implementation of ML pipelines
- **Testing**: Model validation and testing
- **Deployment**: Production model deployment
- **Maintenance**: Ongoing monitoring and updates

## Technologies Stack

**Core ML**: Python, Pandas, NumPy, Scikit-learn
**Experiment Tracking**: MLflow, Neptune, Weights & Biases
**Data Versioning**: DVC, Git LFS
**Containerization**: Docker, Kubernetes
**CI/CD**: GitHub Actions, GitLab CI, Jenkins
**Monitoring**: Prometheus, Grafana, MLflow
**Cloud Platforms**: AWS, Google Cloud, Azure
