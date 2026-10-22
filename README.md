# MZ-UCA Academy Profile and Policy Reader
## Project Objective
This project demonstrates Terraform variables, outputs,
locals, data sources and a managed local file.
## Tools Used
- Terraform
- HashiCorp local provider
- Visual Studio Code
- Terminal
## Resources Managed
- local_file.academy_profile
## Data Sources Used
- data.local_file.academy_policy
## Validation
Document the result of terraform validate.
## Execution
Document the result of terraform plan and terraform apply.
## Testing
Explain how changing the environment variable changed
the generated academy profile.
## Lessons Learned
Managing infrastructure requires handling different types of data elements. In Terraform, variables, outputs, locals, and data sources act as the inputs, outputs, constants, and external queries of your infrastructure configuration:
**Variables (`variable`):** These act as function parameters or input arguments. They allow you to pass dynamic values into your configuration from the outside without hardcoding them, making your infrastructure code reusable across different environments (e.g., dev, staging, prod).
**Outputs (`output`):** These act as return values. They extract and expose specific information about your infrastructure resources after deployment (such as a resource ID or a public IP address) so that they can be printed to the CLI or read by other independent infrastructure stacks.
**Locals (`local`):** These act as private, internal variables or constants. They are used to simplify code by assigning a friendly name to an expression or a combination of strings (like a naming convention). Unlike input variables, their values cannot be overridden from outside the configuration files.
**Data Sources (`data`):** These act as read-only API or database queries. They allow you to fetch and read real-time configuration information from infrastructure that already exists outside of your current Terraform workspace, such as querying an existing VPC ID or retrieving the latest cloud machine image ID.
## Evidence
List the screenshots and files submitted with the project.
