# Polygon Editor (2025-1)

O projeto Polygon Editor desenvolvido durante o quarto semestre do curso, teve como empresa parceira a Visiona

[Acesso ao projeto no github](https://github.com/Morpheus-Fatec/API_4S_Visiona_PolygonEditor)

Desenvolvimento de uma plataforma web de edição poligonal com objetivo de importar arquivos geoJson de talhões capturados por drone. O Objetivo é possibilitar a revisão por um analista das imagens captadas e gerar arquivos GeoJson com as correções para dar continuidade ao processo de Machine Learning. Projeto proposto pela FATEC em parceria com empresa Visiona e desenvolvido pela equipe Morpheus, alunos do 4° Semestre de Banco de Dados.

## Tecnologias

Java Spring Boot

- Empregados na criação do back-end da aplicação, com organização de rotas, controle de autenticação, mmanipulação de dados e gestão de 

Maven

- Ferramenta de automação de build utilizada para gerenciar dependências e facilitar a compilação do projeto.

Vue.js e Leaflet

- Biblioteca utilizada para construção da interface interativa e dinâmica para manipulação de dados geoespaciais

Postgres e PostGIS

- Banco de dados relacional utilizado para armazenar as informações extraídas e manipuladas e uso de extenão para manipulação de dados geoespaciasi

Swagger

- Utilizado para documentação da API RESTful.

## Contribuições pessoais

### Desenvolvimento frontend de análises:
Criação e documentação de métodos para expôr dados que haviamos importado e estavam armazenados no banco. 

Meus maiores aprendizados com essa tarefa foram uso de repository JPA para acesso aos dados, gestão dos dados através de índices de paginação, exibição de dados de acordo com filtros dinâmicos e utilização de classes DTO com Lombok para auxiliar processamento dos services e agilizar crição de métodos get e set.

### Desenvolvimento frontend de análises:
Nesse projeto, me desafiei a participar mais de tarefas frontend.

Meus maiores aprendizados foram compreensão sobre componentização, estilização dos componentes e desenvolvimento de rotinas para consumo das APIs.

### Implementação de autenticação e security:
Essa foi minha contribuição mais complexa para o projeto e meu maior aprendizado.

Implementei spring security junto à Java JWT para realizar gestão de acessos e autenticação do projeto. Desenvolvi de autenticação da aplicação para gerar token de acesso. Além disso, implementei controle de cargos e permissões para fornecer consumo de APIs específicas apenas para usuários de cargos autorizados.

### Autenticação e gestão de rotas frontend:
Realizei controle de autenticação da aplicação para permitir acesso a rotas apenas após feito o login do usuário.

Ao consumir a API de login do usuário, armzenei-a através de pinia para autorizar seu acesso pela aplicação. Realizei a gestão de acessos a rotas e tornei dinâmico a apresentação de alguns componentes de acordo com os cargos do usuário.

## APRENDIZADOS EFETIVOS:
### HARDSKILLS
- <ins>**Aprendizado de security e autenticação:**</ins> tive o primeiro contato com frameworks de segurança e criação de tokens para gerenciar de acesso e proteger APIs internas.
  
- <ins>**Desenvolvimento fullstack de funcionalidades de análise de dados:**</ins> contribui pela primeira vez desenvolvendo integrados backend e frontend para uma funcionalidade. Fiz uso de repositorys, services e DTOs para manipular dados e criei componentes para consumi-los e exibi-los de acordo com sua paginação.

- <ins>**Gestão de cargos e autorização de usuários:**</ins> gerenciei o acesso às funcionalidades da aplicação, restrigindo algumas de funcionários sem alçada de autorização.

### SOFTSKILLS
- <ins>**Compreensão da aplicação como um todo:**</ins> desenvolvi habilidade para contribuir com as variadas necessidades de suporte à aplicação.
  
- <ins>**Resolução de conflitos:**</ins> no decorrer do projeto, houveram alguns conflitos na cooperação da equipe. Foi necessário a aplicação de estratégias para contornar as divergências e garantir boas entregas nas sprint reviews.
  
- <ins>**Análise crítica:**</ins> ao trabalhar com tarefas de autenticação e gestão de usuários por cago, pude mapear cenários de uso da aplicação de modo a identificar possíveis fragilidades e inconsistências que infrigiriam as regras de negócio estabelecidas.

