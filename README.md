# Learn Git Rethink

## **ESTUDOS SOBRE GIT HUB:**

**O que é um COMMIT:**

O git commit pode ser considerado em alto níveis um repositório util de gerencialmento e cronograma, onde cada commit representa nivel cronológico do trabalho representado, niveis esses que podem ser acessados e editados constantemente  apartir de *Branchs*. 

**O que é um Branch:**

O Branch é uma ramificação  em um algum nível do cronograma, que pode ser editado sem que se altere a main do repositório, e pode-se fundir o branch com o main apartir de um *Merge*.

**O que é um Merge:**

Em portugues, mesclagem, é simplimente uma unificação na linha cronologica que esteja bifurcada por uma Branch. 

**Repositório:**

Para criar um repositório basta ir em seu git de preferencia, e seguir em "meus repositórios", depois entrar em "new" e preencher os passos que estão descrito de um forma bem didática.

## **Principais comandos:**

```bash
git clone "nome arquivo":
```
O primeiro comando é de suma importancia pois é onde se cria um clone que possa modificar sem alterar diretamente no repositório.

```bash
git add "nome do arquivo":
```
Realiza a inclusão ou modificação do arquivo descrito no diretório local e o prepara para o `git commit`.

```bash
git commit -m "commit message":
```
 Esse codigo permite criar um commit imediato, e com um atalho para a mensagem de commit que será dada entre os as áspas ("..."). Esse atalho é permitido e dado pelo codigo `-m` após o codigo git commit, que originalmente abriria um editor de texto para pedir essa mensagem.

```bash
 `git commit --amend`:
```
 O codigo modifica o ultimo commit realizado, vale lembrar que não é criado um novo commit e sim apenas modifica.

```bash
git push:
```
Após o `git commit` está liberado o push que é simplemente fazer o envio final para o repositório git.

```bash
git log:
```
Descreve todos os commits realizados em ordem decrescente, apenas visual não é possivel moficalos, mas é importande para ver o endereço do commit para ser utilizado no `git revert`

```bash
git revert:
```
Usa o endereço do commit para ir até ele, como se fosse um ctrl + z. A intenção é criar um commit novo que inverte as alterações especificadas. 

```bash
git checkout 'nome da branch/main/origin:
```
Esse é um comando importante pois possibilita navegar entre as branchs criadas e a main do repositório.

