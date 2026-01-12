# CloudOps Handbook

> ⚠️ **Status: Under Construction** - This repository is currently being built. We have only a few guides available at the moment. If you have expertise in any cloud operations or DevOps topic, **we invite you to contribute your guides!** After community contributions are made, this handbook will be continuously updated and expanded. All contributed content must be original work and placed under copyright. Please do not upload content that belongs to other creators or vendors.

A comprehensive collection of guides, cheatsheets, and curated resources for cloud infrastructure, DevOps tools, and platform engineering. This handbook serves as a practical reference for engineers working with modern cloud-native technologies.

## 📚 What's Inside

Each topic folder contains:
- **Guides** - In-depth tutorials with step-by-step instructions and best practices
- **Cheatsheets** - Quick reference cards for common commands and workflows
- **Prompts** - Suggested GenAI prompts for ChatGPT, Gemini, Claude, etc. organized by use case

## 🗂️ Repository Structure

```
cloudops-handbook/
├── kubernetes/          # Container orchestration
├── prometheus/          # Metrics and monitoring
├── grafana/             # Visualization and dashboards
├── github/              # Git and version control
├── github-actions/      # CI/CD automation
├── docker/              # Containerization
├── terraform/           # Infrastructure as Code
├── aws/                 # Amazon Web Services
├── azure/               # Microsoft Azure
├── gcp/                 # Google Cloud Platform
├── templates/           # Templates for creating new content
└── assets/              # Shared diagrams, images, and icons
```

## 📖 Topics Covered

- **[Kubernetes](./kubernetes/)** - Container orchestration, workloads, networking, and security
- **[Prometheus](./prometheus/)** - Metrics collection, alerting, and monitoring
- **[Grafana](./grafana/)** - Visualization, dashboards, and alerting
- **[GitHub](./github/)** - Git workflows and version control
- **[GitHub Actions](./github-actions/)** - Workflow automation and CI/CD pipelines
- **[Docker](./docker/)** - Containerization basics and patterns
- **[Terraform](./terraform/)** - Infrastructure provisioning and management
- **[AWS](./aws/)** - Amazon Web Services guides
- **[Azure](./azure/)** - Microsoft Azure guides
- **[GCP](./gcp/)** - Google Cloud Platform guides

## 🚀 Quick Start

### Browse a Topic
Navigate to any topic folder to find guides, cheatsheets, and GenAI prompts for that technology.

### Use GenAI Prompts
Each topic includes a `prompts.md` file with curated prompts for ChatGPT, Gemini, Claude, and other GenAI tools. Use these as starting points for learning or problem-solving.

### Find Quick References
Look for `cheatsheet.md` or `cheatsheet.pdf` in each topic folder for quick command references.

## 🤝 Contributing

Contributions are welcome! We're actively building this handbook and would love your expertise:

1. **Choose a topic** - Pick an existing topic or suggest a new one
2. **Create a guide** - Write a markdown file with your expertise
3. **Add a cheatsheet** - Create a quick reference (MD or PDF)
4. **Suggest prompts** - Add useful GenAI prompts to the topic's `prompts.md`

### Contributing Guidelines

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/add-kubernetes-cni-guide`)
3. Commit your changes (`git commit -m 'Add Kubernetes CNI deep dive guide'`)
4. Push to the branch (`git push origin feature/add-kubernetes-cni-guide`)
5. Open a Pull Request

**Important:**
- ✅ All contributed content must be your original work
- ✅ Content is subject to the project's copyright and license
- ❌ Do not upload content from other creators, vendors, or proprietary sources
- ❌ Always respect intellectual property rights

See [CONTRIBUTING.md](./CONTRIBUTING.md) for detailed guidelines.

## 📝 File Structure for Each Topic

Each topic folder follows this optional structure:

```
topic-name/
├── prompts.md              # GenAI prompts organized by use case
├── cheatsheet.md           # Quick reference (markdown)
├── cheatsheet.pdf          # Quick reference (PDF) - optional
├── getting-started.md      # Introductory guide
├── [specific-guide].md     # Additional topic-specific guides
├── images/                 # Diagrams and screenshots
└── [other-resources]       # PDFs, examples, etc.
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## ⭐ Acknowledgments

This handbook is built on knowledge from the DevOps community, official documentation, and hands-on experience. Special thanks to all contributors and the open-source community.

## 🎯 Using This with GenAI Tools

Each topic includes a `prompts.md` file with curated prompts. Here's how to use them effectively:

1. **Select a Use Case** - Find a scenario matching your needs in the topic's `prompts.md`
2. **Copy the Prompt** - Use the provided prompt as a starting point
3. **Customize** - Adapt it to your specific environment and requirements
4. **Get Better Results** - Follow the tips provided for each topic

### Supported GenAI Tools
- ChatGPT (OpenAI)
- Gemini (Google)
- Claude (Anthropic)
- Other LLM-based AI assistants

## 📚 Using Templates

Create new content using our templates:
- [guide-template.md](./templates/guide-template.md) - For writing guides
- [cheatsheet-template.md](./templates/cheatsheet-template.md) - For quick references
- [prompts-template.md](./templates/prompts-template.md) - For GenAI prompts
- [troubleshooting-template.md](./templates/troubleshooting-template.md) - For troubleshooting guides

## 🔗 Official Documentation

- [Kubernetes Official Docs](https://kubernetes.io/docs/)
- [Prometheus Documentation](https://prometheus.io/docs/)
- [Docker Documentation](https://docs.docker.com/)
- [GitHub Documentation](https://docs.github.com/)
- [Terraform Documentation](https://www.terraform.io/docs)

---

**Made with ❤️ for the DevOps and Cloud Operations community**

*Last updated: January 2026*
