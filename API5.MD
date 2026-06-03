# Neo Horizon (2025-2)
O projeto Neo Horizon, desenvolvido durante o quinto semestre do curso, teve como empresa parceira a Necto.

[Acesso ao projeto no github](https://github.com/FatecNeoHorizon/API_5S)

Desenvolver uma aplicação web de inteligência de negócios para gestão de projetos, integrada à base de dados do Jira. Essa ferramenta será um painel de controle centralizado, fornecendo uma visão clara do desempenho dos projetos.

O objetivo da solução é transformar dados brutos em informações estratégicas, capacitando os usuários na tomada de decisões de forma ágil e assertiva.

## Tecnologias

Java Spring Boot

- Empregados na criação do back-end da aplicação, com organização de rotas, controle de autenticação, manipulação de dados e gestão de acesso dos usuários

Maven

- Ferramenta de automação de build utilizada para gerenciar dependências e facilitar a compilação do projeto.

React

- Framewrok utilizado para construção da interface interativa e vista dos dashboards e indicadores

Github Actions

- Ferramenta para execução de pipeline de CI/CD

SonarQube Cloud

- Ferramenta para análises estáticas do código e gestão do quality gate do projeto

Postgres

- Banco de dados para registro dos dados organizados no modelo estrela

Swagger

- Utilizado para documentação da API RESTful.

## Contribuições pessoais

### Estruturação e configuração de testes unitários
Atuei na definição de processo, ferramentas para gestão de qualidade de desenvolimnetos do projeto e acompanhamento de quality gate integrado ao SonarQube Cloud.

Alinhado ao time, defini que a unidade a ser analisada em nosso projeto seria a Classe. Defini padrões e exemplos de desenvolvimento de teste visando atender quality gate e code coverage esperados. 

Para a realização dos testes, foi utilizado o framework JUNIT, como no exemplo a seguir:

```java
import org.junit.jupiter.api.Test;
import static org.junit.jupiter.api.Assertions.*;

class CalculadoraTest {

    Calculadora calc = new Calculadora();

    @Test
    void deveSomarDoisNumerosCorretamente() {
        // Given (Dado que)
        int a = 5;
        int b = 3;

        // When (Quando)
        int resultado = calc.somar(a, b);

        // Then (Então)
        assertEquals(8, resultado);
    }
}
```

### Atuação em gestão de prazos e remoção de impeditivos
Atuei no papel de Scrum Master do projeto, sendo o resposável por assegurar que os artefatos e eventos do SCRUM fossem cumpridos. 

Dessa forma, promovi a realização dos eventos Planejamento de sprint, 'Dailies Meetings', Reunião de Review e Retrospectiva de Sprint. Fiz a definição das DOD e DOR da equipe e atuei na remoção de impeditivos que a equipe viesse a encontrar
 
Realizei a gestão de entregas e prazos alinhados com a equipe através de ferramenta de Burndownd automático integrado à plataforma Zube, a qual acompanhava as entregas realizadas através de integração com o Github Projects.

### Documentação geral do projeto
Gerenciei todas as documentações do projeto, técnicas, processuais e DevOps. As documentações de detalhamento do escopo do projeto apliquei no README do repositório. Defini um submódulo do projeto exclusivo para alocar as documentações técnicas da aplicação. Por fim, para realizar a gestão de cada uma das etapas de nosso processo de DevOps, utilizamos a ferramenta de Wiki do próprio Github.

## APRENDIZADOS EFETIVOS:
### HARDSKILLS
- <ins>**Criação de pipelines YAML:**</ins> para concretizar o processo de CI/CD de nosso DevOps, criamos uma pipeline contemplando cada uma das etapas do nosso fluxo de DevOps até o Deploy Automático. Aprendizagem e aplicação desse fluxo me auxiliou na implementação prática de uma pipeline para os desenvolvimentos de minha equipe no trabalho.

- <ins>**Desenvolvimento de Testes Unitários:**</ins> conheci mais a fundo processo de testes unitários, de análises estáticas e cobertura de código. Também me auxiliou em implementação do processo em meu trabalho, implementando análise estática e execução de testes automatizados durante o desenvolvimento de novas funcionalidades.

### SOFTSKILLS
- <ins>**Gestão de prazos:**</ins> fiz o acompanhamento de mútliplos desenvolvimentos simultâneos assegurando que os requisitados combinados com o cliente fossem entregues no prazo acordado.

- <ins>**Resolução de Conflitos:**</ins> removi impasses e desentendimentos do time e contribui com a definição de quesitos onde havia discordância.

- <ins>**Facilitação:**</ins> atuei próximo aos membros do time para agilizar entregas e otimizar nossos resultados


