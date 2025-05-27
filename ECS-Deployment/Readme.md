
# ECS Deployment Use Case

This use case demonstrates how to use **Facets** to simplify and scale containerized application deployments using **Amazon ECS**.

It includes:

- Project Type – Blueprint for deploying services on ECS with supporting resources.
- Project – A demo project implementing a Spring PetClinic app with ECS.

## Architecture Overview

The ECS deployment project provisions the following infrastructure:
![ECS Deployment](https://github.com/user-attachments/assets/0f6783a7-7360-4c86-8ee2-89ae586d004b)


### Components:

- **loadbalancer**: Handles external traffic routing to the ECS service.
- **petclinic (ecs_service)**: Spring PetClinic app deployed as a container.
- **database (postgres)**: Backend PostgreSQL database.
- **s3bucket**: Object storage for app assets.
- **ecs-cluster**: ECS cluster hosting the service.
- **vpc-network**: Underlying network infrastructure.

## How to Use in Facets

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

[ECS Deployment Use Case – Facets](https://www.facets.cloud/use-case/simplify-and-scale-your-ecs-deployments)

---

Maintained by the Facets Team.
