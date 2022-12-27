# Repositório do desafio de projeto sobre Git/GitHub 🖥️
O objetivo desse repositório foi reforçar o meu conhecimento em Git com um desafio de projeto totalmente prático, onde executei todos os passos para a criação, atualização e sincronização de um repositório no GitHub. Dessa forma, poderei compartilhar minhas anotações e exercícios em um repositório próprio. Criando assim, o primeiro (de muitos) projetos do meu portfólio. 

# Criação, atualização e sincronização de um repositório no GitHub: 

## *Criação de um novo repositório 🆕*

#### Passo 1: Acesse o GitHub e crie um novo repositório.

A primeira etapa é a criação de um novo repositório diretamente no GitHub. Para isso, basta clicar em **Repositories** e em seguida no botão **New**. Você será redirecionado para o "*Create a New Repository*".

- Escolher um nome que tenha relação com o projeto em questão;
- Não esquecer de selecionar "*Public*" para que o repositório fique visível para todos;
- Selecionar o *Readme.md*, caso queira incluir uma introdução/descrição mais detalhada ao seu projeto. 

➡️ Clique no botão **CREATE REPOSITORY**. 

#### Passo 2: Com o repositório criado e selecionado, clique no botão <> **CODE**. 

Siga os seguintes passos: *Local* --> *Clone* --> *HTTPS* = Copie o **link HTTPS**. 

#### Passo 3: Selecione a pasta local onde ficarão salvos os arquivos commitados no GitHub.

1. Clique com o botão direito do mouse e selecione a opção *"Git Bash Here"*. Vai abrir um **Console**. 

2. Digite "`git clone`" e cole o HTTPS copiado do GitHub. Aperte enter e aguarde. 

   Ao abrir a pasta local recém criada, os arquivos que estiverem no GitHub já aparecerão na pasta.

`Dica: não feche o console ainda` 



## *Como adicionar novos arquivos na pasta local e sincronizar com o GitHub* 💻

Para adicionar novos arquivos na pasta local é bem simples, basta copia-los dentro da pasta criada anteriormente para o Github. Nesse passo os arquivos já devem estar atualizados. 

#### Passo 1: Com o console aberto, digite "`git status`". Normalmente irá aparecer uma frase em vermelho, reconhecendo que tem um novo arquivo que ainda não foi commitado.

###### Frase em vermelho: Use "git add <file> ..." to include in what will be committed

Para incluir esses novos arquivos, digite no **console**: 

- `git add .` ou `git add -A`

Não esqueça de digitar *`git status`* novamente para conferir se os arquivos já foram commitados. 

###### Frase em verde: new file "nome do arquivo adicionado..."

**Atenção:** Esses passos servem para fazer adições no `controle de versão local`, os arquivos ainda não atualizaram no GitHub. 

`Ainda não feche o console` 

#### Passo 2: Digite `git -m "Comentário relacionado a versão atual"`, aperte enter e aguarde. 

Esse comentário deve ser coerente com a nova versão, indicando exatamente a nova alteração. 

Digite: `git status` e aparte enter. Irá aparecer uma frase semelhante:

`On branch main` 

`Your branch is ahead of 'origin/main' by 1 commit.`

​	`(use "git push" to publish your local commits)`

`nothing to commit, working tree clean` 

Digite: `git push origin main` no console e aperte enter.

***O push envia todos os commits locais para a nuvem (GitHub)***

Pronto! Agora os seus arquivos atualizados já estrarão lá no GitHub. 😁

