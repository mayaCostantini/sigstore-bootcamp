# Welcome to this Sigstore (unofficial) bootcamp!
_This repository is a work in progress_ :construction:

An attempt at gathering knowledge to get you started with understanding and using project [Sigstore](https://sigstore.dev).

## What will you find in this guide?

The Sigstore bootcamp is organized the following way:

### General introduction to Sigstore - Getting started

This introductory section offers an overview of project Sigstore:

- **Chapter 1:** General introduction to Sigstore, its history, philosophy and purpose
- **Chapter 2:** How does Sigstore work? Introduction to Sigstore subprojects and workflows
- **Chapter 3:** Installation instructions for the Sigstore Cosign client

### Sigstore use cases: sign everything

- **Chapter 4:** Explain the kind of artifacts Sigstore can sign, how signatures are stored (OCI registries)
- **Chapter 5:** Current support for Sigstore signatures from popular software repositories and container registries

### Using the Sigstore ecosystem-specific clients

This section describes the Sigstore clients available for different language ecosystems: Python, Rust, Java, JavaScript...
how to install them and use them from the command line or as libraries to integrate Sigstore natively into your projects.

- **Chapter 6:** Using the Sigstore language clients API

### Securing CI/CD pipelines with Sigstore

As a cloud-native project, Sigstore possesses a number of integrations with Kubernetes tools to attest content integrity
and to ensure that this content can be trusted when used in a cluster.
The following chapters give examples of how Sigstore signatures can generated by cloud-native CI/CD pipelines and signature verification enforced by Kubernetes admission controllers.

- **Chapter 7:** The Sigstore policy-controller
- **Chapter 8:** Sigstore in Tekton pipelines
- **Chapter 9:** Automatically publishing Sigstore signatures with GitHub Actions
- **Chapter 10:** Using Sigstore with Kyverno

**Installing Sigstore: bootstrap your own private instance**

While Sigstore's public good instance can be safely used to upload signatures for publicly distributed software,
some use cases require users to deploy their own internal Sigstore instance.
Chapters 11 to 14 explain the motivations behind deploying a private Sigstore instance and provide instructions and useful resources
to get started with bootstrapping Sigstore on different environments.

- **Chapter 11:** Why deploy your own Sigstore instance? Motivations
- **Chapter 12:** Single VM installation
- **Chapter 13:** Sigstore The Hard Way: bootstrap your own Sigstore instance on a GCP environment
- **Chapter 14:** Installing Sigstore on Kubernetes

## Appendix

**Sigstore specs index**

Specify useful specs for Sigstore APIs / materials (supported signatures, client specs, entry strutures etc)

**Advanced topics**

A set of resources for advanced Sigstore users.

**Contributing to Sigstore and joining the community**

Contribute to Sigstore and join the project community.

