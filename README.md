# Brainboard ServiceNow integration

Brainboard is an end-to-end solution that allows you to visually design and manage your cloud infrastructures with AI. It leverages Terraform/OpenTofu with best practices to have the predictability and stability the infrastructure needs.

## Deployment Stages

1. Install the update set [Brainboard Global Update Set.xml](./Brainboard%20Global%20Update%20Set.xmll).
   - Make sure to commit this update set to your instance before installing the scoped app from this repository.
   - The update set is in the Global Scope and allows the creation of Catalog Variable records from other Scoped Apps.

2. Install the Scoped App from this Git repository.

**N.B:** Brainboard Architecture Templates, Variables, Projects, and Environments are imported from the Brainboard API every 30 minutes. Therefore, you need to wait up to 30 minutes to see the Architecture Templates.
