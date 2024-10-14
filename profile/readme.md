# Kube-dAI 🚀
*Kube (Kubernetes) and dAI (Data and AI)*

*Pronounced: "Cubed AI"*

## Kube-dAI: Empowering Scalable Data and AI Solutions on Kubernetes

Welcome to **Kube-dAI**, an open-source initiative dedicated to providing highly scalable deployment patterns, infrastructure-as-code templates, and best practices for data processing and AI workloads on Kubernetes.

## 🚀 About Kube-dAI

Kube-dAI aims to empower organizations with battle-tested, scalable architectures for running data and AI workloads on Kubernetes, primarily on **AWS Cloud**. Our project offers:

- **End-to-End Deployment Blueprints**: Automated scripts for deploying VPCs and EKS clusters with essential Kubernetes addons on AWS.
- **Best Practices**: Compute, storage, and networking optimization techniques specific to AWS infrastructure.
- **Comprehensive Benchmarks**: Performance evaluation and cost-efficiency analyses on AWS services.
- **Infrastructure-as-Code Templates**: Rapid deployment using Terraform and Helm tailored for AWS.
- **Observability Integration**: Tools for monitoring and logging, including Spark History Server and FluentBit.

Whether you're orchestrating large-scale data processing pipelines or deploying cutting-edge AI models, Kube-dAI provides the insights and tools you need to maximize your Kubernetes infrastructure on AWS.

## 🔍 Project Focus

Our project delves deep into compute and storage best practices for each deployment, covering:

🔍 Focus Areas

 - **Data Processing Pipelines:** Optimized for Spark, Flink, Trino, and more.
 - **Machine Learning Inference & Training:** Using KServe, RayServe, NVIDIA Triton.
 - **Scalable Infrastructure:** Automated deployment with Terraform, Crossplane, and GitOps using ArgoCD.
 - **GitOps:** LContinuous delivery and infrastructure management with GitOps.

## 🔧 How It Works

Our repositories provide everything you need to get started:

 - **Infrastructure as Code (IaC):** Easily deploy VPCs, EKS clusters, and essential Kubernetes add-ons on AWS.
 - **Data & AI Workloads:** Deploy Spark, Ray, Trino, and ML models with scalable architecture.
 - **Monitoring & Observability:** Pre-integrated tools like Prometheus, Grafana, and the Spark History Server.

## 📊 Benchmarks and Best Practices

Each repository includes detailed benchmarks and best practices, covering:

- **Scalability Tests**: From gigabytes to petabytes on AWS infrastructure.
- **Throughput and Latency Measurements**
- **Resource Utilization Optimizations**
- **Cost-Efficiency Analyses**
- **Comparative Studies of AWS Storage Solutions**: EBS, EFS, S3, etc.
- **Scheduler Performance**: Evaluations of YuniKorn, Volcano, and KubeQueue.
- **Best Practices for Specific Workload Types**

## 📂 Repositories

**Data Processing:**

- 🚀 [`spark-rapids-on-kubernetes`](https://github.com/Kube-dAI/spark-rapids-on-kubernetes): The first live repository! Accelerate Apache Spark workloads using GPUs with Spark RAPIDS on AWS. Fully launched and ready to use!
- ⏳ [`spark-on-kubernetes`](https://github.com/Kube-dAI/spark-on-kubernetes): Apache Spark deployment patterns and benchmarks on AWS. (Launching soon)
- ⏳ [`flink-on-kubernetes`](https://github.com/Kube-dAI/flink-on-kubernetes): Apache Flink deployment patterns and benchmarks on AWS. (Launching soon)
- ⏳ [`raydata-on-kubernetes`](https://github.com/Kube-dAI/raydata-on-kubernetes): RayData deployment patterns and benchmarks on AWS. (Launching soon)
- ⏳ [`trino-on-kubernetes`](https://github.com/Kube-dAI/trino-on-kubernetes): Trino deployment patterns and benchmarks on AWS. (Launching soon)
- ⏳ [`druid-on-kubernetes`](https://github.com/Kube-dAI/druid-on-kubernetes): Apache Druid deployment patterns and benchmarks on AWS. (Launching soon)

**Artificial Intelligence:**

- ⏳ [`rayserve-on-kubernetes`](https://github.com/Kube-dAI/rayserve-on-kubernetes): RayServe deployment patterns and benchmarks on AWS. (Launching soon)
- ⏳ [`triton-on-kubernetes`](https://github.com/Kube-dAI/triton-on-kubernetes): NVIDIA Triton Inference Server deployment patterns and benchmarks on AWS. (Launching soon)
- ⏳ [`kserve-on-kubernetes`](https://github.com/Kube-dAI/kserve-on-kubernetes): KServe deployment patterns and benchmarks on AWS. (Launching soon)
- ⏳ [`lws-on-kubernetes`](https://github.com/Kube-dAI/lws-on-kubernetes): LWS deployment patterns and benchmarks on AWS. (Launching soon)

## 💻 Getting Started

To leverage Kube-dAI for your projects:

1. **Explore Our Repositories**: Find relevant technologies and patterns.
2. **Clone the Repository of Interest**:

   ```
   git clone https://github.com/Kube-dAI/<repository-name>.git
   ```
3. Follow the detailed README in each repository for setup, benchmarking, and best practices.

## 🤝 Contributing

We welcome contributions from the community! To contribute:

1. Fork the relevant repository.
2. Create a new branch for your feature, benchmark, or optimization.
3. Submit a pull request with your improvements.

Please review our [Contribution Guidelines](CONTRIBUTING.md) for more details.

## 🔗 Blogs

- [Medium Blogs](https://medium.com/@kubedai24) 

## 📜 License

This project is open-source and available under the [Apache License 2.0](LICENSE).

## 📞 Support

For assistance or to discuss advanced use cases:

- Open an issue in the relevant repository

## 📝 Disclaimer

Kube-dAI is a community-driven project and is not affiliated with AWS or any other company. All trademarks and registered trademarks are the property of their respective owners.

