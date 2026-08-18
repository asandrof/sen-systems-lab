# SEN Systems Lab

> **One Platform. Incremental Evolution. Real Engineering.**
> 
O **SEN Systems Lab** é um laboratório prático de engenharia de software estruturado em torno da evolução incremental de uma plataforma de software financeiro real, desenvolvida em Java.

Em vez de exemplos isolados ou projetos descartáveis, o laboratório trabalha com um único sistema em constante evolução. Cada sessão apresenta um desafio técnico específico, preserva as funcionalidades implementadas anteriormente e faz a plataforma avançar por meio de decisões concretas de engenharia, análise de *trade-offs* e experimentos.

O objetivo é explorar como o software de *backend* evolui à medida que a complexidade aumenta, abrangendo desde o projeto fundamental e a modelagem de domínio até persistência, APIs, testes, arquitetura e aspectos voltados para a produção, de acordo com a evolução do Systems Lab.

---

# Quick Start

## Pré-requisitos

* Java 21 ou superior
* Git
* IntelliJ IDEA, Eclipse ou Visual Studio Code

## Clone o repositório

```bash
git clone https://github.com/asandrof/sen-systems-lab.git
```

## Navegue até um módulo

Exemplo:

```text
MODULE-01-FOUNDATION/
```

## Escolha um laboratório

Exemplo:

```text
LAB-001/
```

Cada laboratório possui seu próprio código-fonte e documentação, podendo ser estudado e executado de forma independente.

---

# Learning Path

A plataforma está organizada em módulos de conhecimento que representam a evolução natural de uma aplicação corporativa.

```text
Foundation
        │
        ▼
Object-Oriented Programming
        │
        ▼
Rich Domain Model
        │
        ▼
Persistence
        │
        ▼
REST APIs
        │
        ▼
Testing
        │
        ▼
Enterprise Architecture
        │
        ▼
Production Ready
```

Cada módulo introduz novas competências e prepara a base para o módulo seguinte.

---

# Objetivos

O SEN Systems Lab foi concebido para:

* Explorar a engenharia de software por meio da evolução incremental de uma única plataforma de software financeiro;
* Introduzir desafios técnicos específicos à medida que a complexidade do sistema aumenta;
* Tornar explícitas as decisões de engenharia, os *trade-offs* e suas consequências;
* Aplicar práticas de engenharia de software em um sistema de *backend* de complexidade progressivamente maior;
* Preservar e evoluir funcionalidades previamente estabelecidas em toda a plataforma;
* Fornecer *snapshots* completos e executáveis ​​do sistema, tornando cada estágio da evolução observável e reproduzível.

---

# Filosofia

O SEN Systems Lab segue um conjunto restrito de princípios que regem a evolução da plataforma.

## Uma Plataforma em Evolução

Todo o laboratório é estruturado em torno de uma única plataforma de software financeiro em constante evolução.

As funcionalidades não são descartadas entre os laboratórios, cada etapa se baseia no sistema estabelecido anteriormente.

---

## Evolução Técnica Focada

Cada laboratório introduz um desafio técnico ou uma questão de engenharia específica.

O objetivo é isolar o impacto de cada alteração, preservando, ao mesmo tempo, as funcionalidades já existentes no sistema.

---

## Complexidade Incremental

A complexidade do sistema aumenta progressivamente.

Grandes mudanças arquiteturais ou técnicas são introduzidas por meio de etapas menores e observáveis, tornando seus efeitos mais fáceis de compreender, avaliar e reproduzir.

---

## Instantâneos (Snapshots) do Sistema Completo

Cada laboratório representa um estado completo e executável da plataforma.

Um *snapshot* inclui o código-fonte, a estrutura do projeto e a documentação necessária para compreender e reproduzir aquela etapa do sistema.

---

## Engenharia Antes da Tecnologia

Tecnologias e *frameworks* são introduzidos quando atendem a uma necessidade concreta de engenharia.

A plataforma concentra-se no problema a ser resolvido, nas restrições envolvidas e nas consequências das decisões técnicas resultantes, em vez de focar na adoção da tecnologia em si.

---

# Organização do Repositório

O repositório está organizado em torno da evolução progressiva da plataforma SEN Systems Lab.

A estrutura pública será expandida incrementalmente à medida que módulos e laboratórios forem disponibilizados.

O repositório segue esta organização geral:

```text
SEN-Systems-Lab/

README.md
CONTRIBUTING.md
CHANGELOG.md
LICENSE.md

MODULE-01-FOUNDATION/
MODULE-02-OBJECT-ORIENTED-PROGRAMMING/
MODULE-03-RICH-DOMAIN-MODEL/
MODULE-04-PERSISTENCE/
MODULE-05-REST-APIs/

...

---

# Roteiro

O SEN Systems Lab evolui por meio de uma sequência de etapas técnicas, com cada módulo introduzindo um novo nível de complexidade do sistema.

## MÓDULO 01 — FUNDAMENTOS

Estabelecer a estrutura inicial da plataforma e os componentes fundamentais necessários para a sua evolução.

## MÓDULO 02 — PROGRAMAÇÃO ORIENTADA A OBJETOS

Expandir o modelo de domínio por meio de design orientado a objetos e comportamentos de negócio progressivamente mais ricos.

## MÓDULO 03 — MODELO DE DOMÍNIO RICO

Aumentar a complexidade do domínio e explorar como regras de negócio, invariantes e comportamentos de domínio evoluem dentro do sistema.

## MÓDULO 04 — PERSISTÊNCIA

Introduzir estado persistente e evoluir a plataforma para lidar com armazenamento de dados, consistência e questões relacionadas à persistência.

## MÓDULO 05 — APIs REST

Expor a plataforma por meio de APIs de backend e introduzir aspectos associados a limites de serviço e interação externa.

---

Módulos adicionais serão introduzidos à medida que a plataforma evoluir.

---

# Estrutura do Laboratório

Cada laboratório representa um instantâneo completo e executável da plataforma SEN Systems Lab.

Um laboratório contém o código-fonte e a documentação necessários para compreender, executar e reproduzir aquele estágio da plataforma.

A estrutura de cada laboratório segue os padrões definidos pelo SEN Systems Lab e pode evoluir à medida que a plataforma e sua estrutura de aprendizado amadurecem.

Os laboratórios são organizados em módulos, sendo que cada módulo representa um estágio mais amplo da evolução técnica da plataforma.

## Documentação

* README.md
* PROJECT_STRUCTURE.md
* CODE_REVIEW.md
* CHANGELOG.md
* LABORATORY_METRICS.md
* ARCHITECTURE_SNAPSHOT.md
* ADR-XXX.md
* CURRICULUM.md

## Código-fonte

Cada laboratório contém todos os arquivos Java pertencentes ao respectivo snapshot da plataforma.

Essa abordagem garante que cada laboratório seja completamente independente.

---

# Como usar o laboratório

A abordagem recomendada é seguir a evolução da plataforma sequencialmente.

Comece com o primeiro módulo disponível e avance pelos seus laboratórios antes de passar para a próxima etapa.

Cada laboratório se baseia nas capacidades estabelecidas anteriormente e apresenta um desafio técnico específico.

Para cada laboratório, estude a implementação, compreenda o problema abordado, examine o estado resultante do sistema e, em seguida, avance para a próxima evolução.

O objetivo não é apenas reproduzir o código, mas observar como o sistema se modifica à medida que novos requisitos e restrições técnicas são introduzidos.

---

# Tecnologias

A plataforma é desenvolvida principalmente em Java e incorporará tecnologias e ferramentas de forma progressiva, à medida que novos desafios de engenharia surgirem.

A pilha tecnológica evolui junto com a plataforma, em vez de ser definida previamente.

As tecnologias podem incluir:

* Java
* Spring Boot
* Spring Data JPA
* Hibernate
* PostgreSQL
* JUnit 5
* Mockito
* Testcontainers
* Docker
* Kubernetes
* OpenTelemetry
* GitHub Actions

Cada tecnologia é introduzida quando atende a um requisito concreto ou a uma necessidade de engenharia da plataforma.

---

# Público-alvo

O SEN Systems Lab destina-se a profissionais de software e engenheiros interessados ​​em compreender como os sistemas de backend evoluem à medida que a complexidade técnica aumenta.

O público-alvo principal inclui:

* Engenheiros de Backend.
* Engenheiros de Software.
* Arquitetos de Software.
* Engenheiros de Plataforma.
* Engenheiros que desenvolvem sistemas com complexidade técnica e operacional crescente.

O laboratório também pode ser utilizado como recurso de aprendizado prático por desenvolvedores que estão construindo suas bases em backend e engenharia de software.

---

# Contribuições

Contribuições são bem-vindas.

Antes de propor alterações, por favor, consulte o arquivo [CONTRIBUTING.md](CONTRIBUTING.md) para conhecer as diretrizes de contribuição, os padrões e o processo de envio do projeto.

---

# License

This project is licensed under the MIT License.

See [LICENSE.md](LICENSE.md) for the full license text.
---

# SEN Systems Lab

**One Platform. Incremental Evolution. Real Engineering.**
