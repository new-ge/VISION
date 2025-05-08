![Image](https://github.com/user-attachments/assets/ec1d49a8-64c7-41c8-af4a-3772f4eaadf8)
<span id="sobre">

## 📍 Introdução

Este projeto foi desenvolvido pelo grupo **New Generation**, formado por estudantes do 5º semestre de Tecnologia em Banco de Dados da Fatec São José dos Campos.

A proposta é criar a **Vision**, uma ferramenta de visualização de indicadores integrada à plataforma [Taiga](https://taiga.io/), com foco em tornar a gestão de projetos mais eficiente, visual e transparente. A Vision permitirá que usuários acompanhem o progresso de tarefas através de dados como tempo médio de finalização, distribuição de responsabilidades, uso de etiquetas e mais.

O projeto é uma solução sob medida para a **Youtan**, empresa especializada no desenvolvimento de softwares e aplicativos sob demanda desde 2002. Localizada no Parque Tecnológico de São José dos Campos e membro do TIC Vale — o maior cluster de TI do Brasil — a Youtan atua com metodologias ágeis e tecnologias modernas para transformar ideias em soluções digitais para Web, Desktop e Mobile. Além disso, oferece o **SIGI**, seu próprio ERP em modelo SaaS, voltado para empresas B2B de pequeno e médio porte.

<br>

> Desenvolvimento ágil;

> Gerenciamento de projetos;


<span id="equipe"> 
     
## Contribuidores 👨‍💻👩‍💻


Nome | Função | Networking | Identificação
--- | --- | --- | --- | 
Amanda Vannucci | Scrum Master |   <a href="https://github.com/Amandavannuccic"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/amanda-vannucci/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> |    <a href="" ><img src="https://avatars.githubusercontent.com/u/127263243?v=4" width="60"></a>
Guilherme Wunderlich | Product Owner | <a href="https://github.com/wunderlich-15"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white5" alt="GitHub"></a> <a href="https://www.linkedin.com/in/guilherme-wunderlich-aa56a2228/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> |<img src="https://avatars.githubusercontent.com/u/74203181?v=4" width="60">|
Cauan Barbaglio| Developer | <a href="https://github.com/Cauanvmb"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a><a href="https://www.linkedin.com/in/cauan-barbaglio/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>| <a href="" ><img src="https://avatars.githubusercontent.com/u/127343662?v=4" width="60"></a>
Naiara Santos | Developer| <a href="https://github.com/NaiaraSantos3"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white5" alt="GitHub"></a> <a href="https://www.linkedin.com/in/naiara-santos-73b83a186/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> |<img src="https://avatars.githubusercontent.com/u/127265827?v=4" width="60">|
Raul Neto | Developer | <a href="https://github.com/raulnt"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/raul-neto-b51b24157/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> |<img src="https://avatars.githubusercontent.com/u/127263427?v=4" width="60">|
Vinícius Chaves| Developer |<a href="https://github.com/ChavesVini"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a> <a href="https://www.linkedin.com/in/vin%C3%ADcius-chaves-197353244/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> |<img src="https://media.licdn.com/dms/image/v2/D4D03AQGwf2fzaEOz3g/profile-displayphoto-shrink_800_800/profile-displayphoto-shrink_800_800/0/1705451376647?e=1746662400&v=beta&t=0aWzeMRwY7tiG0uCqSFqFRjNnmgaXlJsZGxeV0nwEs8" width="60">|

## Requisitos Funcionais

<details>
     
<summary>Clique aqui</summary>

**ID**|**Itens** |
-- | --|
RF1|Criar um dashboard com os indicadores:|
RF2|Quantidade de cards por etiqueta;|
RF3|Quantidade de cards criados por período;| 
RF4|Quantidade de cards finalizados por período;| 
RF5|Quantidade de cards por status (coluna do kanban);| 
RF6|Tempo médio de execução do card;|
RF7|Cards por colaborador;|
RF8|Retrabalhos.|
RF9|Indicadores poderão ser acessados por níveis de acesso (times diferentes);| 
RF10|Criar uma API para integração com outro sistema (Trello, Jira...);|
</details>

## Requisitos Não Funcionais

<details>
     
<summary>Clique aqui</summary>

**ID**|**Itens** |
-- | --|
RFN1|Documentação API – Application Programming Interface;|
RFN2|Responsivo;|
RFN3|Manual do Usuário;|
RFN4|Modelagem de Banco de Dados;| 


</details>

<span id="backlog">
     
## Product Backlog 🔍


| **Rank** | **Épico** | **User Storie** | **Estimativa** | **Requisito do Parceiro** | **Status**|
|---------|-----------|-----------------|---------------|--------------------------|---------------|
| 1 | Dashboard de Indicadores | Como um operador, quero visualizar a quantidade de cards por etiqueta, para que eu possa entender a distribuição das minhas tarefas. | 1 | RF1, RF2 | ✅ | 
| 2 | Dashboard de Indicadores | Como um operador, quero visualizar a quantidade de cards criados por período, para que eu possa acompanhar a criação das minhas tarefas. | 1 | RF1, RF3, RFN2, RFN3 | ✅ | 
| 3 | Dashboard de Indicadores | Como um operador, quero visualizar a quantidade de cards finalizados por período para que eu possa acompanhar a entrega de tarefas ao longo do tempo. | 1 | RF1, RF4, RFN2 | ✅ | 
| 4 | Dashboard de Indicadores | Como um operador, quero visualizar a quantidade de cards por status, para que eu possa entender o andamento das tarefas. | 1 | RF1, RF5 | ✅ | 
| 5 | Dashboard de Indicadores | Como um operador, quero visualizar o tempo médio de execução de cards, para que eu possa analisar a minha eficiência no processo de desenvolvimento. | 2 | RF1, RF6, RFN2 | 🔧 |
| 6 | Dashboard de Indicadores | Como um operador, quero visualizar os retrabalhos, para que eu possa acompanhar os meus cards que retornaram para o desenvolvimento devido a bugs. | 2 | RF1, RF8, RFN2 | ✅ |
| 7 | Dashboard de Indicadores | Como um admin, quero visualizar a quantidade de cards por status, para que eu possa entender o andamento das tarefas. | 2 | RF1, RF5 | ✅ | 
| 8 | Dashboard de Indicadores | Como um admin, quero visualizar o tempo médio de execução de cards, para que eu possa analisar a eficiência no processo de desenvolvimento. | 2 | RF1, RF6 | ✅ |
| 9 | Dashboard de Indicadores | Como um admin, quero visualizar os cards por colaborador, para que eu possa analisar a distribuição de tarefas. | 2 | RF1, RF7 | ✅ |
| 10 | Dashboard de Indicadores | Como um admin, quero visualizar os retrabalhos, para que eu possa acompanhar os cards que retornaram para o desenvolvimento devido a bugs. | 2 | RF1, RF8 | ✅ | 
| 11 | Dashboard de Indicadores | Como gestor, quero visualizar indicadores de meu time, para que eu possa avaliar a performance dos colaboradores e do time como um todo. | 2 | RF1, RNF2 | 🔧 |  
| 12 | Dashboard de Indicadores | Como gestor, quero visualizar os retrabalhos relacionados ao meu projeto, para que eu possa monitorar a qualidade do trabalho e identificar áreas que precisam de melhorias. | 2 | RF1, RF8 | ✅ | 
| 19 | Autenticação | Como um usuário, eu desejo que o sistema realize a autenticação do usuário, para que apenas usuários autorizados possam acessar as funcionalidades do sistema. | 2 | RF9, RFN1 | ✅ |
| 13 | Níveis de Acesso | Como admin, quero configurar os níveis de acesso para diferentes tipos de usuários (Operador, Gestor, Admin), para garantir que as permissões sejam corretamente atribuídas. | 2 | RF9, RFN1, RFN4 | ✅ | 
| 14 | Gestão de Acessos | Como admin, quero garantir que apenas um único gestor tenha acesso aos projetos do seu time, para evitar conflitos de acesso entre diferentes gestores. | 3 | RF9, RFN1, RFN4 | 🔧 |
| 15 | Dashboard de Indicadores | Como um admin, quero visualizar indicadores relacionados a todos os cards de todos os times, para que eu possa acompanhar a carga de trabalho e a distribuição das tarefas. | 3 | RF01, RFN01, RFN02, RFN03 | 🔧 |
| 16 | Dashboard de Indicadores | Como um admin, quero visualizar a quantidade de cards por etiqueta, para que eu possa entender a distribuição de tarefas. | 3 | RF1, RF2 | 🔧 | 
| 17 | Dashboard de Indicadores | Como um admin, quero visualizar a quantidade de cards criados por período, para que eu possa acompanhar a criação das tarefas ao longo do tempo. | 3 | RF1, RF3 | 🔧 |
| 18 | Dashboard de Indicadores | Como um admin, quero visualizar a quantidade de cards finalizados por período, para que eu possa acompanhar a entrega das tarefas ao longo do tempo. | 3 | RF1, RF4 | 🔧 | 



<span id="cronograma">

## Cronograma de Entregas 🗓️

Sprint| Início| Entrega  
--- | --- | ---
Kick off do projeto| 27/02/2025| -------------
Sprint 1| 10/03/2025| 30/03/2025 
Sprint 2| 07/04/2025| 27/04/2025 
Sprint 3| 05/05/2025| 25/05/2025
Feira de Soluções| 29/05/2024| -------------


## Resumo de Sprints 📋

<details>
     
<summary>Sprint 1</summary>

<h2>Objetivos da Sprint</h2>

<p>Nesta sprint, foi planejada a entrega de um Dashboard com indicadores do Operador, incluindo:</p>

<ul>
  <li>✅ Quantidade de cards por etiqueta.</li>
  <li>✅ Quantidade de cards criados por período.</li>
  <li>✅ Quantidade de cards finalizados por período.</li>
  <li>✅ Quantidade de cards por status.</li>
</ul>

<p>A equipe conseguiu concluir todas as entregas planejadas dentro do prazo, garantindo que o cliente recebesse o dashboard conforme especificado. 🚀</p>

 <details>
    <summary>VISION - Tela Operador (Sprint 1) </summary>
    <img src="https://github.com/user-attachments/assets/4453ff97-9923-48d2-af6a-29099248f3e0">
  </details>


<h1>Sprint 1 - Relatório de Resultados</h1>

<h2>Pontos Positivos</h2>

<p>Durante esta sprint, a <strong>comunicação</strong> e <strong>colaboração</strong> entre a equipe foram pontos-chave para o sucesso da entrega. O time manteve um fluxo contínuo de informações, garantindo que todos estivessem alinhados com as demandas e objetivos.</p>

<p>Além disso, a colaboração entre os membros da equipe foi essencial para otimizar o desenvolvimento. Houve um forte espírito de cooperação e compartilhamento de conhecimentos sempre que necessário. Esse trabalho conjunto refletiu diretamente na <strong>eficiência</strong> e <strong>qualidade</strong> da entrega, demonstrando o comprometimento de todos com o resultado final.</p>

<p>Um dos grandes diferenciais desta sprint foi a criação de um <strong>grupo no Teams</strong>, centralizando todas as informações do processo, com acesso fácil para as dailys presenciais e remotas. Além disso, foram disponibilizados <strong>vídeos explicativos</strong> para guiar a equipe em pontos mais complexos do projeto, facilitando a consulta rápida e o entendimento de tarefas específicas.</p>

<p>Esse formato contribuiu para a <strong>melhoria na produtividade</strong>, pois permitiu que todos estivessem alinhados e com acesso rápido ao conteúdo necessário, sem a necessidade de longas explicações. Isso garantiu mais eficiência nas entregas e uma sprint mais fluida.</p>

  <details>
    <summary>VISION - Organização do Time (Microsoft Teams)</summary>
    <img src="https://github.com/user-attachments/assets/90f3baaa-90b4-4547-bfc2-34bd39c0b912" alt="Imagem da Sprint">
  </details>

<h2>Desafios e Obstáculos</h2>

<p>Durante a sprint, enfrentamos alguns <strong>desafios</strong>, como níveis de conhecimento e visões muito diferentes entre os membros da equipe, o que exigiu alinhamentos contínuos. Além disso, o pouco tempo disponível, considerando a alta demanda de tarefas, gerou dificuldades na gestão do ritmo de trabalho. Também houve a adaptação de integrantes ao grupo e à rotina, o que exigiu tempo extra de integração.</p>

<p>Outro obstáculo significativo foi a <strong>necessidade de ajustar a estrutura do banco de dados</strong> na primeira semana, o que impactou as tasks. Na última semana, tivemos que mudar o banco de dados, pois ele se mostrou incompatível com o SonarQube, o que gerou mais ajustes. Apesar desses desafios, conseguimos superá-los com colaboração e esforço conjunto, permitindo a conclusão da sprint dentro dos objetivos propostos.</p>

<h2>Lições Aprendidas</h2>

<p>Durante esta sprint, enfrentamos alguns desafios que nos trouxeram importantes lições. A <strong>divergência de conhecimentos e visões</strong> entre os membros exigiu alinhamentos constantes. Para a próxima sprint, será fundamental ter <strong>expectativas e responsabilidades mais claras</strong> desde o início, reduzindo a necessidade de ajustes ao longo do processo.</p>

<p>O <strong>pouco tempo disponível</strong> e a <strong>alta demanda de tarefas</strong> dificultaram a gestão do ritmo de trabalho. Para melhorar, precisaremos de um <strong>planejamento mais realista</strong>, com <strong>priorização mais precisa</strong> das tarefas e do escopo.</p>

<p>A <strong>adaptação dos integrantes</strong> já foi superada, e para futuras sprints, podemos focar em um <strong>processo de integração mais ágil</strong> para novos membros.</p>

<p>A questão do <strong>ajuste da estrutura do banco de dados</strong> e a <strong>troca de banco de dados devido à incompatibilidade com o SonarQube</strong> foi resolvida, e <strong>não será mais necessário inserir tecnologias nas próximas sprints</strong>. No entanto, essa situação destacou a importância de <strong>validar requisitos técnicos e tecnológicos mais cedo</strong> no processo de planejamento para evitar retrabalho e ajustes imprevistos.</p>

<p>O uso do <strong>Kanban</strong> na primeira sprint ajudou no acompanhamento das tasks, mas o <strong>burndown</strong> foi impactado pela forma como organizamos as tasks no Jira. Para a próxima sprint, <strong>continuaremos com o Kanban</strong>, mas ajustaremos a gestão das tarefas para possibilitar o uso eficaz do burndown, mantendo o acompanhamento do progresso de forma mais ágil e precisa.</p>

<a href="https://www.canva.com/design/DAGisCtEoOY/fr7PqMjUKvOPr65X_Eoxkg/edit?utm_content=DAGisCtEoOY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton">Apresentação da Sprint</a>


</details>

<details>

<summary>Sprint 2</summary>

📌 Sprint Report – Projeto VISION

🧭 Objetivos da Sprint

Nesta sprint, tivemos como foco:

- Migração parcial da documentação do Teams para o Jira.
- Organização e estruturação do fluxo de tarefas.
- Alinhamento da equipe para continuidade do projeto.

Nem todas as entregas planejadas foram concluídas, mas houve progresso significativo em pontos estruturais. A documentação já disponível no Teams começou a ser transferida para o Jira, o que trará maior visibilidade e rastreabilidade para as próximas etapas.

---

✅ Pontos Positivos

- **Centralização de Informações**: O Teams continuou sendo a principal ferramenta de comunicação e organização, o que garantiu uma base sólida para as dailys e acompanhamento do progresso.
- **Documentação**: Iniciamos com sucesso a migração dos registros para o Jira.
- **Decisão Coletiva**: A saída de um integrante do grupo foi realizada por meio de votação unânime, refletindo um processo maduro e bem conduzido.

---

⚠️ Desafios e Obstáculos

- **Saída de Membro**: A equipe passou por uma reestruturação após a saída de um integrante, o que exigiu redistribuição de responsabilidades.
- **Entregas Incompletas**: Algumas tasks não foram concluídas, impactadas pelo tempo disponível e reorganização interna.

---

💡 Lições Aprendidas

- **Planejamento Realista**: Precisamos ajustar o escopo e a priorização das tarefas de acordo com a real capacidade do time.
- **Integração de Ferramentas**: A adoção do Jira deve ser concluída nas próximas sprints para otimizar o acompanhamento e gestão das tasks.
- **Comunicação Clara**: O processo de decisão coletiva foi eficaz. Manter esse padrão de alinhamento será essencial para os próximos ciclos.

---

📂 Documentação

- Documentação atual: [Teams (acesso interno)](https://teams.microsoft.com/)
- Migração em andamento para: [Jira (em progresso)](https://www.atlassian.com/software/jira)

</details>


<datails>
     
<summary>Sprint 3</summary>

</details>

<span id="burndown">

## Burndown 🔥

<details>
     
<summary>Sprint 1</summary>

![image](https://github.com/user-attachments/assets/436c9005-8dcf-440f-abf0-a8d0d336483a)

</details>

<details>

<summary>Sprint 2</summary>

![image](https://github.com/user-attachments/assets/75b08ab9-7813-4b10-835b-47ec562b1c4f)
</details>

<details>

<summary>Sprint 3</summary>


</details>

<span id="docs">

## Testes SonarQube 📑
<details>
     
<summary>Sprint 1</summary>

![image](https://github.com/user-attachments/assets/12e993ec-f295-4136-b792-162460b5e3ec)

</details>

<details>

<summary>Sprint 2</summary>

</details>

<details>

<summary>Sprint 3</summary>


</details>


## Documentação 📜

<a href="https://www.figma.com/design/0fPK99OjIhPviwxL9N9pFi/Vision?node-id=0-1&t=aPUYPgpY4FKNfvbQ-1">Wireframe do Projeto</a>


  
## Tecnologias Utilizadas 💻
  
![Image](https://github.com/user-attachments/assets/2faba05c-1bfc-4937-b29c-5250e36ef626)

<span id = tecnologias>
