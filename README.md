# Lab Environment

**Purpose:** Showcase a small-scale hybrid cloud lab setup, including on-premises virtualization and connectivity to cloud resources. This repository is geared towards IT enthusiasts, consultants, and SMB IT managers looking to design or understand a home lab or test environment that mirrors production scenarios.

**Technologies & Tools:** VMware ESXi / Hyper-V (virtualization), pfSense (networking), Azure/AWS (cloud components), various OS (Windows, Linux) for lab VMs.

**Use Cases:**
- Simulate a production network on a smaller scale for testing and training.
- Experiment with cloud integration (e.g., site-to-site VPN from the lab network to Azure).
- Practice deployment and troubleshooting in a risk-free environment before implementing changes in a live environment.

## Lab Layout

The `configs/` directory includes configurations used in the lab (for example, enabling GPU passthrough on a hypervisor). The `diagrams/` folder contains a network diagram **(homelab-network.png)** illustrating the lab's topology, including VLANs, firewall, servers, and cloud connectivity.

## Usage

Use the provided examples as a reference to build your own lab:
- Apply configurations like [`gpu-passthrough.conf`](configs/gpu-passthrough.conf) on your hypervisor to enable advanced features (e.g., pass a physical GPU into a VM for testing GPU-intensive applications).
- Refer to the network diagram to plan IP addressing, VLANs, and network device roles in your lab setup.

This repository is meant as a blueprint; adjust the specifics to match your hardware and goals.
