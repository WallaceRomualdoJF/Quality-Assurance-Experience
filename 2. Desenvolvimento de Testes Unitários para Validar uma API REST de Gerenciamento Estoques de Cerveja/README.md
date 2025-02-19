
# Testes Unitários para Validar uma API REST

Este repositório contém o conteúdo da aula sobre **Testes Unitários**, apresentada na plataforma **Digital Innovation One**. O objetivo desta aula foi ensinar sobre a pirâmide de testes de software, destacando a importância dos testes unitários durante o desenvolvimento e explorando frameworks como JUnit, Mockito e Hamcrest.

## Objetivos da Aula

- **Pirâmide de Testes de Software**: Explicação e detalhamento dos diferentes níveis de testes (Unitários, de Integração, e de Interface).
- **Importância dos Testes Unitários**: Como garantir a qualidade do código e prevenir regressões durante o desenvolvimento.
- **Frameworks de Testes**: Apresentação de frameworks populares como **JUnit**, **Mockito** e **Hamcrest** para testes em Java.
- **Prática**: Codificação de exemplos de testes unitários, compartilhamento de código e aprendizado colaborativo.

## O que Vamos Utilizar

- **Java 14** para o desenvolvimento.
- **Maven 3.6.2** para gerenciamento de dependências.
- **Spring Boot** (última versão estável) para construção de APIs.
- **Git/GitHub** para versionamento de código.
- **JUnit**, **Mockito** e **Hamcrest** como frameworks de teste.

## Conceitos Importantes

### Anotações e Conceitos

- **@Data**: Gera automaticamente os métodos getters, setters, `toString()`, `equals()` e `hashCode()` para a classe.
- **DAO (Data Access Object)**: Responsável pela comunicação com o banco de dados.
- **Optional**: Introduzido no Java 8, ajuda a lidar com valores ausentes de forma mais segura.
- **@Service**: Indica que a classe é um serviço no contexto do Spring, que contém a lógica de negócios.
- **@RestController**: Controlador que retorna dados sem a necessidade de uma interface gráfica (API RESTful).

### HTTP Verbs (Métodos HTTP)

- **GET**: Lê dados do banco de dados.
- **PUT**: Atualiza/Altera uma linha no banco de dados.
- **PATCH**: Modifica uma linha no banco de dados.
- **POST**: Cria um novo registro no banco de dados.
- **DELETE**: Deleta um registro do banco de dados.

### API RESTful - Richardson Maturity Model

O modelo de maturidade de APIs RESTful, de Richardsons, descreve os seguintes níveis:
- **Level 0**: O "pântano" de POX (Plain Old XML).
- **Level 1**: Recursos.
- **Level 2**: Verbos HTTP.
- **Level 3**: Hiperlinks e controles.

### Pirâmide de Testes

A pirâmide de testes sugere que a maior parte dos testes deve ser de **unidade**, seguidos de **testes de integração** e, por último, **testes de interface**. Exemplo de ferramentas:
- **UI Tests**: Appium.
- **Integration Tests**: UI Automator, Espresso, AndroidJUnit4.
- **Unit Tests**: JUnit, Mockito.

### Vantagens dos Testes

- **Sistema Testado de Ponta a Ponta**: Garantia de que todas as funcionalidades foram verificadas.
- **Evolução Segura**: Desenvolvimento contínuo sem a preocupação de quebrar funcionalidades existentes.
- **Documentação do Código**: Os testes também funcionam como documentação do comportamento esperado.
- **Integração Contínua (CI)**: Automatização do processo de integração do código.
- **Deploy Contínuo (CD)**: Facilitando o envio de novas versões do software sem interromper a produção.

## Licença

Este repositório está licenciado sob a [MIT License](LICENSE).
