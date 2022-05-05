```sh
sudo apt install python3-pip
pip3 install ansible
export PATH="$PATH:$HOME/.local/bin"
ansible-playbook main.yml --ask-become-pass
```
