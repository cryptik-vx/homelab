# Introduction
This repo contains the configuration and documentation for my homelab.
The point of my homelab is mostly for fun and learning. Building systems and hosting applications efficiently and securely is a compelling set of tasks and goals, which having a homelab facilitates. Self-hosting gives me complete control and responsibility over the applications and services that I rely on, which pushes me to be creative while considering the logistics of backup strategies, scalability, deployment difficulty, and maintenance.
# Cluster Provisioning and Architecture
I use Talos Linux as the OS for individual nodes, because it is both lightweight and hardened by default.
My current goal is to revise the architecture and maintain additional clusters for scheduling workloads in order to make system upgrades and configuration updates more testable and resilient to mistakes.
# Hardware
### Nodes
I use Beelink S12 Mini PCs because they take up minimal space and are affordable enough to acquire in my needed volume.
# Installed Apps & Tools
### Apps
- Linkding
- n8n
- Paperless
- wallabag
- Miniflux
- Audiobookshelf
- Grafana - Connects to CloudNativePG, fires alerts to 3rd party platforms
- Uptime Kuma
### Tools
- CloudNativePG - Hosting PostgreSQL database clusters
- Flux CD
- Cilium - Network Observability
