# OficinaTech - Sistema de Gestão para Oficinas Mecânicas

## 📝 Descrição
OficinaTech é um sistema web desenvolvido para auxiliar oficinas mecânicas no gerenciamento de ordens de serviço, clientes e veículos. O sistema oferece uma interface intuitiva e funcionalidades completas para o controle eficiente das operações diárias de uma oficina mecânica.

## 🕶 Diagrama

![alt text](<Untitled diagram-2025-01-27-154807-1.png>)

## 🚀 Funcionalidades Principais

### Gestão de Clientes
- Cadastro completo de clientes com informações de contato
- Histórico de serviços por cliente
- Gerenciamento de dados cadastrais

### Controle de Veículos
- Registro detalhado dos veículos
- Histórico de manutenções
- Vinculação com proprietários

### Ordens de Serviço
- Criação e gestão de OS
- Acompanhamento de status em tempo real
- Cálculo automático de valores
- Registro de serviços realizados

## 🛠️ Tecnologias Utilizadas

- **Backend:**
  - Java EE
  - JPA (Java Persistence API)
  - CDI (Contexts and Dependency Injection)
  - EJB (Enterprise JavaBeans)

- **Frontend:**
  - JSF (JavaServer Faces)
  - PrimeFaces
  - HTML5
  - CSS3

- **Banco de Dados:**
  - PostgreSQL

- **Servidor de Aplicação:**
  - WildFly/Payara/GlassFish

## 📋 Pré-requisitos

- JDK 11 ou superior
- Maven 3.6+
- PostgreSQL 12+
- IDE (Eclipse ou similar)
- Servidor de Aplicação Java EE

## 🔧 Configuração do Ambiente

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/oficina-tech.git
```

2. Importe o projeto na sua IDE como projeto Maven

3. Configure o banco de dados no arquivo `persistence.xml`

4. Configure o DataSource no seu servidor de aplicação

## 📦 Estrutura do Projeto

```
src/
├── main/
│   ├── java/
│   │   └── br/com/oficina/
│   │       ├── model/
│   │       ├── repository/
│   │       ├── service/
│   │       ├── controller/
│   │       └── util/
│   ├── resources/
│   │   └── META-INF/
│   └── webapp/
│       ├── pages/
│       ├── resources/
│       └── WEB-INF/
```

## ⚙️ Executando o Projeto

1. Build do projeto:
```bash
mvn clean package
```

2. Deploy no servidor de aplicação

3. Acesse: `http://localhost:8080/oficina-tech`

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE.md)

## ✒️ Autores

* **Enoque de Sousa Neres** - *Desenvolvimento Inicial* - [enqneres](https://github.com/enqneres)

## 🎁 Expressões de Gratidão

* Compartilhe este projeto com outras pessoas 📢
* Quer melhorar esse projeto ? Me manda uma DM no Linkedin ! Vamos colaborar juntos 🤓
* Agradecimentos aos mentores da ProgrameIO por disponibilizar esse desafio top para alavancar nossos conhecimentos, Ely Bezerra Jr. e Galeno 😎

---
⌨️ com ❤️ por [enqneres](https://github.com/enqneres) 😊
