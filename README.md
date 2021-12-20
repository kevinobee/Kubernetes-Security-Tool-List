# Kubernetes Security Tool List

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
    
## Observability

1. [Pixie](https://github.com/pixie-io/pixie)

    Pixie is an open source observability tool for Kubernetes applications. Use Pixie to view the high-level state of your cluster (service maps, cluster resources, application traffic) and also drill-down into more detailed views (pod state, flame graphs, individual full-body application requests).

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

    Falco is the first runtime security project to join CNCF as an incubation-level project. Falco acts as a security camera detecting unexpected behavior, intrusions, and data theft in real time.

## Security Hardening

1. [Kubernetes Security Profiles Operator](https://github.com/kubernetes-sigs/security-profiles-operator)

    This project is the starting point for the Security Profiles Operator (SPO), an out-of-tree Kubernetes enhancement which aims to make it easier for users to use SELinux, seccomp and AppArmor in Kubernetes clusters.

1. [localtls](https://github.com/Corollarium/localtls)

    DNS server for providing TLS to web services on local addresses
