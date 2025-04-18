# Brainboard ServiceNow integration

Brainboard is an end-to-end solution that allows you to visually design and manage your cloud infrastructures using Terraform with best practices.

## Deployment Stages

1. Install the update set 'Brainboard Global Update Set.xml'. You can find it in the files.
   Make sure to commit this update set to your instance before installing the scoped app from this repository.
   The update set is in the Global Scope and allows the creation of Catalog Variable records from other Scoped Apps.

2. Install the Scoped App from this Git repository.
   Brainboard Architecture Templates, Variables, Projects, and Environments are imported from the Brainboard API every 30 minutes.
   Therefore, you need to wait up to 30 minutes to see the Architecture Templates.
