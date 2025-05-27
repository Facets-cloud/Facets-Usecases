
# Facets Use Cases Repository

Welcome to the **Facets Use Cases** repository! This repository contains real-world examples demonstrating how to use **Facets** to simplify infrastructure provisioning and streamline software deployment across various use cases.

Each use case is structured as a separate folder, with subdirectories for:

- **Project Type** – A reusable blueprint defining infrastructure and service logic.
- **Project** – A complete implementation using that project type.



## 🚀 Getting Started
Facets allows you to easily import reusable infrastructure blueprints (Project Types) and complete application implementations (Projects) using Git. Follow the steps below to link and import these resources into your Facets Control Plane.

- Steps to Import a Project Type
  1. Go to: Facets Console → Project Types → Create Project
  2. Select: Source → Custom Git Repository
  3. Fill in the details: Git URL, Git Ref (branch or commit ID), Relative Path to the project type folder
For full documentation, visit: Facets Documentation – [Creating a Project](https://readme.facets.cloud/docs/project-types#creating-your-first-project-type)

- Steps to Import a Project
  1. Go to: Facets Console → Projects → Create Project
  2. Toggle: Import Project
  3. Fill in the details: Git URL, Git Ref (branch or commit ID), Relative Path to the project type folder
For full documentation, visit: Facets Documentation – [Creating a Project](https://readme.facets.cloud/docs/creating-a-project)


## Available Use Cases

- [ECS Deployment](./ECS-Deployment) – Streamline ECS container deployments with Postgres, S3, and Load Balancer.
- More use cases coming soon...

---

Built and maintained by the [Facets](https://www.facets.cloud) Team.
