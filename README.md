#Prepare

Create python venv and activate it
```sh
python3 -m venv ansible

source path_to_venv/bin/activate
```

Install ansible 2.10 and python modules

```sh
pip3 install -r requirements.txt
```

Correct stack.yml to match your requirements

Launch playbook

```sh
ansible-playbook -e username=nebulauser -e password=nebulapass -vvv -e server=http://xx.xx.xx.xx:2633/RPC2 provision.yml
```
