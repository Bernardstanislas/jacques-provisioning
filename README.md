Provisioning for the Jacques server.

# Installation

- `ansible-galaxy install -r requirements.yml`
- `ansible-playbook -i le-noyau --ask-become-pass prepare.yml`

# Usage

- `ansible-playbook -i le-noyau --ask-become-pass configure.yml`
