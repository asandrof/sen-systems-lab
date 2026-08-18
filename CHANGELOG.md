# CHANGELOG

Todas as mudanças relevantes realizadas no **SEN Systems Lab** serão registradas neste documento.

Este CHANGELOG acompanha exclusivamente a evolução da plataforma como um todo.

As alterações específicas de cada laboratório são documentadas no arquivo `CHANGELOG.md` existente dentro do respectivo laboratório.

O formato deste documento é inspirado em **Keep a Changelog** e segue os princípios de versionamento semântico.

---

# Version 2.0.0

## Added

### Estrutura modular da plataforma

A plataforma passou a ser organizada em módulos de conhecimento.

```text
MODULE-01-FOUNDATION
...
```

Essa organização melhora significativamente a navegação no repositório e permite que a plataforma cresça de forma escalável.

---

### Organização por áreas de conhecimento

Os laboratórios deixam de ocupar diretamente a raiz do repositório.

Cada laboratório passa a pertencer ao módulo correspondente.

---

### Arquitetura pedagógica modular

A trilha passa a ser organizada por grandes áreas de conhecimento.

Cada módulo representa uma etapa da evolução da plataforma.

---

### Framework oficial dos laboratórios

Cada laboratório passa a possuir obrigatoriamente:

* README.md
* PROJECT_STRUCTURE.md
* CODE_REVIEW.md
* CHANGELOG.md
* LABORATORY_METRICS.md
* ARCHITECTURE_SNAPSHOT.md
* ADR-XXX.md
* CURRICULUM.md

além do snapshot completo do código-fonte.

---

### Snapshots independentes

Todos os laboratórios passam a conter todos os arquivos necessários para sua execução.

Nenhum laboratório depende de outro laboratório.

---

### Princípios permanentes

A plataforma passa a seguir oficialmente os seguintes princípios:

* Uma única plataforma.
* Um conceito novo por laboratório.
* Evolução incremental.
* Snapshots completos.
* Engenharia antes da tecnologia.

---

# Version 1.0.0

## Initial Release

Criação da plataforma SEN Systems Lab.

Definição da filosofia do projeto baseada na evolução incremental de uma única aplicação.

Introdução dos primeiros laboratórios da trilha de aprendizagem.

---

# Versioning Policy

O versionamento da plataforma utiliza o padrão Semantic Versioning.

* **MAJOR** - mudanças estruturais na plataforma.
* **MINOR** - novos módulos ou grandes blocos de conhecimento.
* **PATCH** - ajustes de documentação, correções e melhorias sem impacto estrutural.

---

# Scope

Este documento registra exclusivamente mudanças relacionadas à plataforma como um todo.

Mudanças específicas de um laboratório permanecem registradas no `CHANGELOG.md` existente dentro daquele laboratório.

---

# References

* README.md
* CONTRIBUTING.md
* ADRs dos laboratórios
* CHANGELOG.md dos laboratórios
