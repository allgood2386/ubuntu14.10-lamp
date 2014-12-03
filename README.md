## To run:

``ansible-playbook localsetup.yml --connection=local``

## To add a site add a configuration to localsetup.yml like so and run the previous command.

``- {servername: "site4.dev", documentroot: "/var/www/site4"}``