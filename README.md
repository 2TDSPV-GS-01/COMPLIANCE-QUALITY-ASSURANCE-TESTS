# COMPLIANCE-QUALITY-ASSURANCE-TESTS
# 💧 Mini Estação Autônoma de Tratamento e Armazenamento de Água

Um sistema portátil, inteligente e sustentável para tratar, armazenar e monitorar a qualidade da água em cenários críticos — como desastres naturais ou comunidades sem saneamento básico.

---

## 🧠 Descrição do Projeto

O projeto foi desenvolvido como parte da **Global Solution 2025/1 da FIAP**, com o objetivo de propor uma solução tecnológica e inovadora para enfrentar **eventos extremos da natureza**.

A solução combina:
- Engenharia física/química para tratamento de água,
- Dispositivos IoT para monitoramento em tempo real,
- Aplicações Web/Mobile e APIs para gestão de dados,
- Fontes de energia sustentável.

---

## 🎯 Público-Alvo

- Regiões afetadas por enchentes e desastres naturais;
- Comunidades rurais e favelas sem acesso à água tratada;
- Abrigos emergenciais ou temporários;
- Órgãos públicos e ONGs de ajuda humanitária.

---

## 🌟 Funcionalidades

- ✅ Filtragem física com areia, brita e carvão ativado
- ✅ Desinfecção biológica com luz UV-C
- ✅ Monitoramento via sensores (pH, turbidez, temperatura, nível de água)
- ✅ Visualização de dados em dashboard e app mobile
- ✅ Abastecimento por energia solar (com bateria)
- ✅ Comunicação via ESP32 com MQTT/HTTP
- ✅ API REST para centralização e histórico dos dados
- ✅ Instalação rápida, sem necessidade de bomba ou infraestrutura elétrica

---

## 🛠️ Tecnologias Utilizadas

| Categoria                  | Ferramentas / Tecnologias               |
|---------------------------|-----------------------------------------|
| Backend                   | Java Spring Boot ou .NET API REST       |
| Banco de Dados            | Oracle / PostgreSQL / MySQL (container) |
| IoT                      | ESP32, sensores de pH, turbidez, nível  |
| Dashboard                 | Node-RED, Thinger.io                    |
| App Mobile                | React Native                            |
| Deploy & DevOps           | Docker, Docker Compose, GitHub Actions  |
| Arquitetura               | TOGAF (modelado no ARCHI)               |

---

## 🧪 Arquitetura da Solução

Modelada segundo o framework **TOGAF**, utilizando a ferramenta **ARCHI**, contemplando:

- Visão de arquitetura: stakeholders, objetivos e requisitos;
- Arquitetura de negócio: processos, funções e atores;
- Arquitetura de sistemas: APIs, camadas de serviço e dados;
- Arquitetura de tecnologia: rede, dispositivos, servidores e softwares.

> 📁 Arquivos .archi e .pdf disponíveis na pasta `arquitetura/`.

---

## 💰 Viabilidade Financeira

Estimativa de custo por unidade:

| Item                                  | Faixa de Preço (R$) |
|---------------------------------------|----------------------|
| Reservatórios plásticos (2x 40L)      | 100 – 150            |
| Filtro (areia, carvão, brita)         | 30 – 50              |
| Luz UV-C                              | 40 – 80              |
| Painel solar + bateria                | 100 – 200            |
| ESP32 + sensores                      | 110 – 170            |
| Materiais elétricos                   | 30 – 50              |

**Total aproximado:** R$ 400 a R$ 700

---

## 📈 Impacto Esperado

- Redução do uso de galões de água em abrigos emergenciais;
- Maior autonomia para comunidades carentes;
- Monitoramento remoto de qualidade da água;
- Educação ambiental e uso em escolas e ONGs.

---
