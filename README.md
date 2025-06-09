# Desafio DIO: Azure AI Search - Indexação Inteligente

Este repositório documenta as etapas e aprendizados do laboratório prático utilizando **Azure AI Search** para ingestão de conteúdo, criação de índices inteligentes e exploração de dados organizados.

## 🎯 Objetivo

Desenvolver uma solução prática capaz de:
- Organizar documentos de forma inteligente
- Criar índices com base em IA
- Explorar e buscar informações com eficiência

## 🧰 Ferramentas Utilizadas

- Azure AI Search
- Azure Cognitive Services
- GitHub
- Interface gráfica do Azure Portal

## 📁 Documentação

- [Ingestão de Dados]
- [Criação de Índices]
- [Exploração dos Dados]
- [Insights Finais]
## 📸 Capturas de Tela


## 📌 Conclusão

Este projeto serviu para consolidar o entendimento de como organizar e consultar dados usando IA na nuvem com Azure Search. A experiência prática foi essencial para fixar os conceitos abordados nas aulas.

# Desafio-Azure-Cognitive-Search


# Ingestão de Dados

## Etapas Realizadas

1. Criação de um recurso Azure AI Search no portal
2. Seleção do dataset de documentos (PDFs/textos)
3. Utilização de um data source (por exemplo, Azure Blob Storage)
4. Configuração do skillset com habilidades cognitivas:
   - OCR
   - Detecção de linguagem
   - Extração de entidades

## Observações

- É importante garantir que os documentos estejam bem formatados.
- A conexão com o armazenamento precisa ter permissões apropriadas.

# Criação de Índices Inteligentes

## Etapas

1. Definição do schema do índice (campos como: título, conteúdo, autor, etc.)
2. Mapeamento entre os dados extraídos e os campos do índice
3. Execução do indexador para popular os dados

## Dicas

- Use campos pesquisáveis e filtráveis de forma estratégica.
- A escolha do nome dos campos influencia a busca futura.

- # Exploração dos Dados

## Ferramentas Usadas

- Azure Search Explorer (interface gráfica)
- Queries básicas com Lucene Query Syntax


# Insights Finais

- O Azure AI Search é uma ferramenta poderosa para sistemas de busca em larga escala.
- O uso de *skillsets* permite extrair valor de dados não estruturados de forma automatizada.
- Com a prática, ficou mais claro como estruturar pipelines de indexação eficientes.



