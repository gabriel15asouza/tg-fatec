# Zeus (2026-1)
O projeto Zeus, desenvolvido durante o sexto semestre do curso, teve como empresa parceira a Tecsys.

[Acesso ao projeto no github](https://github.com/FatecNeoHorizon/API_6S)

O ZEUS é uma plataforma de inteligência de mercado para o setor elétrico que transforma grandes volumes de dados públicos da ANEEL em informações estratégicas para tomada de decisão.

Ela consolida e processa dados de distribuidoras de energia para fornecer indicadores como potencial de mercado (TAM), priorização de oportunidades com base em criticidade (DEC/FEC) e previsões de desempenho futuro por meio de modelos analíticos. Tudo isso é disponibilizado em um painel web e por APIs, permitindo análises rápidas, escaláveis e confiáveis. A solução possui uma arquitetura robusta de dados, com rastreabilidade, auditoria e conformidade com a LGPD, garantindo segurança, governança e confiança no uso das informações.

## Tecnologias

## Tecnologias

### React, TypeScript, Vite e TailwindCSS

- Utilizados no desenvolvimento da interface web da aplicação.

### Python e FastAPI

- Responsáveis pela implementação do back-end, APIs e regras de negócio.

### PostgreSQL

- Banco de dados relacional utilizado para armazenamento de dados transacionais e sensíveis.

### MongoDB

- Banco de dados não relacional utilizado para armazenamento e análise de grandes volumes de dados da ANEEL.

### Keycloak

- Utilizado para autenticação, autorização e gerenciamento de acessos.

### Docker

- Empregado na conteinerização e padronização dos ambientes da aplicação.

### GitHub Actions

- Utilizado para automação de processos de integração e entrega contínua (CI/CD).

### Turborepo

- Ferramenta utilizada para gerenciamento do monorepositório do projeto.

### Java

- Utilizado no desenvolvimento do módulo de acompanhamento de métricas e burndown.

### GitHub API

- Utilizada para coleta de dados de desenvolvimento e geração de indicadores do projeto.

## Contribuições pessoais

### Análise dos dados Públicos ANEEL
A ANEEL possui uma série de dados padronizados para prestação de contas sobre a rede elétrica nacional. Fui responsánvel pelo estudo das normas do PRODIST (Procedimentos de Distribuição de Energia Elétrica) e análise dos documentos e dados disponibilizados para estruturar quais dados poderiam ser utilizados e que agregariam valor segundo a regra de negócio do cliente. 

Em seguida, transmiti o conhecimento para a equipe e documentei os dados que seriam utilizados e como poderíamos extrai-los.

### Modelagem de banco não estrurado
Defini quais as collections que iriamos utilizar em nosso projeto visando boa performance na leitura de seus dados, já que nossa aplicação visava com mais frequência leitura e análise dos dados do que edição ou escrita.

### Implementação de ETL
Realizei processo de extração dos dados contidos nos documentos disponibilizados pela ANEEL. Transformei os dados para integrar com o conteúdo de diferentes fontes e remover inconsitências. Por fim, realizei a criação dos documentos JSON para realizar carga dos dados na aplicação. Devido ao alto volume, a carga foi realizada através de fragmentos (chunks) para otimizar desempenho.

### Implementação de segurança de rotas e endpoints
Implementei bloqueio de acesso a rotas da aplicação para usuários que não estivessem autenticados. Além disso, construi uma matriz de acesso da aplicação para definir e validar quais usuários poderiam ter acesso a cada uma das funcionalidades de acordo com seus perfis. As validações foram implementadas tanto nas rotas e componenentes da interface, como no consumo dos endpoints.

## APRENDIZADOS EFETIVOS:
### HARDSKILLS
- <ins>**Gestão de dados não estruturados:**</ins> utilizando o Mongo como ferramenta de banco de dados, pude compreender como organizar os dados em bancos não estruturados. Explorei alternativas de organização das collections visando baixo número de joins e melhor performance na consulta das informações para os dashboards.

- <ins>**Manuseio de dados geométricos:**</ins> aprendi sobre como os dados geométricos são compartilhados entre sistemas. Apliquei ferramentas e frameworks, como GeoPandas, para converter arquivos geodatabase para formato geojson, possibilitando fácil consumo.

- <ins>**Extração e gestão dos dados:**</ins> apliquei práticas e técnicas para aprimorar a performance do ETL. Além disso, aprendi sobre armazenagem de blobs através da arquitetura de buckets visando acessibilidade escalável de objetos de grande volume. Apesar da tecnologia ter sido analisada como baixa projeto após spike e, por isso, não foi implementada no projeto, explorei algumas alternativas open source como MinIO, Garage e RustFS.

- <ins>**Usabilidade de contâineres:**</ins> diferentemente dos projetos em que atuei, nos quais o Docker era utilizado apenas para deploy, este foi meu primeiro contato com a conteinerização aplicada durante todo o ciclo de desenvolvimento. A experiência permitiu compreender melhor a padronização de ambientes, a integração entre serviços e os benefícios do uso de containers desde as etapas iniciais do projeto.


### SOFTSKILLS
- <ins>**Visão de Negócio:**</ins> o processo de entendimento de como a rede elétrica era organizada, o que influenciava as interrupções de energia e como poderia organizar os dados de modo a agregar valor foi o que levou mais tempo no desenvolvimento. Aprimorei meu alinhamento entre necessidade do cliente e solução proposta.

- <ins>**Pensamento analítico:**</ins> a estruturação de como os dados se integrariam, como seriam extraídos e, por fim, consumidos me possibilitou desenvolver um ponto de vista crítico para definir a solução de melhor aplicabilidade.

- <ins>**Comunicação:**</ins> A necessidade de transmitir conhecimentos sobre o negócio e o funcionamento da rede elétrica aprimorou minha comunicação. Desenvolvi maior capacidade de explicar conceitos técnicos de forma clara e sistêmica.


