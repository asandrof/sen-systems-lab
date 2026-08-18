# Contributing to SEN Systems Lab

Primeiramente, obrigado pelo seu interesse em contribuir com o **SEN Systems Lab**.

O objetivo deste projeto é construir uma plataforma de aprendizagem em Engenharia de Software baseada na evolução incremental de uma única aplicação.

Toda contribuição deve preservar a consistência arquitetural, pedagógica e documental da plataforma.

---

# Filosofia do Projeto

O SEN Systems Lab não é uma coleção de exemplos independentes.

Toda a evolução acontece sobre uma única aplicação.

Cada laboratório representa um snapshot completo da plataforma em um momento específico de sua evolução.

O principal objetivo é ensinar Engenharia de Software através da evolução contínua do mesmo sistema.

---

# Princípios Fundamentais

Toda contribuição deve respeitar permanentemente os seguintes princípios.

## Uma única plataforma

Toda evolução acontece sobre a mesma aplicação.

Não devem existir projetos paralelos ou exemplos desconectados.

---

## Um conceito novo por laboratório

Cada laboratório introduz exatamente um novo conceito.

Os conceitos anteriormente apresentados continuam sendo utilizados e reforçados.

---

## Evolução incremental

Grandes mudanças devem ser divididas em pequenas etapas.

Cada laboratório representa apenas uma evolução arquitetural.

---

## Snapshots completos

Todo laboratório deve ser completamente independente.

Cada snapshot deve conter:

* Documentação completa;
* Código-fonte completo;
* Estrutura completa do projeto.

---

## Engenharia antes da tecnologia

Frameworks e bibliotecas somente devem ser introduzidos quando fizerem sentido para a evolução da plataforma.

O foco principal permanece sendo Engenharia de Software.

---

# Organização do Repositório

A estrutura oficial do projeto é:

```text
SEN-Systems-Lab/

README.md
LICENSE
CONTRIBUTING.md
CHANGELOG.md

MODULE-01-FOUNDATION/
...
```

Cada módulo agrupa laboratórios pertencentes à mesma etapa de conhecimento.

---

# Organização dos Módulos

Cada módulo é composto por um conjunto de laboratórios relacionados ao mesmo objetivo de aprendizagem.

O `README.md` e o `ADR-MODULE.md` do módulo **somente devem ser gerados após a conclusão do último laboratório pertencente ao módulo**.

Essa regra garante que a documentação do módulo represente exatamente o conhecimento consolidado, evitando revisões desnecessárias durante sua construção.

---

# Estrutura dos Laboratórios

Todo laboratório deve conter obrigatoriamente:

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

Todos os arquivos Java pertencentes ao snapshot correspondente.

Mesmo arquivos que não sofreram alterações devem permanecer presentes, garantindo que cada laboratório seja completamente independente.

---

# Desenvolvimento dos Laboratórios

A geração dos laboratórios segue obrigatoriamente a sequência abaixo.

1. Definição do objetivo do laboratório.
2. README.md.
3. PROJECT_STRUCTURE.md.
4. CODE_REVIEW.md.
5. CHANGELOG.md.
6. LABORATORY_METRICS.md.
7. ARCHITECTURE_SNAPSHOT.md.
8. ADR-XXX.md.
9. CURRICULUM.md.
10. Código-fonte.
11. Revisão técnica e arquitetural.

Após a conclusão do último laboratório do módulo:

* gerar o `README.md` do módulo;
* gerar o `ADR-MODULE.md` do módulo.

---

# Convenções Arquiteturais

Toda evolução deve preservar:

* Encapsulamento.
* Alta coesão.
* Baixo acoplamento.
* Responsabilidade única.
* Rich Domain Model.
* SOLID.
* GRASP.
* Clean Code.
* Domain-Driven Design, quando aplicável.

Mudanças arquiteturais devem ser justificadas por meio de ADRs.

---

# Política de Evolução

Laboratórios já concluídos são considerados snapshots históricos da plataforma.

Após sua conclusão:

* Não devem receber melhorias metodológicas;
* Não devem ser reestruturados;
* Somente poderão ser alterados para correção de erros técnicos relevantes.

Melhorias identificadas durante a evolução da plataforma passam a valer apenas para os laboratórios futuros.

Essa política preserva a rastreabilidade da evolução arquitetural.

---

# Pull Requests

Todo Pull Request deve responder claramente às seguintes perguntas.

* Qual problema está sendo resolvido?
* Qual conceito novo está sendo introduzido?
* Qual laboratório foi impactado?
* Existe impacto arquitetural?
* Existe impacto pedagógico?
* Existe necessidade de atualização documental?

---

# Critérios de Qualidade

Uma contribuição somente será considerada concluída quando atender aos seguintes critérios:

* Código compilando;
* Documentação atualizada;
* Snapshot completo;
* Terminologia consistente;
* Arquitetura preservada;
* Um único conceito novo introduzido;
* Compatibilidade com toda a evolução anterior da plataforma.

---

# Código de Conduta

Todas as interações devem ocorrer com respeito, profissionalismo e foco na construção colaborativa da plataforma.

Discussões técnicas são incentivadas.

Comportamentos ofensivos ou incompatíveis com um ambiente colaborativo não serão aceitos.

---

# Dúvidas Arquiteturais

Mudanças estruturais devem ser discutidas antes de sua implementação.

Sempre que possível, decisões arquiteturais devem ser registradas através de ADRs.

---

# Documentação da Plataforma

A documentação oficial está organizada em três níveis.

## Plataforma

* README.md
* CONTRIBUTING.md
* CHANGELOG.md
* LICENSE

## Módulo

* README.md
* ADR-MODULE.md

## Laboratório

* README.md
* PROJECT_STRUCTURE.md
* CODE_REVIEW.md
* CHANGELOG.md
* LABORATORY_METRICS.md
* ARCHITECTURE_SNAPSHOT.md
* ADR-XXX.md
* CURRICULUM.md

Cada documento possui uma responsabilidade específica e não deve duplicar informações existentes em outro nível.

---

# Obrigado

Obrigado por contribuir com o **SEN Systems Lab**.

Toda contribuição que preserve a evolução incremental da plataforma fortalece o projeto e mantém sua consistência arquitetural, pedagógica e documental.
