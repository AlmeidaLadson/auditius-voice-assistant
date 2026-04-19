# AudITus — Assistente de Voz para Suporte de TI

Projeto desenvolvido durante o Bootcamp Python AI Backend Developer na DIO.

##  O que é o AudITus?
Assistente de voz inteligente que capta perguntas por áudio, transcreve com
Whisper, processa com LLaMA e responde em voz via gTTS, tudo focado em
suporte técnico de TI.

##  Fluxo de funcionamento
Voz → Whisper (transcrição) → LLaMA (resposta) → gTTS (voz)

##  Tecnologias utilizadas
- Whisper Large V3 (Groq)
- LLaMA 3 8B (Groq)
- Google Text-to-Speech (gTTS)
- Python 3 + Google Colab

##  Como executar
1. Abra o notebook no Google Colab
2. Configure a chave `AUDITIUS_GROQ_TOKEN` nos Secrets do Colab
3. Execute as células em ordem
4. Permita acesso ao microfone quando solicitado
