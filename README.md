# Kubernetes Security Tool List

See the [Security and Compliance](https://landscape.cncf.io/card-mode?category=security-compliance&grouping=category) listings on the [CNCF Cloud Native Interactive Landscape](https://landscape.cncf.io/) for a full set of Kubernetes security tools.

## Access Control

1. [Rakkess](https://github.com/corneliusweig/rakkess)

    Review Access - kubectl plugin to show an access matrix for k8s server resources

1. [kubectl-who-can](https://github.com/aquasecurity/kubectl-who-can)

    Show who has RBAC permissions to perform actions on different resources in Kubernetes

1. [audit2rbac](https://github.com/liggitt/audit2rbac)

    Autogenerate RBAC policies based on Kubernetes audit logs

## Code Policy Enforcement

1. [Datree](https://hub.datree.io/)

    Prevent Kubernetes misconfigurations from reaching production
    
1. [Open Policy Agent (OPA)](https://www.openpolicyagent.org/docs/latest/kubernetes-introduction/)

    The OPA is an open-source, general-purpose policy engine that can be used to enforce policies on various types of software systems like microservices, CI/CD pipelines, gateways, Kubernetes, etc. OPA was developed by Styra and is currently a part of CNCF.
    
1. [Gatekeeper](https://open-policy-agent.github.io/gatekeeper/website/docs/)

    Gatekeeper introduces the following functionality:

    * An extensible, parameterized policy library
    * Native Kubernetes CRDs for instantiating the policy library (aka "constraints")
    * Native Kubernetes CRDs for extending the policy library (aka "constraint templates")
    * Audit functionality

1. [Gatekeeper Policy Library](https://github.com/open-policy-agent/gatekeeper-library)

    See the Gatekeeper policy library for a collection of constraint templates and sample constraints that you can use with Gatekeeper.
    
1. [Conftest](https://github.com/open-policy-agent/conftest)

    Conftest helps you write test assertions using the Rego language from Open Policy Agent against structured configuration data such as Kubernetes configuration files.

1. [kube-score](https://github.com/zegl/kube-score)

    `kube-score` is a tool that performs static code analysis of your Kubernetes object definitions.

## Observability

1. [Pixie](https://github.com/pixie-io/pixie)

    Pixie is an open source observability tool for Kubernetes applications. Use Pixie to view the high-level state of your cluster (service maps, cluster resources, application traffic) and also drill-down into more detailed views (pod state, flame graphs, individual full-body application requests).
    
1. [ThreatMapper](https://github.com/deepfence/ThreatMapper)

    Open source cloud native security observability platform. Linux, K8s, AWS Fargate and more.
    Deepfence ThreatMapper hunts for vulnerabilities in your production platforms, and ranks these vulnerabilities based on their risk-of-exploit. 

## Security Scanning

1. [Kubescape](https://github.com/armosec/kubescape)

    Kubescape is the first open-source tool for testing if Kubernetes is deployed securely according to multiple frameworks: regulatory, customized company policies and DevSecOps best practices, such as the NSA-CISA and the MITRE ATT&CK®.
    
3. [kube-bench](https://github.com/aquasecurity/kube-bench)

    Checks whether Kubernetes is deployed according to security best practices as defined in the CIS Kubernetes Benchmark

1. [kube-hunter](https://github.com/aquasecurity/kube-hunter)

    Hunt for security weaknesses in Kubernetes clusters

1. [trivy](https://github.com/aquasecurity/trivy)

    Scanner for vulnerabilities in container images, file systems, and Git repositories, as well as for configuration issues

1. [trivy-plugin-kubectl](https://github.com/aquasecurity/trivy-plugin-kubectl)

    A Trivy plugin that scans the images of a kubernetes resource

1. [tfsec](https://github.com/aquasecurity/tfsec)

    Security scanner for your Terraform code

1. [Falco](https://falco.org/)

    Falco acts as a security camera detecting unexpected behavior, intrusions, and data theft in real time.

## Security Hardening

1. [Kubernetes Security Profiles Operator](https://github.com/kubernetes-sigs/security-profiles-operator)

    This project is the starting point for the Security Profiles Operator (SPO), an out-of-tree Kubernetes enhancement which aims to make it easier for users to use SELinux, seccomp and AppArmor in Kubernetes clusters.

1. [localtls](https://github.com/Corollarium/localtls)

    DNS server for providing TLS to web services on local addresses

## More Reading

Take a look at [Awesome Kubernetes (K8s) Security](https://github.com/magnologan/awesome-k8s-security) for a curated list for Kubernetes (K8s) Security resources such as articles, books, tools, talks and videos.
