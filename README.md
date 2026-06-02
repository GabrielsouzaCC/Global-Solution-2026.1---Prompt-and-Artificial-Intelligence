# Mission Control AI - [Sistema de monitoramento de missão espacial]

Sistema inteligente de monitoramento para o controle básico de uma missão espacial experimental — **GS 2026.1 / FIAP — Prompt and Artificial Intelligence**.

**Integrantes:**
- GABRIEL SOUZA  — RM: 571583
- RAFAEL SÁ — RM: 569223
- JOÃO MELO — RM: 571116 

---

## O que o projeto faz

Sistema de monitoramento de missão espacial feito em Python (Google Colab). Ele gera dados simulados de telemetria (temperatura, energia/bateria, geração solar e sinal de comunicação), aplica uma lógica de regras que dispara **alertas automáticos** e **ações automatizadas** em situações críticas, e usa o modelo **Llama 3.2 (1B) via Ollama** para analisar o estado da missão e recomendar a ação prioritária com contexto espacial. Também faz uma **previsão simples** da autonomia da bateria a partir da tendência dos dados.

---

## Demonstração

> Substitua pelos seus prints reais (pelo menos 2): um com a missão em estado normal e outro com um alerta crítico + resposta da IA. Salve as imagens na pasta `assets/`.

![Dados da missão - estado normal](assets/dados_missao.png)

![Alerta crítico + análise da IA](assets/alerta_critico.png)

---

## Como executar

Abra o notebook no Google Colab:

[Acessar Notebook]((https://colab.research.google.com/drive/1OlC3Y9S235mHM_fUfnjQ5WrPy73KIxMx?usp=drive_link))

Execute as células **em ordem, de cima para baixo**. O Ollama e o modelo Llama 3.2 1B são instalados automaticamente na primeira célula — não é preciso conta nem chave de API.

Ordem das células:
1. Instalação do Ollama e do modelo
2. Configuração da missão
3. a 6. Funções (simulação, alertas/decisão, IA, painel)
7. Monitoramento automático
8. Demonstração de cenário crítico
9. Previsão de autonomia da bateria
10. Chatbot opcional

---

## Tecnologias utilizadas

- Python 3
- Google Colab
- Ollama
- Llama 3.2 (1B) — modelo de linguagem
- Biblioteca `ollama` (Python)

---

## Vídeo de Demonstração

[Assistir ao vídeo](https://link-do-video.com)
