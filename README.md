# GIT COMMANDS

### git config  -> serve para logar em uma nova maquina (git config -global user.name "seu nome" // -global user.email
### git init -> serve para inicializar o git no repositorio local 
### git clone <repository URL> -> cria uma copia exata do repositorio escolhido
### git add * -> vai adicionar todos os arquivos novos/alterados ao seu repositorio
### git commit -> envia o seu repositorio para o github lembrar sempre de por um comentario git commit -a "Esse commit foi sobre isso"
### git push -> serve para empurrar o repositorio para o github 
### git pull  -> serve para baixar o repositorio que foi alterado no github para você ajustar manualmente com o seu repositorio local $ git pull <URL>
### git log --oneline  -> para vê os logs dos commits
### git checkout numeroDoLogComit   -> ex: commit 040459cf second commit /// git checkout 040459cf   -> acessa o arquivo do commit passado "*restaura*"
### git reset <file> ou git reset  -> restaura para o ultimo commit
### git remote add origin <repository URL>  -> vincula ao repositorio github
## Como fazer o git checkout remote branch
<p>Faça o fetch de todas as branches remotas</p> 
<code>git fetch origin</code>
<p>Liste as branches disponíveis para o checkout</p> 
<code>git branch -a</code>
<p>O resultado desse comando é a lista de branches disponíveis para checkout. Para ver as branches remotas, você as verá prefixadas com remotes/origin.</p> 
<p> Agora altere para a branch remota </p>
<code> git checkout --track origin/my-branch-name </code>
<p>Faça o pull das alterações de uma branch remota
Observe que você não pode fazer alterações diretamente em uma branch remota. Assim, você precisa de uma cópia dessa branch. Digamos que você queira copiar a branch remota fix-failing-tests. Você faria isso dessa forma:</p> 
<code>git checkout -b fix-failing-tests origin/fix-failing-tests</code>
O que isso faz:
<ul>
<li>cria uma nova branch local chamada fix-failing-tests</li>
<li>faz o checkout daquela branch</li>
<li>faz o pull das alterações de origin/fix-failing-tests para aquela branch</li>
</ul>




## ARQUIVO CONFIGURANDO CHAVE SSH
<a href=https://docs.google.com/document/d/e/2PACX-1vSIUrYS_BFVGejzUAu7IFVKa7uqsqzjL_QluDWmTLMVVKP5VfGXceTtXMXGxefqs9LDvEDNWcwmjZC6/pub>COMANDOS & SSH GENERATION</a>
