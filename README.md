# Ansible role for Python 3 
Ansible role for Python 3

## What's inside?
- Python 3.x
- Additional modules: `pexpect`
- Symlink `/usr/bin/python` > `/usr/bin/python3`
   
## Tested on

## Installation
1. Navigate to Ansible's roles folder
2. Add the repo to git modules
    ```
    git submodule add https://github.com/budnerp/ansible_role_python3.git ansible_role_python3
    ```
3. Add the role to Ansible's playbook file
    ```    
    roles:
    [...]
        - ansible_role_python3
    [...]
    ```

## Other links

## TO DO
-[ ] add dependencies

## License
Copyright (c) We Are Interactive under the MIT license.