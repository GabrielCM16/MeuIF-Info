# MeuIF 
**[Download do Aplicativo Android](MeuIF.apk)**

**[WebSite Multiplataforma](https://meuif-15823.web.app/)**

**[Artigo Do Projeto](Artigo-MeuIF.pdf)**

## MeuIF: um aplicativo para o gerenciamento de atividades acadêmicas, frequência escolar e otimização dos procedimentos da seção pedagógica do IFPR Campus Cascavel
**MeuIF: managing application for academic activities, school attendance and optimizing procedures in the pedagogical section of the IFPR Campus Cascavel**

<div align="center">
    <img src="imagens/logogif.gif" alt="logo animada" width="400">
</div>

---

**Autores:**
- Gabriel Costa de Moraes
- Heloísa Raquel Siebeneichler
- Fernando Alves de Lima
- Odair Moreira de Souza

---

## Resumo

No âmbito do Instituto Federal do Paraná, Campus Cascavel, surgiu a necessidade de desenvolver um software capaz de otimizar tarefas diárias dos alunos e da Seção Pedagógica e de Assuntos Educacionais (SEPAE). Nesse contexto, este trabalho realizou o desenvolvimento do aplicativo MeuIF, voltado para dispositivos Android, que auxilia a SEPAE na identificação da evasão escolar, otimização dos procedimentos da seção pedagógica e gerenciamento de atividades acadêmicas do IFPR Campus Cascavel.

## Funcionalidades Gerais

- Login e Cadastro com matrícula 
  - Login e Cadastro via Firebase Authentication com e-mail e senha
  - Recuperação de senha por e-mail

- Carteirinha de identificação pessoal 
  - QR Code identificando cada aluno

- Chamada de turma
  - Chamada realizada pelo líder da turma 
  - Visualização via app e download de PDF para a SEPAE
 
- Registro de acesso ao campus
  - Registro de entradas e saídas do campus para a SEPAE 
  - Registros de entradas e saídas pessoais
 
- Registro de quantidade PNAE 
  - Programa Nacional de Alimentação Escolar (PNAE)
  - Registro para controle de quantidade 
  - Cardápio diário
  - Gráficos de quantidade

- Autorizações 
  - Autorizações de entrada atrasada e saída antecipada 
  - Autorização requisitada pelo aluno e disponibilizada no app pela SEPAE
  
- Gerenciamento de perfis 
  - Permissões de Usuário
  - Controle de Acesso de conta
  - Gerenciamento de Acesso

## Desenvolvimento

O desenvolvimento do aplicativo MeuIF foi implementado no ambiente do Android Studio, empregando a linguagem de programação Java e utilizando a infraestrutura de computação em nuvem Google Cloud Platform.

O servidor backend é desenvolvido em Node.js, aproveitando a robustez e a escalabilidade dessa plataforma. A seguir, detalhamos as principais tecnologias e serviços Firebase que integram nossa infraestrutura:

- Firebase Functions: Utilizamos funções serverless do Firebase para executar a lógica backend. Isso nos permite escalar automaticamente e pagar apenas pelos recursos utilizados, sem a necessidade de gerenciar servidores.

- Firebase Hosting: O Firebase Hosting é utilizado para hospedar tanto a aplicação web quanto as funções de backend, garantindo entrega rápida e segura de conteúdo.

- Firebase Firestore Database: Para armazenamento de dados, optamos pelo Firestore, um banco de dados NoSQL que permite a sincronização em tempo real e suporte offline, essencial para uma experiência de usuário fluida.

- Firebase Storage: O Firebase Storage é empregado para armazenar e servir arquivos de maneira eficiente e segura, como imagens, vídeos e documentos.

- Firebase Events: A integração com Firebase Events nos permite rastrear e responder a eventos específicos dentro da aplicação, como interações de usuários ou atualizações de dados.

- Firebase Analytics: Com Firebase Analytics, obtemos insights detalhados sobre o comportamento dos usuários, o que nos ajuda a tomar decisões informadas para melhorar a aplicação continuamente.

## Conclusão

Em conclusão, o desenvolvimento do aplicativo MeuIF representa um avanço significativo na otimização e simplificação das atividades diárias dos alunos e da SEPAE, atendendo à necessidade premente de aprimoramento das operações.

Com base nos resultados do teste de usabilidade, observamos uma receptividade positiva dos estudantes, líderes de sala e a SEPAE em relação às funcionalidades do aplicativo, evidenciando sua praticidade e eficácia no contexto da instituição. 

<div align="center">
  <img src="imagens/GraficoUsoGeral.png" alt="Grafico Uso Geral" width="250">
</div>

<div align="center">
  <img src="imagens/UsabilidadeGeral.png" alt="Usabilidade Geral" >
</div>

---

© 2023 Gabriel C. Moraes & Heloísa Raquel.
