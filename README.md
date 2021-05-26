# Ansible work

working folder of Ansible cfg, playbooks, and experimentation

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install Ansible.  
Here is the docs from the source [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-with-pip)


## Usage
I have used my Macbook as the control node and Digital Oceans ubuntu droplets as managed nodes  
In hosts add your managed nodes and test with  
```bash
ansible -m ping all
```  
You should receive an output  
  
xxxxxxxxxxxxxx | SUCCESS => {
    "changed": false,
    "ping": "pong"
}



## Contributing
Feel free to use any and all code for the basis of your exploration

## License
[MIT](https://choosealicense.com/licenses/mit/)
