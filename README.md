# Ansible WordPress Deployment

This repository contains Ansible code for automating the deployment of a WordPress website with MariaDB, Apache, and PHP. The deployment process is orchestrated using Ansible playbooks, and the repository includes various configuration files to make the deployment flexible and customizable.

## Table of Contents

- [Introduction](#introduction)
- [Files and Structure](#files-and-structure)
- [Usage](#usage)
- [Prerequisites](#prerequisites)
- [How to Run](#how-to-run)
- [Customization](#customization)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This Ansible playbook simplifies the deployment of a WordPress site by automating the setup of MariaDB for the database, Apache as the web server, and PHP for server-side scripting. The playbook uses Ansible roles and variables to offer a straightforward and adaptable deployment process.

## Files and Structure

- **ansible-variable.yml**: Customize deployment settings through Ansible variables.
- **ansible-playbook.yml**: Main Ansible playbook orchestrating the deployment process.
- **ansible-inventory.ini**: Ansible inventory file specifying target hosts.
- **ansible-wordpress-mariadb.yml**: YAML file containing Ansible code for deploying WordPress with MariaDB, Apache, and PHP.

## Usage

### Prerequisites

Ensure the following prerequisites are installed:

- Ansible

### How to Run

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/ansible-wordpress-mariadb.git
    ```

2. Navigate to the repository:

    ```bash
    cd ansible-wordpress-mariadb
    ```

3. Customize variables in `ansible-variable.yml` as needed.

4. Run the Ansible playbook:

    ```bash
    ansible-playbook -i ansible-inventory.ini ansible-playbook.yml
    ```

## Customization

Adapt the deployment to your needs by adjusting variables in the `ansible-variable.yml` file. Detailed explanations for each variable can be found in the file.

## Troubleshooting

If issues arise during deployment, consult the [Troubleshooting](TROUBLESHOOTING.md) guide for common problems and solutions.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests. Review the [Contribution Guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the [MIT License](LICENSE).
