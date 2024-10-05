# Kube-dAI
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

**Note:** While our initial focus is on AWS Cloud, we intend to extend support to other cloud providers like Google Cloud Platform (GCP) and Microsoft Azure in the future.

## 🔍 Project Focus

Our project delves deep into compute and storage best practices for each deployment, covering:

### Data Processing

- **Apache Spark**: Including examples with various storage backends, compute configurations, autoscaling, and schedulers like YuniKorn, Volcano, and Kueue.
- **Spark-RAPIDS**: Accelerate Spark workloads using GPUs.
- **Apache Flink**
- **RayData**
- **Trino** (formerly PrestoSQL)

### Artificial Intelligence

- **KServe**
- **RayServe**
- **RayTrain**
- **NVIDIA Triton Inference Server**
- **Leader Worker Set (LWS)**

For each technology, we provide:

- **Scalable Architecture Designs**
- **Performance Optimization Techniques**
- **Resource Allocation Strategies**
- **Storage Configuration Best Practices**
- **Comprehensive Benchmarks**
- **Observability Solutions**

## 📊 Benchmarks and Best Practices

Each repository includes detailed benchmarks and best practices, covering:

- **Scalability Tests**: From gigabytes to petabytes on AWS infrastructure.
- **Throughput and Latency Measurements**
- **Resource Utilization Optimizations**
- **Cost-Efficiency Analyses**
- **Comparative Studies of AWS Storage Solutions**: EBS, EFS, S3, etc.
- **Scheduler Performance**: Evaluations of YuniKorn, Volcano, and KubeQueue.
- **Best Practices for Specific Workload Types**

## 📂 Repository Structure

Our GitHub organization hosts multiple repositories, each based on a standardized **Factory Repository Template**. This template includes:

- **Docusaurus Documentation Website**: For comprehensive project documentation.
- **GitHub Actions**: Automated CI/CD pipelines.
- **Infrastructure-as-Code**: Terraform and Helm configurations tailored for AWS.
- **Standardized Directory Structure**: Ensuring consistency across projects.

### Repositories

**Data Processing:**

- [`spark-on-kubernetes`](https://github.com/Kube-dAI/spark-on-kubernetes): Apache Spark deployment patterns and benchmarks on AWS.
- [`spark-rapids-on-kubernetes`](https://github.com/Kube-dAI/spark-rapids-on-kubernetes): Apache Spark on GPUs with Spark-RAPIDS on AWS.
- [`flink-on-kubernetes`](https://github.com/Kube-dAI/flink-on-kubernetes): Apache Flink deployment patterns and benchmarks on AWS.
- [`raydata-on-kubernetes`](https://github.com/Kube-dAI/raydata-on-kubernetes): RayData deployment patterns and benchmarks on AWS.
- [`trino-on-kubernetes`](https://github.com/Kube-dAI/trino-on-kubernetes): Trino deployment patterns and benchmarks on AWS.

**Artificial Intelligence:**

- [`kserve-on-kubernetes`](https://github.com/Kube-dAI/kserve-on-kubernetes): KServe deployment patterns and benchmarks on AWS.
- [`rayserve-on-kubernetes`](https://github.com/Kube-dAI/rayserve-on-kubernetes): RayServe deployment patterns and benchmarks on AWS.
- [`raytrain-on-kubernetes`](https://github.com/Kube-dAI/raytrain-on-kubernetes): RayTrain deployment patterns and benchmarks on AWS.
- [`triton-on-kubernetes`](https://github.com/Kube-dAI/triton-on-kubernetes): NVIDIA Triton Inference Server deployment patterns and benchmarks on AWS.
- [`lws-on-kubernetes`](https://github.com/Kube-dAI/lws-on-kubernetes): LWS deployment patterns and benchmarks on AWS.

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

## 📜 License

This project is open-source and available under the [Apache License 2.0](LICENSE).

## 📞 Support

For assistance or to discuss advanced use cases:

- Open an issue in the relevant repository
- Join our community [Discord](https://discord.com/channels/1291838866990301295/1291838866990301298)
- Explore our comprehensive [documentation](https://docs.kubedai.org) (placeholder link)

## 🔗 Useful Links

- [Project Website](https://kubedai.org) (placeholder link)
- [Documentation](https://docs.kubedai.org) (placeholder link)
- [Community Forum](https://forum.kubedai.org) (placeholder link)
- [Blog](https://blog.kubedai.org) (placeholder link) - For the latest benchmarks and best practices

## 🌐 Stay Connected

- Twitter: @Kube_dAI (placeholder)
- LinkedIn: Kube-dAI (placeholder)
- Discord Community: [Discord](https://discord.com/channels/1291838866990301295/1291838866990301298)

## 📝 Disclaimer

Please note that Kube-dAI is a community-driven project and is not affiliated with AWS or any other company. All trademarks and registered trademarks are the property of their respective owners.

---

<p align="center">Kube-dAI: Empowering Scalable Data and AI Deployments on Kubernetes</p>
