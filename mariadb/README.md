# <h1>Vagrant Mariadb</h1>

## <h2>Author: Diego de Sena Bastos</h2>
## <a href="https://www.linkedin.com/in/diego-sena-76ba4896/">Linkedin</a>

## About <a name = "about"></a>

This repository create a vagrant box with MariaDB and Configure the remote acess.

### Prerequisites

1. Internet acess

### Installing

1. Inside the folder run ``` vagrant up ```

### Custom configuration

1. Change box ip = Change the ip on ./Vagrant file section: 
    *    mariadb.vm.network "public_network", ip: "192.168.15.50"
2. Change ansible playbook setting, go to ./configs/playbook.yml, in section:
    *   vars</br>
    Exemplo</br>
        db_password: 123Mud@r </br>
        db_user: admin </br>
        db_name: curso </br>