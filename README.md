# 🎬 Sistema de Streaming

Aplicação Java que simula uma plataforma de streaming, desenvolvida com foco em modelagem orientada a objetos. O projeto aplica os quatro pilares de POO para estruturar as regras de negócio de forma organizada e escalável.

---

## Sobre o projeto

O objetivo foi modelar o domínio de uma plataforma de streaming — com conteúdos, usuários e regras de acesso — usando os conceitos fundamentais de orientação a objetos em Java.

O foco não foi na interface, mas na arquitetura: como organizar classes, distribuir responsabilidades e usar herança e polimorfismo para criar um sistema extensível.

---

## Conceitos aplicados

**Encapsulamento**
Atributos privados com acesso controlado via getters e setters, garantindo que o estado interno de cada objeto seja manipulado de forma segura.

**Herança**
Hierarquia de classes para representar diferentes tipos de conteúdo (filmes, séries, episódios), evitando repetição de código e facilitando extensão.

**Polimorfismo**
Comportamentos que variam de acordo com o tipo de objeto em tempo de execução, permitindo tratar diferentes conteúdos de forma uniforme.

**Abstração**
Classes e interfaces abstratas que definem contratos claros entre as partes do sistema, separando o que um objeto faz de como ele faz.

---

## Estrutura do projeto

```
streaming/
└── src/
    └── (classes do domínio organizadas por responsabilidade)
```

---

## Como rodar

**Pré-requisitos:**
- Java 11 ou superior
- IDE com suporte a Java (IntelliJ, Eclipse ou VS Code com extensão Java)

**Passos:**

1. Clone o repositório
```bash
git clone https://github.com/rcannabrava/streaming.git
```

2. Abra o projeto na sua IDE

3. Localize a classe principal (`Main.java` ou equivalente) e execute

---

## Tecnologias

- Java
- Orientação a Objetos (POO)

---

## Autor

**Rodrigo Furstenau**
Estudante de Ciência da Computação — IBMR, Rio de Janeiro

[LinkedIn](https://linkedin.com/in/rodrigo-furstenau) · [GitHub](https://github.com/rcannabrava)
