## Comandos Git

git config

A primeira coisa que você deve fazer quando instalar o Git é definir o seu nome de usuário e endereço de e-mail. Isso é importante porque todos os commits no Git utilizam essas informações, e está imutavelmente anexado nos commits que você realiza:

```
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com
```


git init

Caso você esteja iniciando o monitoramento de um projeto existente com Git, você precisa ir para o diretório do projeto e digitar

```
git init
```


git add

Para passar a monitorar um novo arquivo, use o comando **git add**.

```
git add
```



git commit

Armazena o conteúdo atual do índice em um novo commit, juntamente com uma mensagem de registro do usuário que descreve as mudanças.
Se usa o commit depois de já ter feito o **git add**, para fazer o commit:

```
git commit -m "Mensagem"
```


git status
A principal ferramenta utilizada para determinar quais arquivos estão em quais estados é o comando:

```
git status
```


git pull 

Incorpora as alterações de um repositório remoto no branch atual. Em seu modo padrão, **git pull** é uma abreviação para **git fetch** seguido de git merge **FETCH_HEAD**. Por exemplo, se eu estiver em uma branch chamada **master** e quiser atualizar caso haja atualizações remotamente:

```
git pull origin master
```


git push

**O git push** é o comando em que você transfere commits a partir do seu repositório local para um repositório remoto.

```
git push origin master
```

git remote

O git remote é para adicionar o endereço do repositório remoto. 

```
git remote add origin "https do repositoria de origem Github"
```

 