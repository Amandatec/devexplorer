<!-- ![banner](https://github.githubassets.com/images/modules/memexes/projects-beta-banner-dark.png) -->
<img src="https://github.githubassets.com/images/modules/memexes/projects-beta-banner-dark.png" style="position: absolute;">

# 🚀DevExplorer

## O que é o DevExplorer?
A Turma 1.0 do Explorer teve a iniciativa de compartilhar suas informações através de um [Google Docs](https://docs.google.com/spreadsheets/d/1SsZ9JL6ADQQ2vDfT-bXqo21PH87N_HjzKIoEeaZL-Rc/edit#gid=0) visando melhorar seu networwing.
Inspirado nessa iniciativa surgiu o [DevExplorer](#) que é um projeto onde o aluno do Explorer podem compartilhar suas informações e ao mesmo tempo aprender como contribuir com um projeto que está no [Github](https://github.com).

## Como posso contribuir?
### 1. Crie uma cópia desse repositório em sua conta do github. Esse processo chamamos de `fork`. 
Faça um `fork` do repositório clicando no botão no canto superio direito da página.
<img src="https://docs.github.com/assets/cb-23088/images/help/repository/fork_button.png" width="500px">

Ou através do link [https://github.com/valdemirfilho/devexplorer/fork](https://github.com/valdemirfilho/devexplorer/fork)

> Caso tenha dificuldade em fazer o `fork` do Projeto veja o passo a passo na [documentação do github](https://docs.github.com/pt/get-started/quickstart/fork-a-repo).

### 2. Clone o repositório.
Com o fork do repositório realizado, você está pronto para cloná-lo para que você tenha uma cópia de trabalho local do código.
Abra um terminal e clone o repositório que está em sua conta para a sua máquina local.
Vamos utilizar o comando `git clone` juntamente com a URL que aponta para o seu fork do repositório.
Esta URL será semelhante à URL abaixo.
```
git clone https://github.com/[seu-nome-de-usuário]/devexplorer.git
```

Você pode copiar a URL usando o botão verde `[Code]` da página do seu repositório que você acabou de fazer `fork`.
![clone-button](https://user-images.githubusercontent.com/6961638/193431077-6e1c8beb-39c3-4bf2-99bd-626aa1bb52f3.png)

### 3. Entre no diretório do projeto.
Digite no terminal o código abaixo.
 ```
 cd devexplorer
 ````
 
### 4. Crie uma Nova Branch.
Crie uma branch com o nome do seu usuário do github.<br>
Você pode verificar o nome do seu usuário na URL do ser perfil do github: `https://github.com/[seu-nome-de-usuário]`
Agora, vamos criar nossa nova branch com o comando `git branch`
```
git branch seu-nome-de-usuário
```
Agora que nossa nova branch está criada, podemos mudar para nos certificar de que estamos trabalhando nessa branch usando o comando `git checkout`
```
git checkout seu-nome-de-usuário
```

> Sempre que você trabalha em um projeto colaborativo, você e outros programadores que contribuem para o repositório terão ideias diferentes para novos recursos ou correções de uma só vez. Alguns desses novos recursos não levarão tempo significativo para serem implementados, mas alguns deles estarão em andamento. Por isso, é importante ramificar o repositório para que você possa gerenciar o fluxo de trabalho, isolar seu código e controlar quais recursos serão retornados à branch principal do repositório do projeto.<br><br>
> Alternativamente, você pode combinar os dois comandos acima, criando e mudando para a nova branch, com o seguinte comando: <br> `git checkout -b seu-nome-de-usuário`

### 5. Faça Alterações Localmente
Neste ponto você pode modificar arquivos existentes ou adicionar novos arquivos ao projeto em sua própria branch.
Abra o diretório do projeto no seu editor de código preferido. Ex: vscode.
Você pode digitar no terminal
```
code .
```
Vá até o diretório `users.example`. Copie esse arquivo para dentro do diretório `users`. Agora renomeie o arquivo `users.js.example` para `seu-nome-de-usuário.js`.
Por exemplo. Meu nome de usuário do github é `valdemirfilho` logo o meu arquivo deve ser renomeado para `valdemirfilho.js`.

Após renomear, abra o arquivo e preencha com as suas informações.  Preencha inicialmente suas informações para networking. As informações sobre os desafios são opcionais e podem ser preenchidas a medida que você for finalizando os desafios.

Depois de modificar o arquivo vamos prepará-lo para fazer o `commit`. Vamos adicionar todas as alterações que fizemos
```
git add -A
```
Em seguida, queremos registrar as alterações que fizemos no repositório com o comando `git commit`.
```
git commit -m "Adicionei as informações de [seu-nome-de-usuário]"
```
Nesse ponto você pode usar o comando `git push` para enviar as alterações locais para o repositório do github
```
git push -u origin [branch-atual]
```
> Lembre-se que  neste ponto a branch atual que você está trabalhando deve ser o seu nome de usuário do github.


## Dúvidas?
Procurar **Valdemir Filho** no Discord do Explorer.

#### Eu e a comunidade agradecemos a sua ajuda 💜

