This playbook is divided into three main sections:

Pre-checks: This section performs checks before any changes are made to the system. It verifies if required packages are installed and if specific directories exist. If any error occurs during pre-checks, it's handled in the rescue section.

System Changes: This section performs the actual changes to the system. You can include tasks like installing packages, configuring services, etc. If any error occurs during system changes, it's handled in the rescue section.

Post-checks: This section performs checks after the changes are made to verify if the system is in the desired state. It checks if services are running and if specific files exist. If any error occurs during post-checks, it's handled in the rescue section.

Feel free to customize this playbook according to your specific requirements by adding or modifying tasks as needed.
