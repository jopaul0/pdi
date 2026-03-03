# <img height="55" width="55" alt="PDI logo" src="src/main/resources/com/dottec/pdi/project/pdi/static/img/logo.png"> PDI
Projeto acadêmico com <a href="https://youtan.com.br" target="_blank"> Youtan</a>.

<br>
<br>

## Objetivo 🎯
Este programa foi desenvolvido para otimizar o processo de criação e gestão de planos de desenvolvimento individual (PDIs). Ele oferece uma solução centralizada para líderes que buscam estruturar, monitorar e alcançar metas de crescimento de forma eficiente, promovendo uma cultura de melhoria contínua e desenvolvimento de competências.

<br>
<br>

## Instalação 🛠️

- Programas necessários: [MySQL](https://www.mysql.com/), [MySQL Workbench](https://www.mysql.com/products/workbench/), [Git](https://git-scm.com/) e [Java](https://www.java.com/en/).

<br>

1. [Ative o servidor MySQL](https://youtu.be/u96rVINbAUI?si=vAKutvf2RUC8Z7oL) e [abra](https://youtu.be/q0EBUXTQQRY?si=ynDUgV0q8uhTZ4VP) o [banco de dados](documents/database.sql) no MySQL workbench.

2. Copie esse repositório usando Git:

```
git clone https://github.com/dottecteam/PDI.git
```

3. Dentro da pasta "PDI", crie um arquivo chamado ".env" com as seguintes informações:

```
DB_URL= // caminho do banco de dados, exemplo: jdbc:mysql://localhost:3306/database
DB_USER= // nome de usuário do servidor, exemplo: root
DB_PASSWORD= // senha do servidor, exemplo: root
```

4. Abra o [arquivo principal](src/main/java/com/dottec/pdi/project/pdi/Application.java).

<br>
<br>

## Product backlog 📋

<br>

| Rank | Prioridade | User Story | Sprint |
| :--- | :--- | :--- | :--- |
| #01 | Alta | Como RH e Gerentes, quero poder registrar um colaborador, para acompanhar seu desempenho. | Sprint 1 |
| #02 | Alta | Como RH e Gerentes, quero gerenciar os colaboradores registrados, para controlar os PDIs. | Sprint 1 |
| #03 | Alta | Como RH e Gerentes, quero adicionar metas ao PDI de um colaborador, para alinhar seu desenvolvimento individual aos objetivos da empresa. | Sprint 1 |
| #04 | Alta | Como RH e Gerentes, quero gerenciar as metas registradas em um PDI, para poder alterar prazos, status e categorias. | Sprint 1 |
| #05 | Alta | Como RH e Gerentes, quero categorizar metas por hard e soft skills, para facilitar o acompanhamento do progresso dos colaboradores através do dashboard. | Sprint 1 |
| #06 | Alta | Como RH e Gerentes, quero gerenciar as categorias, para fazer análises mais claras e específicas dos PDIs. | Sprint 1 |
| #07 | Média | Como RH, quero adicionar e gerenciar setores da empresa, para organizar os PDIs e apoiar a gestão de conhecimento e tomada de decisão. | Sprint 2 |
| #08 | Média | Como RH e Gerentes, quero um dashboard, para análises estatísticas e visuais dos PDIs. | Sprint 2 |
| #09 | Média | Como RH, quero gerenciar as contas dos Gerentes, para controlar acessos ao software. | Sprint 2 |
| #10 | Média | Como RH e Gerentes, quero fazer login com minhas credenciais, para acessar o software. | Sprint 2 |
| #11 | Média | Como Gerente de Setor, quero ter acesso limitado aos PDIs do meu setor, para manter a segurança e organização das informações. | Sprint 2 |
| #12 | Baixa | Como RH e Gerentes, quero uma interface responsiva e amigável, para ter uma experiência agradável ao usar o software. | Sprint 3 |
| #13 | Baixa | Como RH e Gerentes, quero fazer download das informações do Dashboard para planilhas, para fazer análises externas. | Sprint 3 |
| #14 | Baixa | Como RH e Gerentes, quero poder fazer o upload de documentos (como certificados) ao PDI, para documentar o progresso do colaborador. | Sprint 3 |
| #15 | Baixa | Como Gerente de Setor, quero receber lembretes sobre eventos, para me manter inteirado aos prazos. | Sprint 3 |
| #16 | Baixa | Como RH, quero criar modelos de metas, para agilizar sua incrementação aos PDIs. | Sprint 3 |

<br>
<br>

## Mínimo produto viável 📸

<br>

Sprint 1 - <a href="https://www.youtube.com/watch?v=D2EGllhOuvc" target="_blank"> Cadastro de colaboradores</a> ✔️
<br>
Sprint 2 - <a href="https://youtu.be/Jl933PCuGKg" target="_blank"> Dashboard e login</a> ✔️

<br>
<br>

## Tecnologias utilizadas 💻

<br>

<div align="center">
  
  <a href="https://notion.com" target="_blank"> <img align="center" width="70" height="70" alt="Notion logo" src="https://github.com/user-attachments/assets/34482bee-28fe-411f-bebe-6dead80cb3ad"/> </a>
  <a href="https://figma.com" target="_blank"> <img align="center" width="45" height="65" alt="Figma logo" src="https://github.com/user-attachments/assets/313c9e21-96c6-45c8-8f3a-99ba1ca4d102"/> </a>
  <a href="https://lucidchart.com" target="_blank"> <img align="center" width="75" height="75" alt="Lucidchart logo" src="https://github.com/user-attachments/assets/ce117381-8522-4f81-8dc5-05272ab219fa"/> </a>
  <a href="https://mysql.com" target="_blank"> <img align="center" width="95" height="95" alt="MySQL logo" src="https://github.com/user-attachments/assets/f1195336-90f2-4d18-a0a4-aaea693ec11b"/> </a>
  <a href="https://java.com" target="_blank"> <img align="center" width="75" height="75" alt="Java logo" src="https://github.com/user-attachments/assets/2928f4d8-b02b-4782-a7da-8bec7ceab455"/> </a>
  <a href="https://openjfx.io" target="_blank"> <img align="center" width="95" height="95" alt="JavaFx logo" src="https://github.com/user-attachments/assets/410b881c-8d26-4883-96ef-4d3601965e5a"/> </a>
  <a href="https://git-scm.com" target="_blank"> <img align="center" width="65" height="65" alt="Git logo" src="https://github.com/user-attachments/assets/988ae601-046f-47c1-89eb-f020d4d917fb"/> </a>

</div>

<br>

## Equipe Scrum 👥

<br>

<div align="center">

Nome | Função | LinkedIn | GitHub
-|-|-|-
Ramon Varjão | Scrum Master | [![LinkedIn](https://img.shields.io/badge/linkedin-blue?style=for-the-badge)](https://www.linkedin.com/in/ramon-varjao) | <a href="https://github.com/ramonjune"> <img src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github"/> </a>
Kauan Domingues | Product Owner | [![LinkedIn](https://img.shields.io/badge/linkedin-blue?style=for-the-badge)](https://linkedin.com/in/kauandomingues) | <a href="https://github.com/KauanDomingues"> <img src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github"/> </a>
Breno Reis | Developer | [![LinkedIn](https://img.shields.io/badge/linkedin-blue?style=for-the-badge)](https://www.linkedin.com/in/breno-reis-893009321) | <a href="https://github.com/brenoviske"> <img src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github"/> </a>
Cauã Mehiel | Developer | [![LinkedIn](https://img.shields.io/badge/linkedin-blue?style=for-the-badge)](https://www.linkedin.com/in/cau%C3%A3-cursino-748485235) | <a href="https://github.com/CauaCurisno1446"> <img src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github"/> </a>
Davi Andrade | Developer | [![LinkedIn](https://img.shields.io/badge/linkedin-blue?style=for-the-badge)](https://www.linkedin.com/in/daviandrade007) | <a href="https://github.com/aandrade007"> <img src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github"/> </a>
Gabriel Borges | Developer | [![LinkedIn](https://img.shields.io/badge/linkedin-blue?style=for-the-badge)](https://www.linkedin.com/in/gabriel-borges-toledo) | <a href="https://github.com/Gabe-Borges"> <img src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github"/> </a>
Jessica Katayama | Developer | [![LinkedIn](https://img.shields.io/badge/linkedin-blue?style=for-the-badge)](https://www.linkedin.com/in/jessicakatayama) | <a href="https://github.com/JessicaKatayama"> <img src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github"/> </a>
João Paulo | Developer | [![LinkedIn](https://img.shields.io/badge/linkedin-blue?style=for-the-badge)](https://www.linkedin.com/in/joaosantos02) | <a href="https://github.com/jopaul0"> <img src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github"/> </a>
Nicolas Anderson | Developer | [![LinkedIn](https://img.shields.io/badge/linkedin-blue?style=for-the-badge)](https://www.linkedin.com/in/nicolas-anderson-34b082302) | <a href="https://github.com/Slot148"> <img src="https://img.shields.io/badge/github-black?style=for-the-badge&logo=github"/> </a>

</div>
