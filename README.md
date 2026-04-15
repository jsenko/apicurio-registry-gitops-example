# Fulfillment Team Schemas

This branch contains schemas managed by the **Fulfillment team** for the
Apicurio Registry GitOps multi-repo example.

See the [`main` branch README](https://github.com/Apicurio/apicurio-registry-gitops-example/blob/main/README.md)
for the full scenario description and setup instructions.

## Contents

- **fulfillment/** — shipment event schemas (loaded by both prod and staging)
- **experimental/** — staging-only schemas for features in development

## Note

This branch does **not** contain a registry configuration file (`registry-v0`).
The registry configuration is managed by the Platform team on the `main` branch.
When using multi-repo mode, this branch is aggregated alongside `main`.
