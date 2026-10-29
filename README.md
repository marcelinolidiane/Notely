<div align="center">

# Notely

### Sistema de Gestão Acadêmica

Sistema web para gerenciamento de notas, faltas e informações acadêmicas, com controle de acesso e integração com inteligência artificial.

![Java](https://img.shields.io/badge/Java-0077B6?style=for-the-badge\&logo=openjdk\&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-0077B6?style=for-the-badge\&logo=springboot\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-0077B6?style=for-the-badge\&logo=mysql\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-0077B6?style=for-the-badge\&logo=javascript\&logoColor=white)

</div>

---

## Sobre o Projeto

O Notely é um sistema web desenvolvido durante o curso de Análise e Desenvolvimento de Sistemas, na disciplina de Tecnologias Emergentes.

A aplicação permite gerenciar alunos, professores, turmas, disciplinas, notas e faltas em um único ambiente.

Além das funcionalidades acadêmicas, o projeto também trabalha com autenticação, controle de permissões, segurança de dados e integração com inteligência artificial.

## Funcionalidades

O sistema possui três tipos de usuários, cada um com permissões específicas.

### Alunos

* Consulta de notas e médias
* Acompanhamento de faltas e frequência
* Visualização da situação acadêmica
* Consulta de disciplinas e matrículas
* Assistente acadêmico com inteligência artificial

### Professores

* Consulta de turmas e disciplinas
* Lançamento e correção de notas
* Registro e atualização de faltas
* Acompanhamento dos alunos de suas turmas

### Administradores

* Gerenciamento de alunos e professores
* Cadastro de turmas e disciplinas
* Controle de matrículas
* Gerenciamento de usuários e permissões
* Consulta de registros de auditoria

---

## Assistente Acadêmico com IA

O sistema possui um assistente acadêmico integrado à API da NVIDIA.
O recurso permite que os alunos façam perguntas sobre seu desempenho, como:

* Como estão minhas notas?
* Quantas faltas tenho?
* Qual disciplina precisa de mais atenção?
* Como está minha frequência?

O assistente utiliza as informações acadêmicas fornecidas pelo sistema para responder às perguntas.
Os cálculos de médias e frequência são realizados pelo backend, enquanto a inteligência artificial auxilia na interpretação dos dados.

---

## Segurança

A segurança foi um dos principais pontos trabalhados durante o desenvolvimento.

O sistema utiliza:

* Autenticação com JWT
* Criptografia de senhas com BCrypt
* Controle de acesso por perfil
* Validação de permissões
* Recuperação de senha por e-mail
* Registro de ações administrativas
* Proteção de informações acadêmicas

Cada usuário possui acesso apenas às funcionalidades e informações permitidas para seu perfil.

---

## Tecnologias Utilizadas

| Tecnologia      | Finalidade                      |
| --------------- | ------------------------------- |
| Java 21         | Desenvolvimento do backend      |
| Spring Boot     | Estrutura da aplicação          |
| Spring Security | Autenticação e autorização      |
| MySQL           | Banco de dados                  |
| HTML e CSS      | Estrutura e estilização         |
| JavaScript      | Funcionalidades do frontend     |
| JWT             | Autenticação                    |
| NVIDIA API      | Assistente acadêmico com IA     |
| Resend          | Recuperação de senha por e-mail |
| Swagger         | Documentação da API             |
| Maven           | Gerenciamento de dependências   |

---

## Estrutura do Projeto

O sistema utiliza uma arquitetura em camadas, separando as responsabilidades da aplicação.

* **Controller:** recebe e processa as requisições.
* **Service:** concentra as regras de negócio.
* **Repository:** realiza a comunicação com o banco de dados.
* **Model:** representa as entidades do sistema.
* **DTO:** organiza os dados transferidos entre as camadas.

Essa organização facilita a manutenção e o desenvolvimento de novas funcionalidades.

---

## Como Executar

### Pré-requisitos

Para executar o projeto localmente, é necessário ter:

* Java 21
* MySQL
* Maven ou Maven Wrapper
* Configuração das variáveis de ambiente

### Configuração

Configure as variáveis de ambiente necessárias:

```env
DB_URL=
DB_USERNAME=
DB_PASSWORD=
JWT_SECRET=
NVIDIA_API_KEY=
RESEND_API_KEY=
MAIL_FROM=
APP_BASE_URL=
```

As chaves de API, senhas e demais informações sensíveis não devem ser publicadas no repositório.

### Iniciando a aplicação

No Windows:

```bash
mvnw.cmd spring-boot:run
```

No Linux ou macOS:

```bash
./mvnw spring-boot:run
```

Após iniciar, a aplicação estará disponível, por padrão, em:

`http://localhost:8080`

A documentação da API pode ser acessada em:

`http://localhost:8080/swagger-ui/index.html`

---

## Sobre o Desenvolvimento

O projeto foi desenvolvido como parte das atividades do curso de Análise e Desenvolvimento de Sistemas.
Durante o desenvolvimento, foram trabalhados conceitos de programação orientada a objetos, banco de dados, APIs REST, autenticação, segurança de aplicações e integração com serviços externos.
O Notely reúne esses conhecimentos em uma aplicação voltada ao gerenciamento de informações acadêmicas.

---

## Autora 

## **Lidiane Marcelino**

Estudante de Análise e Desenvolvimento de Sistemas.

[![GitHub](https://img.shields.io/badge/GitHub-0077B6?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/marcelinolidiane)

---

<div align="center">

</div>
