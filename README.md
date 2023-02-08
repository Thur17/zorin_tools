# Ferramentas da estação de trabalho

Este repositório contém scripts para automatizar e acelerar o fluxo de trabalho e preparação para minha máquina.

> **_Isenção de responsabilidade_**:
> Esses scripts são relacionados ao Ubuntu com a versão principal 18, para outras distribuições você precisará adaptá-lo
___

## Preparar estação de trabalho

> Leia o arquivo `zorin.yml` antes de se inscrever e certifique-se de entender tudo o que será feito.

1. Instale o Ansible
```bash
sudo apt update && sudo apt install ansible unzip git -y
```
2. Clone este repositório
```bash
git clone https://github.com/Thur17/zorin_tools.git
```

3. Aplique a configuração
```bash
ansible-playbook tools/zorin.yml --ask-become-pass
```
>Digite sua senha quando solicitado a dar permissões de root para algumas ações.
___

# Licença
GPLv3

# Informação sobre o autor
Criado por [Caio Delgado](https://linktr.ee/caiodelgadonew)

Contribuições são mais que bem-vindas!
