algumas atualizações na 3ª section 
main .pro-section .text-wrapper {
    position: absolute;
    top: 10%; /* Coloca o topo do texto no centro da imagem */
    left: 50%; /* Coloca a esquerda do texto no centro da imagem */
    transform: translate(-50%, -50%); /* Move o texto para o centro da imagem */
    text-align: center; /* Centraliza o texto */
}

aprendizado com git segue a baixo :

git init
 inicia um novo projeto com git

git add <nome-arquivo>/.
 add os arquivos prontos p commitar

git commit -m "mensagem commit" ou manualment no vscode
 commit os arquivos no historico

git log
 mosta ultimos commit, log de alterações

git status
 como esta o estado das ramificações

git diff
mostra oq foi alterado, tbm oq tem de alteração na ramificação

git merge
mescla as ramficações 

git branch
 mostra a branch atual

git checkout <nome da branch>
 muda a branch

git branch -b <nome da branch>
 cria uma nova brancha a partir da que estou

git remote add <nome> <url>
 adiciona um repositorio remoto para push e pull

git push <nome> <nome da branch>
,amda as alterações locais para o repositorio remoto p cada branch

git pull <nome> <nome da branch>
 pega as alterações do repositorio remoto

git fetch 
atualiza o novo historico local de acordo com o historico salvo la  no repositorio
sincronização do local com o remoto
