# 🐧 Linux Essentials & Hardening - Plano de Estudos

## 🎯 Objetivos

- **Domine o terminal Linux** e os comandos essenciais para administração diária de servidores em nuvem.
- **Compreenda a estrutura do sistema de arquivos** (_File System Hierarchy_) para navegar e localizar configurações e logs.
- **Aplique conceitos de Hardening e Segurança**, gerenciando permissões de arquivos (`chmod`/`chown`) e o princípio do menor privilégio (_Least Privilege_).
- **Gerencie processos, usuários e permissões administrativas (`sudo`)** para auditoria e controle de acesso.

---

### 📌 Legenda de Status

- ❌ **Não Iniciado**
- ⏳ **Em Andamento**
- ✅ **Concluído**

## 📅 Progresso do Curso

| Aula no Plano | Tema do Módulo                                                   | Vídeo Exato na Playlist Bóson                       | Status |             Anotações              |
| :-----------: | :--------------------------------------------------------------- | :-------------------------------------------------- | :----: | :--------------------------------: |
|    **01**     | Instalação do Linux Debian (Servidor em VM)                      | **Aula 02** - Instalação do Linux Debian            |   ✅   | [Ver Resumo](./resumos/aula-01.md) |
|    **02**     | Estrutura de Diretórios e Sistema de Arquivos                    | **Aula 70** - Estrutura do Sistema de Arquivos      |   ❌   | [Ver Resumo](./resumos/aula-02.md) |
|    **03**     | Comandos Básicos de Navegação (`ls`, `cd`, `pwd`, `clear`)       | **Aula 04** (Comando ls) e **Aula 17** (Básicos 01) |   ❌   | [Ver Resumo](./resumos/aula-03.md) |
|    **04**     | Manipulação de Arquivos e Diretórios (`mkdir`, `cp`, `rm`)       | **Aula 23** (cp, rm) e **Aula 24** (mkdir, rmdir)   |   ❌   | [Ver Resumo](./resumos/aula-04.md) |
|    **05**     | Leitura de Arquivos e Logs (`head`, `tail`, `cat`)               | **Aula 19** (head) e **Aula 21** (tail, tac, wc)    |   ❌   | [Ver Resumo](./resumos/aula-05.md) |
|    **06**     | Permissões de Acesso a Arquivos e Pastas                         | **Aula 05** - Permissões de Acesso no Terminal      |   ❌   | [Ver Resumo](./resumos/aula-06.md) |
|    **07**     | Gerenciamento de Permissões com `chmod`                          | **Aula 06** - Comando chmod                         |   ❌   | [Ver Resumo](./resumos/aula-07.md) |
|    **08**     | Donos e Grupos de Arquivos (`chown`, `chgrp`)                    | **Aula 07** - Comandos chgrp e chown                |   ❌   | [Ver Resumo](./resumos/aula-08.md) |
|    **09**     | Gestão de Usuários e Identidade (`/etc/passwd`, `/etc/shadow`)   | **Aula 33** (/etc/passwd) e **Aula 35** (shadow)    |   ❌   | [Ver Resumo](./resumos/aula-09.md) |
|    **10**     | Criação e Alteração de Usuários (`useradd`, `passwd`, `usermod`) | **Aula 36** (useradd) e **Aula 39** (usermod)       |   ❌   | [Ver Resumo](./resumos/aula-10.md) |
|    **11**     | Gerenciamento de Processos e Sinais (`kill`, `killall`)          | **Aula 43** - Processos, Sinais, kill e killall     |   ❌   | [Ver Resumo](./resumos/aula-11.md) |
|    **12**     | Monitoramento do Sistema e Desempenho (`top`, `uptime`)          | **Aula 28** - Comandos top e uptime                 |   ❌   | [Ver Resumo](./resumos/aula-12.md) |
|    **13**     | Filtros e Busca de Texto com Expressões Regulares (`grep`)       | **Aula 56** - Comando grep e Filtragem              |   ❌   | [Ver Resumo](./resumos/aula-13.md) |

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=GNU%20Bash&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Debian](https://img.shields.io/badge/Debian-A81D24?style=for-the-badge&logo=debian&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)

- **Sistema Operacional:** Linux (Distribuições Debian/Ubuntu)
- **Interface:** Shell / Terminal Bash
- **Conceitos Chave:** Hardening, Controle de Acesso (RBAC), Permissões POSIX (`chmod`, `chown`), Gerenciamento de Processos, Filtros de Texto (`grep`), Auditoria de Usuários e Segurança do Sistema de Arquivos (`FHS`).

---

## 🔗 Fonte do Conteúdo

- **Bóson Treinamentos** [Curso de Linux (YouTube)](https://www.youtube.com/watch?v=UsHiWIgxj2M&list=PLUO_OuMzpk6l5VdncktFOeTV77mgUeD_B)

## 🤝 Agradecimentos

Agradecimento especial ao **Edson Bezerra** (_Manager, LATAM Cyber Security Infrastructure Services - DXC Technology_) pela mentoria, orientações estratégicas e incentivo na estruturação deste plano de estudos e documentação.
