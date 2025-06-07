# Mini Estação Autônoma de Tratamento e Armazenamento de Água

## Introdução

Este documento descreve a arquitetura de tecnologia desenvolvida para o projeto *"Mini Estação Autônoma de Tratamento e Armazenamento de Água"*, elaborado como parte do desafio proposto pela FIAP no Global Solution.

A arquitetura foi modelada utilizando a ferramenta *ARCHI, com base no framework **TOGAF*, com o objetivo de representar todos os dispositivos, serviços, softwares e camadas de rede envolvidos na solução.

---

## Visão Geral da Solução

A proposta envolve uma estação portátil e inteligente, capaz de tratar e armazenar água, utilizando sensores físicos (pH, turbidez, temperatura, nível), alimentação por energia solar e conectividade IoT.

Os dados captados são enviados por meio de protocolos como *MQTT* e *HTTP/HTTPS* para APIs hospedadas em containers Docker (Java e .NET), processados, armazenados em banco de dados e exibidos a usuários via aplicativo mobile ou dashboard web. Toda a comunicação opera sobre infraestrutura de nuvem (Azure).

---

## Estrutura da Arquitetura de Tecnologia

### Dispositivos e nós de tecnologia
- ESP32 com sensores
- Gateway IoT
- Container Docker: API REST Java
- Container Docker: API REST .NET
- Container Docker: Banco de Dados Oracle
- Dispositivo Mobile (App)
- Dispositivo do Gestor
- Dashboard Web

### Softwares instalados
- API REST Java
- API REST .NET
- Banco de Dados Oracle
- Mobile App
- Dashboard
- Deploy
- Repositório de Código

### Serviços de rede e comunicação
- HTTP/HTTPS (REST)
- MQTT
- Wi-Fi / Rede Móvel
- Internet (Azure)

---

## Conexões Representadas

As ligações entre os elementos foram modeladas de acordo com os relacionamentos do ArchiMate:

- Realization: conecta o software ao dispositivo onde está instalado.
- Serving: indica que um dispositivo fornece um serviço tecnológico (como HTTP ou MQTT).
- Association: representa relações indiretas ou de apoio (como repositórios e ferramentas de deploy).

---

## Ferramentas Utilizadas

- Archi (para modelagem da arquitetura)
- GitHub (armazenamento de código-fonte)
- Docker CLI e Azure CLI (para deploy)
- MQTT e HTTP/HTTPS como serviços de transporte de dados

---

## Objetivo da Modelagem

A modelagem tem como objetivo ilustrar as interações técnicas entre os componentes da solução, incluindo sensores, serviços em nuvem, softwares e dispositivos dos usuários finais. Também serve para validar a viabilidade técnica do projeto, promovendo alinhamento com boas práticas de arquitetura corporativa.
