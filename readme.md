# I-Exchange

## Descrição do Projeto

O **I-Exchange** é uma projeto desenvolvido dentro da disciplina de Marketing no curso de Sistemas para internet na Fatec de Jales. 

O propósito do projeto é facilitar as relações de negócios entre as pessoas.

## Tecnologias Utilizadas

- **Linguagem:** Java 17
- **Framework:** Spring Boot 3.3.3
- **Sistema de Build:** Gradle

## Pré-requisitos

Antes de iniciar, certifique-se de ter as seguintes ferramentas instaladas em sua máquina:

- **JDK 17** - [Download JDK 17](https://www.oracle.com/java/technologies/javase-jdk17-downloads.html)
- **Gradle 7.6 ou superior** - [Download Gradle](https://gradle.org/install/)
- **Git** (opcional, para clonar o repositório) - [Download Git](https://git-scm.com/downloads)

## Como baixar e executar o projeto

Siga os passos abaixo para configurar e executar o projeto em sua máquina local:

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/darnosls/projeto-marketing-fatec.git
   cd projeto-marketing-fatec
   ```

2. **Compile e construa o projeto:**

   Execute o seguinte comando para compilar o projeto e baixar todas as dependências necessárias:

   ```bash
   ./gradlew build
   ```

3. **Execute a aplicação:**

   Para iniciar a aplicação, utilize o comando abaixo:

   ```bash
   ./gradlew bootRun
   ```

4. **Acesse a aplicação:**

   Após a execução bem-sucedida, a API estará disponível em `http://localhost:8080`.

## Estrutura do Projeto

A estrutura básica do projeto é organizada da seguinte forma:

```
I-Exchange/
├── src/
│   ├── main/
│   │   ├── java/               # Código-fonte Java
│   │   └── resources/          # Arquivos de configuração e recursos estáticos
│   └── test/                   # Testes unitários
├── build.gradle                # Configurações do Gradle
├── settings.gradle             # Configurações do projeto no Gradle
└── README.md                   # Documentação do projeto
```
## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).