Navegação no Git Bash
pwd	- Mostra em qual pasta você está
ls - Lista os arquivos e pastas do local atual
ls -la - Lista arquivos, inclusive ocultos, com detalhes
cd nome-da-pasta - Entra em uma pasta
cd .. - Volta uma pasta
cd ~ - Vai para sua pasta de usuário
cd / - Vai para a raiz do Git Bash
clear - Limpa o terminal
history - Mostra os comandos usados anteriormente
==================================================================================

Criar, mover, copiar e excluir
mkdir pasta	Cria uma nova pasta
touch arquivo.txt	Cria um arquivo vazio
cp arquivo.txt copia.txt	Copia um arquivo
cp -r pasta1 pasta2	Copia uma pasta inteira
mv arquivo.txt pasta/	Move um arquivo para uma pasta
mv antigo.txt novo.txt	Renomeia um arquivo
rm arquivo.txt	Exclui um arquivo
rm -r pasta	Exclui uma pasta e seu conteúdo
rm -rf pasta	Força a exclusão de uma pasta e seu conteúdo ⚠️
==================================================================================

Git — configuração
git --version	Mostra a versão do Git instalada
git config --list	Mostra as configurações do Git
git config --global user.name "Seu Nome"	Define seu nome no Git
git config --global user.email "email@email.com"	Define seu e-mail no Git
git config user.name	Mostra o nome configurado
git config user.email	Mostra o e-mail configurado
==================================================================================

Criar/iniciar um projeto Git
git init	Transforma a pasta atual em um repositório Git
git status	Mostra o estado atual do projeto
git clone URL	Baixa/clona um repositório existente
git remote -v	Mostra os repositórios remotos conectados
==================================================================================

Adicionar arquivos
git add arquivo.txt	Adiciona um arquivo para o próximo commit
git add .	Adiciona as alterações da pasta atual
git add -A	Adiciona todas as alterações do projeto
git restore --staged arquivo.txt	Remove um arquivo da área de preparação
==================================================================================

Commits
git commit -m "mensagem"	Salva as alterações no histórico do Git
git log		Mostra o histórico de commits
git log --oneline	Mostra o histórico de forma resumida
git show ID	Mostra detalhes de um commit específico
git diff	Mostra alterações ainda não adicionadas
git diff --staged	Mostra alterações que estão prontas para commit
==================================================================================

GitHub / Repositório remoto
git remote -v	Mostra o endereço do GitHub/remoto
git remote add origin URL	Conecta o projeto local a um repositório remoto
git remote set-url origin URL	Altera o endereço do repositório remoto
git push	Envia seus commits para o repositório remoto
git push origin main	Envia a branch main para o remoto
git push -u origin main	Envia a main e configura a conexão padrão
git pull	Baixa e integra alterações do remoto
git fetch	Baixa informações do remoto sem aplicar as alterações
git clone URL	Copia um repositório remoto para seu computador
==================================================================================

Branches
git branch	Mostra suas branches locais
git branch -a	Mostra branches locais e remotas
git branch nome	Cria uma nova branch
git switch nome	Troca para outra branch
git switch -c nome	Cria uma branch e já entra nela
git checkout nome	Troca para uma branch — comando mais antigo
git checkout -b nome	Cria e entra em uma branch — forma antiga
git branch -d nome	Exclui uma branch
git branch -D nome	Força a exclusão de uma branch ⚠️
git push -u origin nome	Envia uma nova branch para o remoto
==================================================================================

