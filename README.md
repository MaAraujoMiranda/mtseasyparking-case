# MTS Easy Parking — Case

Sistema de estacionamento com foco em **operação confiável** no dia a dia (entrada/saída, tarifação e caixa) + **API** para serviços e integrações.

**Status:** fase final de testes para produção  
**Site:** https://mtseasyparking.com.br

---

## Visão geral

O MTS Easy Parking foi pensado para reduzir falhas na operação e dar previsibilidade no atendimento:
- Fluxo claro de **entrada → permanência → saída**
- **Tarifação** consistente e configurável
- **Caixa** com rastreabilidade de movimentações
- **Relatórios operacionais** para acompanhamento
- **API** para integração/serviços de apoio (camada central)

---

## Componentes deste case

### 1) PDV (Desktop)
Aplicação desktop para operação do estacionamento.

**Tecnologias**
- C# • WPF • .NET 8
- Banco de dados: MySQL

**Principais módulos**
- **Entrada e saída** de veículos
- **Tarifação** (regras e parâmetros)
- **Caixa** (movimentações e fechamento)
- **Relatórios** (operação/caixa)

---

### 2) API (Serviços / Integrações)
Serviço REST usado como base para integrações e funcionalidades do ecossistema.

**Tecnologias**
- Node.js + Express
- Banco de dados: MySQL

**Funções principais**
- Serviços de apoio ao PDV
- Base para integrações e automações
- Camada central para validações e operações relacionadas ao sistema

> Observação: este repositório público é uma vitrine (sem código). Detalhes internos ficam em repositório privado.

---

## Screenshots


![Landing](screenshots/01-landing.png)
![PDV - Visão geral](screenshots/02-pdv-dashboard.png)
![PDV - Entrada](screenshots/03-pdv-entrada.png)
![PDV - Saída / Tarifação](screenshots/04-pdv-saida-tarifacao.png)
![PDV - Caixa](screenshots/05-pdv-caixa.png)
![Relatórios](screenshots/06-relatorios.png)
![API](screenshots/07-api-swagger.png)

---

## Observações
- Este repositório é **apenas vitrine**: descrição + arquitetura de alto nível + screenshots.
- Código e regras de negócio ficam em repositórios privados.
- Posso apresentar uma **demo guiada** quando necessário.

---

## Autor
Mateus de Araújo Miranda  
LinkedIn: https://www.linkedin.com/in/matheusaraujotecnicotiemanutencao
