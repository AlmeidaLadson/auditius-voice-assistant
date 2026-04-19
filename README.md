# AudITus — Assistente de Voz para Suporte de TI

Assistente de voz inteligente desenvolvido como projeto de portfólio no
Bootcamp Python AI Backend Developer da DIO.

## Sobre o projeto

O AudITus capta perguntas por áudio, transcreve com Whisper, processa
com LLaMA e responde em voz via gTTS, com foco em suporte técnico de TI.

## Fluxo de funcionamento

Voz → Whisper (transcrição) → LLaMA (resposta) → gTTS (áudio)

## Tecnologias utilizadas

- Whisper Large V3 — transcrição de voz para texto
- LLaMA 3.1 8B Instant — geração de resposta via Groq API
- Google Text-to-Speech (gTTS) — síntese de voz
- Python 3 + Google Colab

## Como executar

1. Abra o notebook `AudITus_VoiceAssistant.ipynb` no Google Colab
2. Configure a chave `AUDITIUS_GROQ_TOKEN` nos Secrets do Colab
3. Execute as células em ordem
4. Permita acesso ao microfone quando solicitado pelo navegador

## Pré-requisitos

Conta gratuita na [Groq](https://console.groq.com) para obter a API key.
