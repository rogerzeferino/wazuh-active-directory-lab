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

## ✅ Funcionalidades Implementadas

- [x] Ambiente virtualizado no Proxmox
- [x] Firewall e segmentação de rede com pfSense
- [x] Active Directory com Windows Server 2022
- [x] Auditoria de eventos de segurança no AD
- [x] Coleta de eventos do Windows pelo Wazuh Agent
- [x] Detecção de falhas de autenticação (Event ID 4625)
- [x] Visualização de alertas no Wazuh Dashboard
- [x] Integração inicial do Wazuh com Grafana
- [x] Criação de dashboards básicos para monitoramento
