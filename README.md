# doc_gith


git init: ele inicia o arquivo ".git/" para controlar a pasta
git status: Ele é responsavel por validar os arquivos modificados dentro do projeto
git add: Ele é responsavel por colocar o arquivo modificado em uma area segura.
git commit -m "<texto_da_modificação>": Ele é responsavel por criar uma versão do projeto com as referencia do 

Configuração dos usuarios do Git
Erros:
git config --global user.name "<seu_nome>"
git config --global user.email "<seu_email>"


git checkout -b develop: git de desenvolvimento

git checkout -b <login>: cria uma nova branch ou ramo 

git checkout <nome da branch>: Muda de branch/ramo

git merge <nome da branch>: junta para ver os conflitos entre as branch

gitk: mostra as alterações

Erros:

remote: error: GH007: Your push would publish a private email address.
remote: You can make your email public or disable this protection by visiting:
remote: http://github.com/settings/emails
To https://github.com/Carrha/doc_gith.git
 ! [remote rejected] main -> main (push declined due to email privacy restrictions)

resolução
Go to Setting your commit email address.
Follow the Setting your email address for every repository on your computer.
Open your GitHub account, and go to Settings → Emails.
Select the Keep my email address private check box.
Unselect the Block command line pushes that expose my email check box.