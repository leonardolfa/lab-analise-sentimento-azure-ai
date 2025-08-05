# Primeiros Passos com Azure AI: Transcrição e Tradução de Áudio

Este repositório documenta a minha jornada inicial de estudo com os serviços de inteligência artificial da Microsoft Azure. O projeto se concentra em uma exploração prática e conceitual das ferramentas de fala e de linguagem natural, com o objetivo de entender como a IA pode processar e manipular áudio e texto.

O estudo prático demonstra um fluxo de trabalho simples, mas completo, que envolve a transcrição de fala e a tradução de texto utilizando o [Azure AI Speech Studio](https://ai.azure.com/explore/models/aiservices/Azure-AI-Speech/version/1/registry/azureml-cogsvc/tryout?NewUX=true&Trigger=AutoRedirect_NoSpeechResources#speechtranslation).

---

## Estrutura do Repositório

`audio/`: Contém o arquivo de áudio original utilizado para a transcrição.

`images/`: Pasta com as capturas de tela que documentam as etapas do processo no Azure Speech Studio.

`output/`: Pasta que contém os arquivos de texto e JSON gerados pelo Azure Speech Studio, documentando os resultados da transcrição e tradução.

`README.md`: Este arquivo, que detalha o projeto e o processo de aprendizado.

---

## Exploração Prática: Azure AI Speech Studio
Esta seção descreve o processo de transcrição e tradução que você realizou.

Fonte do Áudio: O arquivo de áudio ([WhatAICanDo.m4a](https://github.com/leonardolfa/lab-analise-sentimento-azure-ai/tree/main/audio)) usado neste estudo foi obtido a partir de um recurso de aprendizado da Microsoft, disponível em: [Explore Speech in Azure AI Foundry portal](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html).

**Fluxo de Trabalho**:

O áudio foi enviado para o Azure AI Speech Studio.

Utilizei a ferramenta de Conversão de Fala em Texto para transcrevê-lo, obtendo o texto original, transcrito em idioma inglês.

Em seguida, usei a ferramenta de Tradução de Fala para traduzir o texto, que também fez a transcrição e realizou a tradução do texto para o idioma português.

**Resultados e Observações**: As ferramentas se mostraram eficazes, fornecendo transcrições e traduções precisas de forma rápida. As capturas de tela na pasta /images mostram a transcrição e a tradução completas.

---

## Exploração Conceitual: Azure AI Language Studio

Embora o plano inicial incluísse a Análise de Sentimento, não foi possível realizar a prática no Azure AI Language Studio devido a uma limitação técnica (falta de tokens de acesso ou credenciais necessárias no momento).

No entanto, a exploração do tema foi feita de forma teórica por meio de duas fontes principais:

* O tutorial da Microsoft Learn, que detalha o processo no portal: Analyze text in Azure AI Foundry portal.

* As aulas do BootCamp em Análise de Dados pela plataforma da [Digital Innovation One](https://www.dio.me), que abordaram o conceito e a aplicação da análise de texto.

O estudo permitiu compreender o conceito da Análise de Sentimento e como ela é aplicada para classificar o humor de um texto.
