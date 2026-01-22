📌 Assistente de Voz Multi-Idiomas com Whisper e ChatGPT

Este projeto implementa um assistente de voz inteligente, capaz de ouvir, compreender, processar e responder ao usuário por meio de áudio, utilizando modelos modernos de Reconhecimento de Fala (ASR), Inteligência Artificial Conversacional e Síntese de Voz (TTS).

O fluxo completo ocorre de forma automatizada, permitindo uma experiência próxima a um assistente virtual real, com suporte a múltiplos idiomas.

🚀 Visão Geral do Funcionamento

O assistente executa as seguintes etapas:

Captação de áudio do usuário
O áudio é gravado diretamente no navegador (via JavaScript) e disponibilizado ao Python em tempo real, sem necessidade de upload manual de arquivos.

Transcrição de fala para texto (Speech-to-Text)
Utiliza o modelo Whisper (OpenAI) para converter o áudio gravado em texto, com alta precisão e suporte a diversos idiomas.

Processamento da mensagem com IA Conversacional
O texto transcrito é enviado à API do ChatGPT, que interpreta o conteúdo e gera uma resposta contextual e inteligente.

Conversão da resposta em áudio (Text-to-Speech)
A resposta do ChatGPT é sintetizada em voz utilizando gTTS, permitindo que o assistente “fale” com o usuário.

Reprodução automática da resposta
O áudio gerado é reproduzido diretamente no ambiente de execução (Google Colab).

🧠 Tecnologias Utilizadas

Python

JavaScript (MediaStream Recording API) – gravação de áudio no navegador

Whisper (OpenAI) – reconhecimento de fala (Speech-to-Text)

ChatGPT (OpenAI API) – processamento de linguagem natural

gTTS (Google Text-to-Speech) – síntese de voz

Google Colab – ambiente de execução

🌍 Suporte a Múltiplos Idiomas

O idioma do assistente pode ser configurado facilmente por meio de uma variável, permitindo transcrição e resposta em diferentes línguas, conforme suportado pelo Whisper e pelo gTTS.

🎯 Objetivo do Projeto

Este projeto tem como objetivo servir como base educacional e experimental para:

Assistentes virtuais por voz

Sistemas conversacionais com IA

Automação de atendimento

Estudos em IA aplicada (ASR, NLP e TTS)

Prototipação rápida de interfaces de voz

⚠️ Observações Importantes

É necessário possuir uma API Key da OpenAI para uso do ChatGPT.

O projeto foi desenvolvido para execução no Google Colab, podendo ser adaptado para outros ambientes.

Custos de API podem ser gerados conforme o uso.

📄 Licença

Este projeto pode ser utilizado para fins educacionais e experimentais. Verifique as licenças individuais das bibliotecas utilizadas, especialmente as relacionadas à OpenAI.
