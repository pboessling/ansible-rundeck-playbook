# ansible-rundeck-playbook

Ansible playbook to setup Rundeck.

## Requirements

- CentOS/RHEL 7.4
- Ansible 2.5

For local testing:
- Vagrant
- VirtualBox

## Local Testing

In the project root folder run the following command:
```
$ vagrant up
```

Open the following URL in a browser: [http://192.168.60.4:4440/]()

## TODO

- Install Ansible
- Install Rundeck-Ansible-Plugin - https://github.com/Batix/rundeck-ansible-plugin
- Configure vHost for Rundeck
- Configure TLS
- Install MariaDB
- Configure Rundeck to use MariaDB instead of H2 
- Install OpenLDAP
- Configure LDAP for user authentication

## Resources

- http://rundeck.org/docs/administration/installation.html
- http://meinit.nl/rundeck-centos-behind-apache-httpd-proxy

## License

[MIT](LICENSE)

## Author Information

Created by [Philippe Bößling](https://www.gihub.com/pboessling).