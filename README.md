# Pedro Henrique Evers

![Terminal de Pedro em Blumenau. Suporte N2 Fiscal e estudos em DevOps e Cloud com AWS, Terraform, Kubernetes e CI/CD.](assets/terminal.svg)

Na **Linx (TOTVS)**, investigo incidentes fiscais com análise de logs, consultas SQL em PostgreSQL e leitura de XMLs de NF-e e NFC-e. Também automatizo tarefas repetitivas do suporte. Curso **Análise e Desenvolvimento de Sistemas na Uniasselvi** e uso Linux e Git nos meus laboratórios de infraestrutura como código, automação de deploy e observabilidade.

## Projetos

- **[SimulaCloud](https://github.com/PHEvers/SimulaCloud)** — projeto de simulados para certificações em nuvem, começando pela AWS Cloud Practitioner.
- **[ChatProbe](https://github.com/PHEvers/ChatProbe)** — projeto em fase inicial para automatizar testes de assistentes virtuais pela interface web e registrar evidências de cada cenário.

## Diário de laboratório

Registro minha formação em DevOps no repositório do [+Dev2Blu 2026](https://github.com/PHEvers/-Dev2Blu-2026).

### AWS com Terraform · EC2 e balanceamento de carga

**Objetivo** · Distribuir tráfego entre dois servidores web.  
**O que fiz** · Provisionei duas instâncias EC2 com Nginx em zonas de disponibilidade diferentes, atrás de um Application Load Balancer.  
**O que pratiquei** · Provisionamento de redes e instâncias na AWS e distribuição de tráfego entre servidores.

### Terraform e Ansible · Configuração de servidores

**Objetivo** · Repetir a configuração de dois servidores sem instalar o Nginx manualmente.  
**O que fiz** · Provisionei duas instâncias EC2 com Terraform e usei um playbook do Ansible para instalar e iniciar o Nginx nas duas.  
**O que pratiquei** · Separar o provisionamento da infraestrutura da configuração dos servidores.

### Kubernetes na AWS · Control plane e workers

**Objetivo** · Montar um cluster Kubernetes em instâncias EC2.  
**O que fiz** · Provisionei com Terraform a rede e as instâncias de um control plane e dois workers em sub-redes separadas.  
**O que pratiquei** · Organizar a topologia do cluster e a comunicação entre os nós.

### GitLab CI/CD · Pipeline .NET

**Objetivo** · Levar uma API .NET do build ao deploy em dois ambientes.  
**O que fiz** · Configurei o build da imagem Docker e o deploy pelo GitLab CI/CD em clusters kind separados para staging e produção.  
**O que pratiquei** · Usar contextos Kubernetes por ambiente e validar o rollout após a atualização da imagem.

## Contato

[LinkedIn](https://www.linkedin.com/in/pedro-henrique-evers-903a3ab3/) · [E-mail](mailto:pedroevers@gmail.com)
