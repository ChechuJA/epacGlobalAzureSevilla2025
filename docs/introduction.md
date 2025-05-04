# Introduction to EPAC

EPAC (Enterprise Policy as Code) is a framework designed to manage Azure policies, initiatives, and assignments using a code-first approach. This project demonstrates how to implement EPAC for governance in Azure environments.

## Key Features
- Policy as Code (PAC) implementation.
- Automated deployment pipelines.
- Support for multiple environments (e.g., dev, prod).

## Azure Resource Naming Rules
When creating or assigning resources in Azure, it's important to follow the [Azure Resource Naming Rules](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/resource-name-rules#microsoftauthorization). For example:
- **Policy Assignments**: The `name` field is limited to 24 characters.
- **Policy Definitions**: The `name` field must not exceed 64 characters.
- **Other Resources**: Different resource types have their own naming restrictions.

### Best Practices for Naming
- Use short, descriptive names that convey the purpose of the resource.
- Avoid special characters and spaces in names.
- Use consistent prefixes (e.g., `EPAC-`) to group related resources.

Make sure to review these rules to avoid deployment errors and ensure compliance with Azure standards.