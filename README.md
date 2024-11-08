# PostgreSQL-primary-read-replica-architecture-using-Terraform-and-Ansible.

Create an API that automates the setup of a PostgreSQL primary-read-replica architecture using Terraform and Ansible. The API should accept configurable parameters such as PostgreSQL version, instance type, number of replicas, and key settings like max_connections and shared_buffers. It should dynamically generate Terraform code to provision the infrastructure (e.g., EC2 instances, security groups) and Ansible playbooks to install and configure PostgreSQL, including replication between the primary and replicas.

The API should provide endpoints to generate the code, run the terraform plan and apply it to create the infrastructure, and execute Ansible to configure PostgreSQL. It should return success or error messages at each step, ensuring a smooth end-to-end workflow for the setup process.

Best practices must be followed in terms of security, code modularity, and idempotency. Ensure that the Terraform and Ansible configurations are maintainable and flexible, with clear documentation on how to use and modify the API, including handling edge cases and errors. Do share the readme to explain your approach, future use cases, and assumptions.
