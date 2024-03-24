# Azure Cognitive Search Utilizando AI Search para indexacao e consulta de Dados

**Objetivo** :  Descrever o passo a passo para se configurar uma pesquisa, assim como seus insights, possibilidades de ferramentas que se beneficiam com esse tipo de ferramenta.

## Falando Sobre o Azure Cognitive Search

O Azure Cognitive Search é uma plataforma de serviço baseada em inteligência artificial da Microsoft que permite aos desenvolvedores criar experiências de pesquisa avançadas em aplicativos e sites de negócios. 
Com recursos como busca de texto completo, navegação geoespacial e indexação de dados de vários sistemas, incluindo armazenamento em nuvem e bancos de dados, o Azure Cognitive Search capacita a criação de bancos de dados pesquisáveis para funcionários explorarem documentos internos, como políticas e procedimentos, enriquecendo os dados por meio de IA para melhorar o conteúdo do índice.


## Fontes  de consultas para execução do projeto:

Além das aulas do Bootcamp Microsoft Azure AI Fundamentals da [DIO](dio.me) foi utilizado a orientação do [Microsoft Learn](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)

### Para este projeto foi necessário a utilização de 03 serviços da plataforma:

    • AI Search  
    • Azure AI Services
    • Storage Accounts


  # Vamos seguir a orientação da documentação para desenvolvermos o projeto:

  ![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/dbab437d-e965-4677-a70f-ab8212f2bcb3)


  ![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/27affc85-5737-495e-a0b9-f49149f407e4)


  ![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/5f0a2a8f-b1d2-4bf8-ab61-21c4bec4d0ba)


  # 1. Criando o Recurso de AI Search 

  ![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/52f1708f-32b9-422c-a140-5039cf2c9c68)


  ![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/9460101a-dc79-4198-adeb-61368edc1ec7)


![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/e61428a5-9f0b-4314-879c-360ff9f314db)

![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/453820fc-c4f6-454c-8aec-949206631290)

![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/e00fb0f0-2dd1-42fa-a1ac-e21116780762)


# 2 . Criando Azure AI Service

![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/58c84cf6-cc3f-4bf2-8ec7-69b09c0bb11c)

![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/e8246ff8-508f-427e-be2f-6c6cb1566a77)

![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/80601e30-0abd-4a40-92ea-3fa60386efb0)

![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/1d3d59ad-d1de-41c7-89f5-bed503d7cfa6)



# 3 . Storage Accounts

![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/83a958f7-b49d-40cf-99da-97ecb4b1d194)


![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/abb0c185-f91d-4ffd-a30d-7d47f4db9af1)

![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/23d99df4-6b92-41a0-b9d8-7e1128fbab3f)


![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/44f438ed-b8db-47c4-b1c6-0f77d296a148)

![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/047524d8-d5f7-41be-b29b-76e56bbc7b97)


Habilitando o acesso anônimo : 

![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/d7ffe192-d118-42f1-832d-2ed348d5c3a9)



# 4 . Carregando Arquivos para o Armazenamento do Azure

![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/3cd5bdf9-c227-497d-84d8-418b5381601a)


![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/f614f945-31e6-4f5c-a78a-3e5d6c986076)



## Criando  um Container


![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/ee182634-b4ed-496b-a2af-7e807e81b70e)


![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/bda5876e-0aa9-4686-9f75-fe42919f90f6)


## Container Criado

![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/d7bcb37e-745b-4833-826d-1a3aeb879b99)


## Fazendo Upload dos Arquvivos no Container

![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/934fd4af-e337-4c67-9333-ee48e2aba882)




# 5. Depois de indexar os documentos seguindo as orientações da documentação. Usei Search Explorer para fazer uma consulta e verificar os resultados 


![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/ab359e65-8afd-4959-a5bf-d27d0a10e08b)


# 6 . Consultas


![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/126e6f84-2504-4336-9c43-baeb4b2441fe)

![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/2b957482-1727-4a37-9ce5-a38ce17bc7d7)


![image](https://github.com/SilvioSodre13/Azure-Cognitive-Search-Utilizando-AI-Search-para-indexacao-e-consulta-de-Dados/assets/101529833/a2f8f9aa-8087-469f-b63a-242db88d4125)



# Fim
















  

  


    

