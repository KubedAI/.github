# Kube-dAI 🚀

*Kubernetes + Data + AI = Cubed AI*

Open-source blueprints for running high-performance data and AI workloads on Kubernetes.


## What is this?

Kube-dAI is where I experiment with emerging tech, build benchmark tools, and create production-ready patterns for data and AI on Kubernetes. Think of it as a lab for scalable data infrastructure—mostly on AWS, always evolving.

**What you'll find here:**
- **Benchmark tools** for Spark, GPU acceleration, and distributed compute
- **Infrastructure patterns** using Terraform, Helm, and GitOps
- **Performance analysis** for real-world workloads (TPC-DS, RAPIDS, shuffle services)
- **Operator utilities** like Spark History Server integrations
- **Agentic AI tools** for data platforms—troubleshooting agents, upgrade agents, and autonomous optimization for Spark, Kubernetes, and distributed systems

If you're running Apache Spark at scale, training models on Kubernetes, or just curious about what's next in cloud-native data—this is the place.


## Projects

| Repository | Description | Status |
|------------|-------------|--------|
| [**spark-rapids-on-kubernetes**](https://github.com/Kube-dAI/spark-rapids-on-kubernetes) | GPU-accelerated Spark with RAPIDS on EKS | ✅ Live |
| [**spark-k8s-benchmarks**](https://github.com/KubedAI/spark-k8s-benchmarks) | TPC-DS benchmark suite for Spark on K8s | ✅ Live |
| [**spark-history-server**](https://github.com/KubedAI/spark-history-server) | Production-grade Helm chart for Spark History Server | ✅ Live |

More coming soon: Celeborn benchmarks, DRA experiments, agent orchestrators.


## Tech Stack

**Orchestration:** Kubernetes (EKS), Karpenter, ArgoCD  
**Data Processing:** Apache Spark, RAPIDS, Velox, Celeborn  
**AI/ML:** KServe, Ray, Triton Inference Server  
**IaC:** Terraform, Crossplane, Helm  
**Observability:** Prometheus, FluentBit, Spark UI


## Get Started

Explore the projects above—each repository has detailed setup instructions, architecture diagrams, and deployment guides.

## Contributing

Got ideas? Found a bug? Want to add a new benchmark?

1. Fork the repo
2. Create a feature branch
3. Submit a PR

No bureaucracy—just useful contributions. Check individual repos for specific guidelines.

## Learn More

📝 [Blog posts on Medium](https://medium.com/@kubedai24)  
💬 Open an issue for questions or advanced use cases  


## License

Apache 2.0 — use it, modify it, ship it.

---

**Disclaimer:** Independent project. Not affiliated with AWS, Apache, or NVIDIA. All trademarks belong to their respective owners.
