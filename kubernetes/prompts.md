# Kubernetes - GenAI Prompts

> This file contains suggested prompts for use with GenAI tools like ChatGPT, Gemini, Claude, etc. Use these as starting points and customize them for your specific needs.

## Use Case 1: Getting Started with Kubernetes

### Prompt
```
I'm new to Kubernetes and want to understand the fundamentals. Can you explain:
1. What is a Pod and why is it the smallest deployable unit?
2. What are the differences between Deployments, StatefulSets, and DaemonSets?
3. What is a Service and how does it expose applications?
Provide simple examples for each.
```

### Expected Output
- Clear explanations of core Kubernetes concepts
- YAML examples for each object type
- Use cases for each deployment strategy

---

## Use Case 2: Troubleshooting Pod Issues

### Prompt
```
My Kubernetes pod is failing to start. Help me debug by explaining:
1. What are the most common reasons for ImagePullBackOff and CrashLoopBackOff errors?
2. What kubectl commands should I use to investigate the issue?
3. How do I check logs from a failed container?
Provide the exact kubectl commands I should run.
```

### Expected Output
- Step-by-step debugging process
- Common error scenarios and solutions
- Actual kubectl commands to execute

---

## Use Case 3: Configuring Networking and Service Discovery

### Prompt
```
I need to set up networking in my Kubernetes cluster. Please explain:
1. How does a ClusterIP Service differ from NodePort and LoadBalancer?
2. How does Kubernetes DNS work for service discovery?
3. How can I set up Ingress for external access with proper routing?
Include YAML examples for each scenario and explain when to use each type.
```

### Expected Output
- Explanation of networking models
- Complete YAML configurations
- Best practices for service exposure

---

## Use Case 4: ConfigMaps and Secrets Management

### Prompt
```
I need to manage configuration and sensitive data in Kubernetes. Guide me on:
1. When should I use ConfigMaps vs Secrets?
2. How do I create and mount ConfigMaps in a Pod?
3. What are the best practices for handling sensitive credentials securely?
Provide YAML examples for both ConfigMap and Secret usage.
```

### Expected Output
- ConfigMap and Secret creation examples
- Various mounting strategies
- Security best practices

---

## Use Case 5: Scaling and Resource Management

### Prompt
```
I want to ensure my applications scale properly in Kubernetes. Explain:
1. How does Horizontal Pod Autoscaler (HPA) work?
2. What are resource requests and limits, and why are they important?
3. How do I set up HPA based on CPU and memory metrics?
Provide complete YAML configuration examples.
```

### Expected Output
- HPA configuration examples
- Resource request/limit best practices
- Monitoring metrics needed for scaling

---

## Use Case 6: Persistent Storage

### Prompt
```
I need persistent storage for stateful applications in Kubernetes. Explain:
1. What are PersistentVolumes (PV) and PersistentVolumeClaims (PVC)?
2. How do I set up storage for different use cases (databases, logs, cache)?
3. What are the differences between storage classes?
Include YAML examples for a typical database setup.
```

### Expected Output
- PV and PVC configuration examples
- Storage class setup
- Real-world persistence patterns

---

## Use Case 7: RBAC and Security

### Prompt
```
I need to implement Role-Based Access Control (RBAC) in Kubernetes. Guide me on:
1. What are Roles, ClusterRoles, RoleBindings, and ClusterRoleBindings?
2. How do I create a service account with specific permissions?
3. What are the security best practices for RBAC?
Provide YAML examples for common scenarios.
```

### Expected Output
- RBAC object explanations
- ServiceAccount creation
- Example RBAC policies with explanations

---

## Use Case 8: Deployments and Rolling Updates

### Prompt
```
I need to deploy updates safely to production. Help me understand:
1. How do rolling updates work in Kubernetes?
2. What are readiness and liveness probes, and why are they critical?
3. How do I configure deployment strategies (Rolling, Blue-Green, Canary)?
Include YAML examples for each strategy.
```

### Expected Output
- Probe configuration examples
- Deployment strategy implementations
- Best practices for safe deployments

---

## Use Case 9: Monitoring and Logging

### Prompt
```
I need to monitor my Kubernetes cluster. Explain:
1. What metrics should I monitor in Kubernetes (CPU, memory, network, etc.)?
2. How do I set up Prometheus to scrape Kubernetes metrics?
3. What are the best practices for container logging?
Include configuration examples and recommended tools.
```

### Expected Output
- Key metrics to monitor
- Prometheus scrape configuration
- Logging strategies and tools

---

## Use Case 10: Helm and Package Management

### Prompt
```
I want to use Helm to manage Kubernetes applications. Guide me on:
1. What is a Helm chart and how does it differ from raw YAML?
2. How do I install and manage releases with Helm?
3. How do I create my own Helm chart for my application?
Provide step-by-step examples.
```

### Expected Output
- Helm concepts explained
- Installation and usage examples
- Helm chart creation tutorial

---

## Tips for Better Results
- Be specific about your Kubernetes version if you have compatibility concerns
- Include your infrastructure details (cloud provider, networking plugin)
- Ask for YAML examples when discussing configuration
- Request troubleshooting steps in order of likelihood
- Include security implications in your questions
