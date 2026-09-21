Projeto Java - Prática com Git

Projeto simples em Java criado para praticar Git e controle de versionamento.

📋 Sobre o projeto

O programa exibe algumas informações básicas no terminal, como:

Uma mensagem de boas-vindas;

O nome de uma pessoa;

A idade da pessoa.

O objetivo principal deste projeto não é desenvolver uma aplicação complexa, mas sim utilizar o código como base para praticar os principais comandos do Git.

🛠️ Tecnologias utilizadas

Java

Git

📁 Estrutura do projeto
projeto-git/
├── Main.java
└── README.md

▶️ Como executar

Certifique-se de que o Java esteja instalado na sua máquina.

Compile o programa:

javac Main.java


Depois execute:

java Main


A saída será semelhante a:

Olá, Git!
Nome: João
Idade: 20

🌱 Praticando Git

Este projeto pode ser utilizado para praticar um fluxo básico de versionamento.

1. Inicializar o repositório
git init

2. Verificar o estado dos arquivos
git status

3. Adicionar arquivos
git add .

4. Criar um commit
git commit -m "Cria programa inicial"

5. Criar uma branch
git branch nova-funcionalidade

6. Trocar para a branch
git switch nova-funcionalidade

7. Fazer alterações

Altere o arquivo Main.java, adicione uma nova funcionalidade e depois registre a alteração:

git add .
git commit -m "Adiciona nova funcionalidade"

8. Voltar para a branch principal
git switch main

9. Fazer merge
git merge nova-funcionalidade

🎯 Objetivos de aprendizado

Ao trabalhar neste projeto, você pode praticar:

Criar um repositório Git;

Fazer commits;

Consultar o histórico;

Criar e excluir branches;

Trocar entre branches;

Fazer merge;

Resolver conflitos;

Utilizar mensagens de commit;

Trabalhar com um repositório remoto.

📚 Comandos úteis

Ver o histórico de commits:

git log


Ver alterações nos arquivos:

git diff


Listar branches:

git branch


Excluir uma branch:

git branch -d nome-da-branch


Ver o estado atual do projeto:

git status

🚀 Próximos exercícios

Para continuar praticando, tente implementar algumas alterações no programa:

Adicionar uma variável para armazenar a cidade.

Exibir a cidade no terminal.

Criar uma função para exibir as informações do usuário.

Criar uma branch para cada nova funcionalidade.

Fazer commits separados para cada alteração.

Criar propositalmente um conflito entre duas branches e praticar sua resolução.

📄 Licença

Este projeto foi criado para fins de estudo e prática com Java e Git.
