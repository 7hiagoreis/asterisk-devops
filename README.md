# asterisk-devops
Projeto de laboratório focado na automação, contêiner e gerenciamento do Asterisk PBX utilizando Debian 13 e práticas DevOps.


# Asterisk DevOps

Este repositório é um ambiente de laboratório prático focado na modernização e automação do **Asterisk** utilizando o **Debian 13 (Trixie)** como sistema operacional base. 

O objetivo é estudar e aplicar conceitos de DevOps (como conteinerização, automação de infraestrutura e gerenciamento de arquivos de configuração) no ecossistema de telefonia IP (VoIP).

## Tecnologias Principais

*   **Asterisk:** Motor de comunicação Open Source para gerenciamento de ramais.
*   **Debian 13 (Trixie):** Sistema operacional base do projeto.
*   **Docker & Docker Compose:** Para isolar o Asterisk e facilitar os testes locais.

## Estrutura do Repositório

```text
asterisk-devops/
├── asterisk/               # Configurações de telefonia (pjsip.conf, extensions.conf)
├── iac/                    # Scripts de Infraestrutura como Código (Ansible/Terraform)
├── scripts/                # Scripts utilitários de suporte
├── doc/                    # Documentação técnica e anotações de estudo
├── Dockerfile              # Construção da imagem do Asterisk no Debian 13
└── docker-compose.yml      # Orquestração do container do Asterisk
```	
