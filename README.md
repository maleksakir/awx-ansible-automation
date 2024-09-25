# AWX Ansible Automation Project

This project demonstrates how to automate server provisioning using Ansible and AWX. The playbook installs Apache, starts the service, deploys a simple web page, and configures the firewall.

## Prerequisites

- AWX installed and configured.
- Ansible installed locally or on the AWX controller.
- A target server accessible via SSH.

## Project Structure

- **main.yml**: The Ansible playbook to automate tasks.
- **inventory**: Inventory file specifying the target server.
- **README.md**: Project documentation.

## How to Run the Playbook in AWX

1. Upload this project to your AWX Git project.
2. Create an **Inventory** in AWX matching the `inventory` file.
3. Create a **Template** pointing to the `main.yml` playbook.
4. Launch the playbook.

The playbook installs Apache, starts it, deploys an HTML file, and configures the firewall.
