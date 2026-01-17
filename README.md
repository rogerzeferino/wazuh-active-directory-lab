# wazuh-active-directory-lab
Laboratório de Segurança com Wazuh, Active Directory e Grafana em Proxmox

# 🔐 Lab de Segurança com Wazuh, Active Directory e Grafana

## 📌 Visão Geral
Este projeto consiste em um laboratório prático de Segurança da Informação com foco em monitoramento, auditoria e análise de eventos de autenticação em ambiente Windows, utilizando o Wazuh integrado ao Active Directory e visualizações no Grafana.

Todo o ambiente está virtualizado no Proxmox e segmentado em rede através do pfSense.

## 🏗️ Arquitetura do Laboratório

O laboratório foi construído em ambiente totalmente virtualizado utilizando Proxmox, com segmentação de rede realizada através do pfSense.

### Componentes do ambiente:
- **Proxmox VE** como host de virtualização
- **pfSense** atuando como firewall e gateway da rede
- **Windows Server 2022 (DC01)**  
  - Active Directory  
  - DNS  
  - Auditoria de eventos de segurança
- **Ubuntu Server**  
  - Wazuh Manager  
  - Wazuh Indexer  
  - Wazuh Dashboard  
  - Grafana
