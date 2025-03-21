# Avanade.AI-Search

 Projeto de Reconhecimento de Texto (OCR) com Azure OpenAI e Content Filters

## Introdução
Neste projeto, desenvolvi uma aplicação de reconhecimento de texto (OCR) utilizando os conceitos abordados durante o conteúdo da DIO. O objetivo foi demonstrar como integrar ferramentas avançadas, como Azure OpenAI, Microsoft Copilot e Content Filters, para extrair texto de imagens e tratar os resultados de forma inteligente. O projeto destaca a importância da automação e da inteligência artificial no processamento de dados.

---

## Estrutura do Projeto
O projeto está organizado da seguinte forma:
- **inputs/**: Pasta contendo as imagens utilizadas para o reconhecimento de texto.
- **output/**: Pasta onde são salvos os resultados do OCR, com os textos extraídos de cada imagem.
- **README.md**: Este arquivo, que descreve o processo, apresenta alguns prints e compartilha insights e possibilidades de futuras melhorias.

---

## Passo a Passo do Processo

### 1. Preparação do Ambiente
- Criei um repositório no GitHub com o nome `meu-projeto-ocr-dio`.
- Organizei as pastas `inputs` e `output` para armazenar as imagens e os resultados.

### 2. Captura das Imagens
- Utilizei imagens contendo texto para testar a aplicação.
- As imagens foram salvas na pasta `inputs`.

### 3. Processamento e Reconhecimento de Texto (OCR)
- Integrei o serviço de OCR utilizando a API do Azure OpenAI (ou outro serviço de OCR disponível).
- O código realizou a extração de texto das imagens e salvou os resultados na pasta `output`.
- Durante esse processo, utilizei filtros de conteúdo para melhorar a qualidade dos resultados.

### 4. Análise e Tratamento dos Dados
- Realizei ajustes finos para garantir que o reconhecimento estivesse preciso.
- Alguns prints do processo foram capturados para ilustrar a execução e os resultados obtidos.

---

## Prints do Processo

### Exemplo de Execução do OCR

)![images](https://github.com/user-attachments/assets/b57d291d-90d3-434e-afb9-d9b1706fb791)


### Resultado do Reconhecimento de Texto
📄 [output/imagem.txt](output/imagem.txt)

---

## Insights e Possibilidades

### Integração com Azure OpenAI
Aprendi como integrar serviços de inteligência artificial para enriquecer a extração de dados e melhorar a precisão do reconhecimento.

### Utilização de Content Filters
Os filtros de conteúdo possibilitam a melhoria dos resultados, removendo ruídos e ajustando o output do OCR.

### Microsoft Copilot
Explorando a generative AI com o Microsoft Copilot, pude automatizar parte do processo de revisão e validação dos resultados.

---

## Futuras Expansões
- Desenvolver uma interface web para exibir as imagens e os textos reconhecidos.
- Implementar um pipeline de processamento mais robusto com logs e tratamento de erros.
- Ampliar o uso de AI para incluir tradução ou análise semântica do texto extraído.

---

## Conclusão
Este projeto reforça a importância da organização e da documentação dos processos, além de demonstrar como tecnologias modernas, como Azure OpenAI e Microsoft Copilot, podem ser utilizadas para resolver problemas práticos. A integração com serviços da Azure e o uso de ferramentas de AI abrem diversas possibilidades para aprimorar a experiência de reconhecimento de texto e enriquecer o portfólio de projetos.
