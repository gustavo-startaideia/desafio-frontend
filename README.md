# Dev. Front-End

Sua tarefa é construir um front-end para a aplicação VUTTR (Very Useful Tools to Remember). A aplicação é um simples repositório para gerenciar ferramentas com seus respectivos nomes, links, descrições e tags. Utilize um repositório Git (público, de preferência) para versionamento e disponibilização do código.
O front-end deve ser construído utilizando o framework de sua preferência, utilizando [este style guide](https://xd.adobe.com/spec/6a82c840-1813-4b23-6919-2ac91409d104-1cb3/) e seguindo os wireframes apresentados abaixo.

## O que será avaliado

Queremos avaliar sua capacidade de desenvolver e documentar um front-end para uma aplicação com back-end pronto. Serão avaliados:

- Código bem escrito e limpo;
- Quais ferramentas foram usadas, como e por quê;
- Seu conhecimento em JavaScript, HTML e CSS;
- Sua capacidade de se comprometer com o que foi fornecido (wireframe, styleguide);
- Sua capacidade de documentação da sua parte da aplicação.

## O mínimo necessário

- As telas seguindo os wireframes a seguir e utilizando a API disponibilizada ao fim deste documento;
- [README.md](http://readme.md) contendo informações básicas do projeto e como executá-lo.

## Bônus

Os pontos em negrito se destacam como características para se tornar **Tech Lead** em squads.

- Testes de front-end;
- Uso de ferramentas externas que facilitem o seu trabalho;
- Cuidados especiais com otimização, SEO, entre outros;
- **Deploy da aplicação utilizando ferramentas externas (Netlify, Surge, S3, Firebase, etc)**;
- **Pipeline de deploy contínuo**
- Sugestões sobre o challenge embasadas em alguma argumentação.

# User Stories e wireframes

## 1: O(A) usuário(a) deve poder ver a lista de todas as ferramentas cadastradas

![Wireframe_1](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F75d16a8e-e4da-43e6-ab85-effcf60ee83e%2FHome.png?table=block&id=8c50c90e-0bc6-430a-9741-366bf333172f&width=2730&cache=v2)

## 2: O usuário deve poder adicionar uma nova ferramenta

![Wireframe_2](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F73d42f2c-51b5-4b7e-8158-372335c712ae%2Fadd-tool.png?table=block&id=9cc4335a-46cb-425d-98cf-4a0a0581fc17&width=2560&cache=v2)

## 3: O usuário deve poder remover uma ferramenta

![Wireframe_3](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F3c2a9c92-4ea4-4711-bf15-d897b2909421%2Fremove-tool.png?table=block&id=bab5a791-760b-4e89-bebc-d7f580c76769&width=2560&cache=v2)

## 4: O usuário deve poder buscar ferramentas dinamicamente (global ou utilizando apenas tags)

![Wireframe_4](https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F6e6287ba-3584-47c6-afba-831258a2b0f1%2Fsearch.png?table=block&id=ec770b95-0245-4704-81b3-b08d566d3510&width=2560&cache=v2)

## Critérios de Aceitação

- Deve ser usada a API disponibilizada no fim deste documento para listar, adicionar, remover e filtrar as ferramentas. Se você está realizando o desafio para full-stack, deve utilizar a API construída por você, no desafio de back-end.

# API

[https://github.com/gustavo-startaideia/rest-fake-api](https://github.com/gustavo-startaideia/rest-fake-api)

---
