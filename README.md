# CodeKN

KN is a public and open-source project used to present the development process of the real-world project.

The purpose of the project is to build a platform for developers. As a first step, it gathers articles and engineering post URLs from the authority website and provides a useful user interface for developers.

Tech stack: Go-lang, Docker, Kubernetes, MySQL.

## Includes

### ProfX

#### Purpose

Back-end service to gather information from different sources and store in easy to use structured way.

#### Current state

Deployed to Kubernetes cluster and uses MySQL database cluster to store the information.

### Flash

#### Purpose:

API for the back-end data.

#### Current state:

Dummy API endpoint which exposes env of the pod.
