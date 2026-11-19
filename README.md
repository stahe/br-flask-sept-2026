# Introdução passo a passo ao framework web [Flask]

**Curso e código (setembro de 2026)**: 👉 **[https://stahe.github.io/br-flask-sept-2026/](https://stahe.github.io/br-flask-sept-2026/)**

## Autor

O código e o curso foram escritos inteiramente por **Claude**, a IA da Anthropic, que é o **autor único**, a pedido de Serge Tahé.

## Visão geral

Este curso apresenta um guia passo a passo para construir uma aplicação web MVC usando o framework **Flask** (Python). As páginas HTML são geradas pelo servidor usando views **Jinja2**, sem um framework JavaScript no lado do cliente.

Ele dá continuidade ao curso [Introdução passo a passo ao framework web [Spring MVC](https://stahe.github.io/br-springmvc-sept-2026/)], e segue exatamente a mesma progressão. Esse curso, por sua vez, seguia os cursos de [ASP.NET Core MVC](https://stahe.github.io/br-aspnetcoremvc-sept-2026/) e [NestJS](https://stahe.github.io/br-nestjs-html-sept-2026/). Os exemplos têm os mesmos números e abordam os mesmos tópicos: um leitor familiarizado com um desses cursos pode comparar os frameworks exemplo por exemplo.

O curso é dividido em duas partes:

- **28 exemplos curtos**, cada um focado em um conceito específico:
  - actions, roteamento, respostas e redirecionamentos;
  - binding de parâmetros e validação (Pydantic);
  - views Jinja2, templates e macros;
  - formulários WTForms, padrão Post/Redirect/Get e proteção contra CSRF;
  - internacionalização;
  - escopos de dados;
  - ciclo de vida da requisição;
  - autenticação JWT, papéis e CAPTCHA;
  - Arquitetura em camadas com SQLAlchemy e MySQL.
- **Um estudo de caso completo**: *RdvMedecins*, uma aplicação de agendamento de consultas para um consultório médico. Ela possui três papéis de usuário (administrador, médicos, pacientes), funciona em francês e inglês e é protegida contra bots. Todos os seus arquivos são comentados no curso.

## Tecnologias

Python 3.12+ · Flask 3.1 · Jinja2 · Werkzeug · Flask-WTF / WTForms · Pydantic · SQLAlchemy 2.1 · PyMySQL · PyJWT · bcrypt · Babel · waitress · Bootstrap 5.3 · MySQL 8 / MariaDB

## Pré-requisitos

- Python 3.12 ou mais recente;
- Visual Studio Code, com a extensão "Python" da Microsoft;
- MySQL 8 (por exemplo, com o Laragon no Windows) ou MariaDB;
- curl.

As instruções de instalação dessas ferramentas são fornecidas nos apêndices do curso.

## Conteúdo do repositório de código

- `examples/`: os 28 exemplos, cada um uma pequena aplicação Flask (porta 5000);
- `rdvmedecins2-flask/`: o estudo de caso (porta 8081), com seu script SQL e `README.md`;
- `directory.txt`: a estrutura completa de diretórios.
