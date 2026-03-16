# 🚁 AiAgent — Drone de Entrega Inteligente

Trabalho acadêmico desenvolvido na **ULBRA** que implementa um agente inteligente baseado em estados, simulando o comportamento de um drone de entrega em Python.

---

## 📋 Sobre o Projeto

O projeto modela um **agente autônomo** seguindo os conceitos de Inteligência Artificial clássica: o drone percebe o ambiente por meio de sensores, mantém um estado interno e executa ações conforme as transições definidas entre estados (ex: em espera, carregando, em rota, entregando, retornando).

O objetivo é demonstrar na prática a arquitetura de um agente reativo baseado em estados, aplicado a um cenário de logística de entregas.

---

## ⚙️ Funcionalidades

- Modelagem de estados do drone (ex: ocioso, em rota, entregando, retornando à base)
- Transições de estado controladas por condições do ambiente
- Ciclo agente: **percepção → estado → ação**
- Simulação em terminal sem dependências externas

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| Python 3.x | Linguagem principal |
| Estruturas nativas (`class`, `dict`, `enum`) | Modelagem de estados e transições |

---

## 🚀 Como Executar

**Pré-requisito:** Python 3.8+

```bash
# Clone o repositório
git clone https://github.com/ArthurSouzaDev/AiAgent.git
cd AiAgent

# Execute a simulação
python drone_de_entrega.py
```

---

## 📁 Estrutura

```
AiAgent/
└── drone_de_entrega.py   # Agente e lógica de estados
```

---

## 📚 Contexto Acadêmico

Projeto desenvolvido para a disciplina de **Inteligência Artificial** na Universidade Luterana do Brasil (ULBRA), com foco em agentes inteligentes e modelagem de comportamento baseado em estados.

---

> Desenvolvido por [ArthurSouzaDev](https://github.com/ArthurSouzaDev) por [Lucas Nascimento](https://github.com/lukasnascky) e por [David chaves](https://github.com/davidchaves3)
