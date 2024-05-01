<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/619af8f8-d138-4e40-9d48-fec7b318e44d.png"></a>
    <span> 
Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados</span>
</h1>

## Problema:

O desafio propoe que seja criada uma pesquisa que funcione juntamente com um serviço de inteligência artificial para identificar palavras chave, sentimentos, utilizando também o serviço de armazenamento do azure.

[Documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)

## Passo 1: Criar recurso do Asure AI Search:     

## Passo 2: Criar recurso do Azure AI services:      

## Passo 3: Criar o storage:      

## Passo 3: Permitir o acesso anônimo ao Blob:      

Como nosso laboratório é apenas didático,para aprender os princípios da inteligência artificial com o Azure, precisamos permitir o acesso anônimo ao blob para simplificar e facilitar nossas implementações, Após criar o seu Storage, entre no mesmo e navegue até a guia SETTINGS > CONFIGURATION seguindo os passos abaixo:


## Passo 5: Criar o Container:      

Navegue até a guia DATA STORAGE > CONTAINERS, para criar o contanier dentro do storage e adicionar as pesquisas que seram analisadas pelo AI SERVICE.

## Passo 6: Importar e indexar dados para o AI SEARCH:      

Neste ponto você precisa linkar / importar os dados que você inseriu e configurou no seu STORAGE, volte para o AI SEARCH e siga os passos abaixo:

Esta é a parte mais importante de todo o processo, assim como o bootcamp fala são muitos passos que que você precisa seguir a risca, achei apenas uma diferença da documentação oficial para o que achei quando configurei o meu.

Ao seguir a [Documentação](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html) você chegará em INDEX DOCUMETS, o qual o gif acima mostra o início do processo, siga os topicos até chegar na sessão 4:

## Passo 7: Cnsultar o índice:      

Feitas todas as configurações vamos voltar ao AZURE AI SERVICES, entrar no nosso serviço e através do SEARCH EXPLORER testar se tudo foi indexado e se a consulta esta funcionando, utilizando os comandos:

```
search=*&$count=true    (  verifica se a indexação esta funcionando e mostra os documentos )
```

```
search=locations:'Chicago' ( Consulta as ocorrencias acontecidas em Chicado )
```

```
search=sentiment:'negative' ( Consulta as ocorrencias com sentimento negativo )


## Observações finais:      

As ferramentas de inteligÇencia artificial do Azure facilitam a consulta emdocumentos, pesquisas e depoimentos, agilizando ainda mais a consulta de satisfação de empresas sobre seus produtos e serviços.


