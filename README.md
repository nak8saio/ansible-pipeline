# ansible-pipeline
Learning ansible CI/CD pipeline
## CI/CD

## CI/CD Workflow

Changes are developed on the develop branch.

GitHub Actions performs:
- Ansible syntax check
- Ansible lint
- Ansible dry run

Changes are merged into main through a Pull Request.

This project uses GitLab CI to validate Ansible playbooks.
