# 📝 Atividades realizadas no dia 01/06/2026 - Grupo 5

## 🚦 Sobre o Projeto
Este repositório contém as atividades realizadas no dia **01/06/2026**, pelo **Grupo 5 (GR5)**. O projeto engloba o planejamento, a simulação lógica e a montagem virtual de um sistema de semáforo inteligente utilizando **Arduino UNO**. 

O sistema principal visa controlar o fluxo de veículos e garantir a travessia segura de pedestres por meio do acionamento de um botão.

---

## 📁 Estrutura do Repositório
O repositório está organizado com os seguintes arquivos essenciais para o entendimento e execução do projeto:

* **`GR5-5w2h.xlsx`**: Planilha de planejamento utilizando a metodologia 5W2H, detalhando as orientações, responsabilidades e custos envolvidos.
* **`GR5-cronograma.xlsx`**: Arquivo de gestão de tempo, definindo as etapas de desenvolvimento e os prazos de entrega dos integrantes do grupo.
* **`GR5-fluxograma.fprg`**: Arquivo executável no software **Flowgorithm** que detalha a lógica estruturada do funcionamento dos semáforos.
* **`GR5-link-tinkercad.txt`**: Documento contendo o link direto para a simulação do circuito de hardware na plataforma **Tinkercad**.
* **`GR5-vídeo-da-confecção`**: Vídeo demonstrativo registrando o processo de produção e/ou o funcionameno do projeto.

---

## ⚙️ Arquitetura e Lógica do Sistema

### 🛠️ 1. Circuito (Tinkercad)

| Componente | Descrição no Circuito |
| :--- | :--- |
| 🎛️ **Placa Arduino Uno** | Central de processamento que gerencia todos os componentes do sistema. |
| 🚗 **Semáforo de Veículos** | Saídas digitais ligadas aos LEDs Verde, Amarelo e Vermelho para os carros. |
| 🚶 **Semáforo de Pedestres** | Saídas digitais ligadas aos LEDs Verde e Vermelho para os pedestres. |
| 🔘 **Push Button (Botão)** | Entrada digital configurada com resistor para detectar a intenção de travessia. |
| 📡 **Sensor Ultrassônico** | Módulo HC-SR04 conectado para leitura de distância e presença de objetos. |

---

### ⚙️ 2. Lógica da Programação (Fluxograma)

| Etapa do Algoritmo | Descrição Lógica |
| :--- | :--- |
| 🎬 **Estado Inicial** | O sinal dos carros inicia aberto (Verde) e o de pedestres fechado (Vermelho)[cite: 2, 3]. |
| 📖 **Leitura do Botão** | O programa entra em prontidão esperando o input `"sim"` ou `"não"` do usuário[cite: 4, 5]. |
| ✅ **Transição (Sim)** | O sinal dos carros muda para Amarelo, depois Vermelho, e libera o Verde dos pedestres[cite: 6, 7]. |
| ❌ **Transição (Não)** | Nenhuma mudança é acionada; o sistema mantém o estado inicial seguro[cite: 16, 30, 31]. |
| ⚠️ **Tratamento de Erros** | Loops de repetição (`while`) barram respostas inválidas até que o input correto seja digitado[cite: 8, 9, 10]. |

---
**👥 Integrantes do grupo**
- Danielli Gonçalves Martins
- Gabriel Martins Mandelli
- Thiago Marcelino Vieira
- Vinícius dos Santos Ribeiro Antunes
- Vitor Rodrigues Santos
