# Estudo Pessoal da Documentação do Gemini

Este repositório contém um estudo pessoal baseado na documentação oficial do Gemini API da Google para geração de texto. O objetivo é explorar diversas funcionalidades da API através de exemplos práticos em um notebook IPython.

## Objetivo

O objetivo deste estudo é aprender a usar efetivamente o Gemini API para diferentes tarefas de geração de texto, incluindo respostas a prompts simples, geração de múltiplas respostas candidatas, integração com imagens para geração de texto visual, e interação em tempo real através de chat.

## Estrutura do Estudo

O notebook está estruturado em diferentes estudos, cada um focado em uma funcionalidade específica da API. Abaixo está um resumo de cada etapa do estudo:

### 1. Gerando Respostas

Nesta etapa, configuramos o ambiente e utilizamos o modelo Gemini 1.0 Pro para gerar uma resposta a partir de um prompt simples. Passos incluem importação de bibliotecas, configuração da chave de API, definição do modelo e do prompt, e exibição do conteúdo da resposta.

### 2. Candidates: Gerando Várias Respostas

Demonstração de como o Gemini pode gerar várias respostas candidatas para um único comando. Exploração das possíveis respostas geradas pelo modelo e métodos para seleção da resposta mais adequada.

### 3. Gerando Texto com Imagens e Texto

Exemplo prático de como integrar imagens como entrada para o modelo Gemini 1.5 e gerar texto com base nas informações visuais e textuais fornecidas. Inclui o processo de download e utilização de uma imagem, e a geração de texto correspondente.

### 4. Conversas por Chat

Utilização do Gemini para criar uma sessão de chat interativa. Mostra como iniciar uma conversa, enviar mensagens para o modelo e receber respostas em tempo real, gerenciando o histórico da conversa.

## Como Usar

Cada estudo é apresentado em um notebook separado dentro deste repositório. Antes de executar qualquer código, siga as instruções de instalação e configuração da chave de API conforme descrito no início de cada notebook.

## Documentação Adicional

Para mais detalhes sobre a API Gemini, consulte a [documentação oficial](https://ai.google.dev/gemini-api/docs/get-started/tutorial?hl=pt-br&lang=python).
