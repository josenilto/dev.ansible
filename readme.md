### ℹ️ Ansible

Provisionamento de software de código aberto, gerenciamento de configuração e implantação de aplicativo que habilita a infraestrutura como código. Cole seu YAML e clique em "Ir" - nós diremos se é válido ou não e forneceremos uma versão UTF-8 limpa e agradável dele. Otimizado para Ruby.

----

### ➡️ Exemplo:

```MD
- hosts: all
  tasks:
    - name: 'Instala pacotes de dependencia do sistema operacional'
      apt:
        name: "{{ item }}" 
        state: lastest
      become: yes
      with_items:
        - php5
        - apache2
        - libapache2-mod-php5
        - php5-gd
        - libssh2-php
        - php5-mcrypt
        - mysql-server-5.6
        - python-mysqldb
        - php5-mysql
```

----

### ➡️ Links:

[<img title="Ansible" align="left" alt="josenilto | Twitter" width="28px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/ansible.svg" />][ansible]
[<img title="YamLint" align="left" alt="josenilto | Twitter" width="28px" src="https://raw.githubusercontent.com/iconic/open-iconic/master/svg/globe.svg" />][website]

[Ansible]: https://docs.ansible.com/ansible/latest/index.html 
[Website]: http://www.yamllint.com 
