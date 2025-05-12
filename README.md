# Sistema de Gerenciamento da Defesa Civil

Projeto desenvolvido como requisito para a disciplina de **Programação Orientada a Objetos** no curso de Ciência da Computação da Universidade Católica de Brasília (UCB), sob orientação do professor **Adam Smith Gontijo Brito de Assis**.

## 🧩 Descrição

Trata-se de uma aplicação **Full Stack** que visa auxiliar a Defesa Civil na gestão de informações de **famílias em situação de risco** e das **emergências** enfrentadas por uma cidade do sul do Brasil. A aplicação permite:

- Cadastro de famílias, membros e seus dados pessoais
- Classificação das famílias por **nível de risco**
- Registro de emergências: tipo, data, danos e localização
- Associação entre famílias e emergências
  
## 📸 Demonstração

Confira o funcionamento do sistema neste vídeo:

▶️ [Apresentação do Sistema de Gerenciamento da Defesa Civil](https://youtu.be/bFZFFEGuk9o)

## 🧠 Tecnologias Utilizadas

- 📌 **Back-End:** Java com **JPA/Hibernate** + **Spring Boot**
- 🖥️ **Front-End:** Swing (interface gráfica em Java)
- 🗃️ **Banco de Dados:** MySQL (com modelagem conceitual, lógica e física)
- 📦 Gerenciamento de dependências: Maven (`pom.xml`)
- 🔐 Segurança básica: Tela de login com validação de credenciais

## 📌 Funcionalidades Principais

- **Login** de usuários com controle de acesso
- **Cadastro de famílias** com dados como endereço e tipo de risco
- **Cadastro de membros**, incluindo upload de foto e dados de contato
- **Registro de emergências**, com associação a famílias afetadas
- **Validação de campos** e máscaras para CPF, telefone, data de nascimento
- **Efeitos visuais nos botões (hover)** para melhorar a UX
- **Modelo MVC** aplicado entre `View`, `Model` e `DAO`

## 👩‍💻 Equipe de Desenvolvimento
- Júlia Gabriela Gomes da Silva

- Lara Ewellen de Carvalho Rocha

- Luís Eduardo Brito Costa Melo

- Luiz Guilherme de Almeida Fernandes
