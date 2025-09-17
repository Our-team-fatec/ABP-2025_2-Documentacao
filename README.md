# 🐾 Da Vinci Pets

## 📚 Sobre o Projeto

O **Da Vinci Pets** é uma solução digital criada pela equipe **Da Vinci Team** com o objetivo de melhorar a adoção, o controle de saúde e a integração da comunidade PET.

---

## 🎯 Objetivos do Projeto

* **Adoção de PETs** com questionários para garantir responsabilidade.
* **Controle de Saúde**: vacinas, exames, consultas e medicamentos.
* **Comunidade PET**: integração com estabelecimentos pet-friendly, hotéis, creches, cuidadores, pet shops e veterinários.

---

## 🌍 Benefícios Sociais

* Bem-estar e saúde animal.
* Conscientização e educação para tutores.
* Inclusão social e promoção da adoção consciente.
* Segurança com carteirinhas digitais e QR Code para pets.
* Geração de dados úteis para campanhas de vacinação pública.

---

## 🔗 Repositórios Relacionados

* 📱 [SuperPET Mobile](https://github.com/Our-team-fatec/ABP-2025_2-Mobile)
* 🖥️ [SuperPET Server](https://github.com/Our-team-fatec/ABP-2025_2-Back)

---

### 🏁 Entregas de Sprints
Previsão de entrega das Sprints e relatórios:
| Sprint | Previsão de entrega | Status           | Histórico |
|:--:|:----------:|:-------------------|:-------------------------------------------------:|
| 01 | 16/09 - 07/10 | Em andamento | [ver relatório]() |
| 02 | 13/10 - 03/11 | Não iniciada | [ver relatório]() |
| 03 | 06/11 - 24/11 | Não iniciada | [ver relatório]() |

---

### 📋 1. Backlog de Produto (Histórias de Usuário)

| ID    | História do Usuário                                                                                               | Prioridade | Tipo  |
|-------|-------------------------------------------------------------------------------------------------------------------|------------|-------|
| US01  | Como *ONG/abrigo/user*, quero **publicar animais para adoção** com fotos, idade e histórico, para aumentar suas chances de adoção. | A | RF |
| US02  | Como *interessado em adoção*, quero **responder a questionários de adoção responsável** para garantir compatibilidade com o PET. | A | RF |
| US03  | Como *tutor*, quero **registrar meu PET com informações básicas (nome, raça, idade, peso)** para controlar sua saúde. | A | RF |
| US04  | Como *tutor*, quero **registrar vacinas, exames e consultas** para manter o histórico médico atualizado.             | A | RF |
| US05  | Como *tutor*, quero **receber notificações automáticas sobre vacinas obrigatórias (raiva, etc.)** para manter meu PET protegido. | A | RF |
| US06  | Como *tutor*, quero **ter uma carteirinha digital com QR Code** para facilitar a identificação do meu PET em caso de perda. | M | RF |
| US07  | Como *tutor*, quero **localizar clínicas, hotéis, creches e cuidadores próximos** usando geolocalização, para facilitar o acesso a serviços. | M | RF |
| US08  | Como *tutor*, quero **consultar dicas de cuidados e educação animal via chatbot**, para melhorar o bem-estar do meu PET. | M | RF |
| US09  | Como *tutor*, quero **avaliar e comentar serviços de pet shops, hotéis e veterinários**, para ajudar outros tutores. | B | RF |

---

### 📋 2. Classificação dos Requisitos

#### ✅ Requisitos Funcionais (RF)

| ID    | Requisito                                                                                     | Atende à História |
|-------|-----------------------------------------------------------------------------------------------|------------------|
| RF01  | O sistema deve permitir que ONGs/Users publiquem animais para adoção com informações completas.     | US01             |
| RF02  | O sistema deve disponibilizar questionários de adoção responsável.                            | US02             |
| RF03  | O sistema deve permitir o cadastro e gerenciamento de informações do PET.                     | US03             |
| RF04  | O sistema deve permitir o registro de vacinas, exames e consultas médicas.                    | US04             |
| RF05  | O sistema deve enviar notificações automáticas sobre vacinas obrigatórias.                    | US05             |
| RF06  | O sistema deve gerar uma carteirinha digital com QR Code.                                     | US06             |
| RF07  | O sistema deve exibir no mapa serviços cadastrados (clínicas, hotéis, cuidadores, etc.).      | US07             |
| RF08  | O sistema deve incluir chatbot com respostas pré-configuradas sobre cuidados com PETs.        | US08             |
| RF09  | O sistema deve permitir avaliações e comentários em serviços cadastrados.                     | US09             |

#### ✅ Requisitos Não Funcionais (RNF)

| ID    | Requisito                                                                 | Atende à História |
|-------|----------------------------------------------------------------------------|------------------|
| RNF01 | O sistema deve estar disponível em Android.                         | US01 – US09      |
| RNF02 | O sistema deve ter interface responsiva, acessível e intuitiva.            | US01, US02, US06, US07, US08      |
| RNF03 | O sistema deve garantir segurança de dados sensíveis (LGPD).               | US03 – US06      |
| RNF04 | O sistema deve suportar geolocalização com precisão mínima de 10m.         | US07             |

---

### 📌 3. Priorização das Histórias de Usuário

| Prioridade | Histórias de Usuário                            |
|------------|-------------------------------------------------|
| A (Alta)   | US01, US02, US03, US04, US05                   |
| M (Média)  | US06, US07, US08                                |
| B (Baixa)  | US09                                            |

---

## 🔧 Tecnologias utilizadas

### Backend
- Node.js + TypeScript
- Express.js
- MongoDB
- Jest

### Frontend (Mobile + Web)
- React Native (mobile)
- Jest

---

## 🎲  4. Modelagem do banco de dados
<img width="1181" height="704" alt="image" src="https://github.com/user-attachments/assets/821df6ff-4785-496b-bc1a-824a18deb406" />


## 👥 Equipe

|                                                                                                                                                  LinkedIn & GitHub                                                                                                                                                  | Integrantes                 | Função        |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------- | :------------ |
|               [![Linkedin](https://img.shields.io/badge/Linkedin-blue?style=flat-square\&logo=Linkedin\&logoColor=white)](https://www.linkedin.com/in/lucasrmc/) [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square\&logo=github\&logoColor=white)](https://github.com/LucasRbnc)              | Lucas Roberto M. Nascimento | Product Owner |
|             [![Linkedin](https://img.shields.io/badge/Linkedin-blue?style=flat-square\&logo=Linkedin\&logoColor=white)](https://www.linkedin.com/in/lucascostadwn/) [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square\&logo=github\&logoColor=white)](https://github.com/lucasdwn)            | Lucas Ferreira da Costa     | Scrum Master  |
|           [![Linkedin](https://img.shields.io/badge/Linkedin-blue?style=flat-square\&logo=Linkedin\&logoColor=white)](https://www.linkedin.com/in/aliceujunior/) [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square\&logo=github\&logoColor=white)](https://github.com/AliceuJunior)           | Aliceu Donizete F. Junior   | Dev Team      |
| [![Linkedin](https://img.shields.io/badge/Linkedin-blue?style=flat-square\&logo=Linkedin\&logoColor=white)](https://www.linkedin.com/in/andre-lucas-almeida-sales-156779251/) [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square\&logo=github\&logoColor=white)](https://github.com/andreluke) | André Lucas de A. Sales     | Dev Team      |
|           [![Linkedin](https://img.shields.io/badge/Linkedin-blue?style=flat-square\&logo=Linkedin\&logoColor=white)](https://www.linkedin.com/in/muril0gomes/) [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square\&logo=github\&logoColor=white)](https://github.com/MuriloGGSilva)           | Murilo Gomes da Silva       | Dev Team      |
|       [![Linkedin](https://img.shields.io/badge/Linkedin-blue?style=flat-square\&logo=Linkedin\&logoColor=white)](https://www.linkedin.com/in/larissa-candido-70b199298/) [![GitHub](https://img.shields.io/badge/GitHub-111217?style=flat-square\&logo=github\&logoColor=white)](https://github.com/larixyz)       | Larissa E. Barbosa Candido  | Dev Team      |
