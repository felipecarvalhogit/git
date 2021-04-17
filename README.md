    #git 
    <img src="https://img.shields.io/static/v1?label=Git&message=ReadMe&color=orange&style=style=for-the-badge&logo=git"/>

:pushpin: O GIT é um controlador de versão de código.


## INSTALAÇÃO

http://git-scm.com/
> Download; <br>
> siga os passos de instalação conforme seu sistema operacional; <br>
> Utilize o prompt de comandos "GIT BASH" que vem junto na instalação; <br>
> ou se preferir pode usar o terminal nativo do seu sistema;

## COMANDOS BÁSICOS

> Status do Projeto: Em desenvolvimento :warning: <br>
Comandos básicos que ajudam aos iniciantes e aos esquecidos :)

1) versão instalada com `git --version`

2) Assinatura personalizada - Cofiguração Global <br>
`git config --global user.name "Nome de usuario"` <br>
`git config --global user.email "seuemail@dominio.com"`

3) Criando uma pasta para o novo repositório com `mkdir nomedoprojeto`

4) Entrando na pasta criada e dando início ao repositório <br>
`cd nomedoprojeto` <br>
`git init`

5) criando um arquivo com `touch arquivo.txt`

6) abre o arquivo direto do prompt com `vim arquivo.txt`

7) Ao terminar de escrever no arquivo, <br>
pressione `ESC` para sair do modo de "INSERÇÃO" <br>
Salve com `:w` <br>
ou se quiser salvar e sair para o modo de comando digite `:wq`

8) Indica ao GIT que o arquivo deve ser monitorado <br>
`git add arquivo.txt`

9) Exibe o status do que foi feito dentro do GIT com `git status`

10) Marcando um ponto na história de seu projeto *COMMIT* 
```
git commit -m "Sua mensagem"
```
> O 'commit' marca a versão e o que for feito daqui em diante, será uma nova versão;

11) Caso altere algum dos arquivos, posso ver a diferença entre as versões <br>
`git diff`

12) Adicionar todos os arquivos do repositório ao próximo *COMMIT* <br>
`git add .`
> Formas de adicionar... <br>
>> ...todos com uma mesma extensão: `git add *.html` <br>
>> ...por arquivos com a mesma extensão dentro de uma pasta: `git add pasta/*.tsx` <br>

13) Ignorar arquivos com a criação de um registro contendo os caminhos a serem ignorados:<br>
`touch .gitignore`
> Posso acrescentar / editar com `vim .gitignore` <br>
> Ex.: node_modules/
> Posso ver o conteúdo da pasta com: `cat .gitignore` <br>

14) mostra o histórico de *commits* e alterações dos participantes do projeto com `git log` <br>
**OBS.:** `git log -1` vejo o último *commit* com `git log -2` os 2 últimos e assim por diante; <br>

15) Deleta um arquivo com `rm nomedoarquivo.htm`

16) Mostra o conteúdo da pasta com `ls` 

17) Vendo o passado ou Recuperação de pontos passados: <br>

➡️ `git log` e copie o código do commit em questão <br>
➡️ `git checkout` + o código copiado do commit <br>
> git chekout serve para pular para algum ponto do projeto git.
> Para retornar para o ponto atual: <br>
➡️ `git checkout master`
<br>
<h2>Ramificação</h2>
<br>

18) Cria ramo novo + nome <br>
`git branch nome-do-ramo`
> Para exibir os ramos: `git branch`<br>

19) Navegando para o ramo: ` git checkout nome-do-ramo `

20) Juntando um ramo <br>
`git merge nom-do-ramo`

21) Deletar ramo <br>
`git branch -D nome-do-ramo`

22) Adicionando um ponto remoto do GitHub:
<br> *git* *remote* *add* + *nome-do-ponto* + *URL* <br>
```
git remote add origin https://github.com/felipecarvalhogit/git
```
> Lista as URLs: `git remote -v`

23) Enviando ramos com arquivos para o Github:<br>
*git* *push* + *nome-do-ponto* + *nome-do-ramo*
```
git push origin master
```

# GitHub :octocat:
[GitHub Docs](https://docs.github.com/pt/github/writing-on-github/basic-writing-and-formatting-syntax)

## Emojis para o README
Uma lista completa deles pode ser encontrada no repositório <br>
https://gist.github.com/rxaviers/7360908.js

**Alguns que destaco:** <br>

***Números de 1 a 10:***<br>
1️⃣ 2️⃣ 3️⃣ 4️⃣ 5️⃣ 6️⃣ 7️⃣ 8️⃣ 9️⃣ 🔟

***Sinais:***

:octocat: ✔️ 😄 🏁 🔴 ❗ ✖️ ❌ 💲 😑 💬 😞 ◀️ ▶️ 🔽 🔼 


## Como usar Badges
Fonte: https://dev.to/reginadiana/como-escrever-um-readme-md-sensacional-no-github-4509
> Badges servem para certificar ou indicar algo do teu projeto como status, licença, linguagens, testes, etc.<br>

Para utilizados podemos entrar o site shields.oi. Lá é possível encontrar vários modelos prontos, mas hoje eu vou mostrar com personalizar um.<br>

Podemos fazer isso a partir de uma URL como esta:<br>

```
https://img.shields.io/static/v1?label=<LABEL>&message=<MESSAGE>&color=<COLOR>&style=<STYLE>&logo=<LOGO>
```

***Onde cada parâmetro significa:*** <br><br>

**LABEL** texto do campo esquerdo <br>
**MESSAGE** texto do campo direto <br>
**COLOR** cor do campo direito (as opções podem ser encontradas no site) <br>
**STYLE** estilo do badge inteiro. Podemos ter: plastic, flat, for-the-badge, social ou flat-square. <br>
**LOGO** logo do campo esquerdo <br><br>

Como exemplo, vou escolher os seguintes parâmetros: <br><br>

**LABEL** como react <br>
**MESSAGE** como framework <br>
**COLOR** como blue <br>
**STYLE** como for-the-badge <br>
**LOGO** como REACT <br><br>

***Podemos colocar ele no README assim:***
```
<img src="https://img.shields.io/static/v1?label=react&message=framework&color=blue&style=for-the-badge&logo=REACT"/>
```
Exemplo: <img src="https://img.shields.io/static/v1?label=react&message=framework&color=blue&style=for-the-badge&logo=REACT"/><br>
  

    

