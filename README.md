# crud-firestory-alunos


Atividade completa — CRUD com Firebase Cloud Firestore e Node.js
Vamos desenvolver a atividade da aula de Banco de Dados NoSQL com um sistema de gerenciamento de alunos, utilizando JavaScript, Node.js e Firebase Cloud Firestore.

O projeto terá um menu interativo no terminal, validação dos dados, operações CRUD e consultas por turma e data de nascimento.

CREATE — cadastrar aluno

READ — listar e consultar alunos

UPDATE — atualizar cadastro

DELETE — excluir cadastro

O Firestore armazena os dados em documentos organizados por coleções. No nosso caso, a coleção será alunos, e cada aluno terá seu próprio documento. 

Firebase

1. Baixe o projeto completo
CRUD Firestore — Node.js

Projeto completo em ZIP, com código-fonte e README.md

Baixar o projeto completo

O projeto contém:

crud-firestore/
├── src/
│   ├── firebase.js
│   ├── aluno.js
│   └── menu.js
├── .gitignore
├── package.json
├── README.md
└── serviceAccountKey.json  ← configurar localmente
2. Como executar o sistema
Depois de baixar e extrair o arquivo:

Abra a pasta crud-firestore no Visual Studio Code.

No terminal, execute:

npm install

Configure sua conexão com o Firebase e, depois, execute:

npm start

O programa apresentará um menu semelhante a este:

====== CRUD FIRESTORE: ALUNOS ======

1. Cadastrar aluno (CREATE)
2. Listar alunos (READ)
3. Atualizar aluno (UPDATE)
4. Excluir aluno (DELETE)
5. Consultar por turma
6. Consultar por data de nascimento
0. Sair

Escolha:
3. Configurar o Firebase
A conexão utiliza o Firebase Admin SDK.

Siga estes passos:

Acesse o Firebase Console.

Crie um projeto chamado CRUD Firestore Alunos.

Entre na opção Firestore Database.

Crie o banco de dados.

Acesse as configurações do projeto.

Entre em Contas de serviço.

Gere uma chave privada para o Admin SDK.

Salve o arquivo como serviceAccountKey.json na raiz do projeto.

Atenção: o arquivo da chave não deve ser publicado no GitHub. O .gitignore do projeto já está configurado para ignorá-lo.

4. Como testar o CRUD
Use os seguintes dados fictícios para testar:

Campo

Valor

Nome

Ana Souza

Turma

3DSB

Data de nascimento

2009-05-15

Ativo

true

Faça os testes nesta ordem:

Cadastre a Ana.

Liste os alunos e confira o ID do documento.

Atualize a turma para 3DSA.

Consulte os alunos da turma 3DSA.

Consulte pela data 2009-05-15.

Exclua o cadastro.

Liste novamente para verificar a exclusão.

5. Publicar no GitHub
Crie um repositório com o nome:

crud-firestore-alunos

Depois, envie os arquivos do projeto.

O README incluído explica a instalação, a estrutura, as funcionalidades e as evidências necessárias para a entrega.
