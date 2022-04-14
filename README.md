# Ansible ARA quickstart 

Ceci est un bout du  Ansible Ultimate Edition :

* dépôt GIT :  https://github.com/wescale/ansible-ultimate-edition 
* Web doc : https://ansible-ultimate-edition.readthedocs.io/en/latest/



# Pré-requis

Vous avez besoin de direnv et de Pyhton, les prérequis sont détaillés ici : https://ansible-ultimate-edition.readthedocs.io/en/latest/exercises/basics/ex00-install.html

Sinon :

```bash
$ sudo apt update 
$ sudo apt install direnv python3 python3-pip python3-venv -y
$ echo 'eval "$(direnv hook bash)"' >> ~/.bashrc
$ source ~/.bashrc
```


# How to

Une fois le projet cloné, allez dedans et activer direnv :

```bash
$ direnv allow .
```

Ensuite installez le nécessaire :

```bash
$ make env
```
