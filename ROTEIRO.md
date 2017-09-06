# docs-api-cd

pre requisitos:
- configurar conta no aws
- conhecimentos básicos em java
- conhecimentos básicos em spring
- conhecimentos básicos em jpa
- conhecimentos básicos em testes

-------------------------------------------

- configurar java local
- criar aplicação com spring boot e gradle
- criar repo no gitlab          

-------------------------------------------

- criar pipeline com step de build
- criar ec2 no aws
- instalar java manualmente
- fazer deploy da aplicação manualmente
- criar step no pipeline de deploy no aws

------------------------------------------

- configurar banco de dados para usar local (postgres)
- criar feature de criar um dev
  - atributos:
    - nome
    - horas de desenvolvimento
    - user no github
  - criar testes unitários (junit 5)
  - criar testes de componente (banco de dados em memoria)
    - usar groovy + spock
  - criar smoke test
    - usar groovy + spock
- adicionar testes no pipeline
- destruir máquina no aws
- automatizar provisionamento (ansible)
- criar máquina manual
- criar banco rds manual
- criar feature de listar devs
  - atributos:
    - nome
    - horas de desenvolvimento
    - senioridade (junior > 2 anos de dev, pleno > 6 anos de dev, senior > 10 anos de dev)
  - criar testes unitarios
  - criar teste de integração (como? não vai ter query)
  - criar testes de componente
- destruir máquina no aws
- automatizar criação de ec2 e rds com terraform
- adicionar feature de integração com github
  - cada 5 repos no github == 1 ano de trabalho para senioridade
  - criar testes unitários
  - criar teste de integração para github
  - criar teste de componente
  - criar teste end-to-end com spock
- escrever teste de carga
- adicionar delay nos requests de 2 segundos
- escalar vertical (mudar de t2.nano ou micro para t2.medium)
- criar auto scaling group com load balacing
- escalar horizontal
