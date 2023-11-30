configurar o git = {
	git config --global user.name 'NOME',
	git config --global user.email 'EMAIL',
	paraSaberQualConfig: {
 		git config --list
 }	
}

git init === iniciar um repositorio, ele vai agora ser controlado pelo git

git add . === ele vai adicionar os arquivos que foi modificado ou alterado, se quiser adiciona apenas um arquivo => git add 'nome do arquivo'

git commit -m "create index.html" === para ter um historico do que foi feito ou adicionado, colocando um etiqueta para ter controle

git log === vai ser listado qual foi os logs, quais commits foi feito e quem fez o commit

git log --oneline === vai ser uma forma mas resumida do log

git log -n 3 === vai me retorna os tres ultimos commit

git status === vai me mostrar qual etapa meus arquivos se em contra

HEAD == é um ponteiro que vai apontar para sempre a ultima aletração feita na linha do tempo do git

git diff === vai me mostrar o que foi alterado no código fonte

git restore index.html === para restaura alguma modificação feita errada, entao o git vai restaura no ponto que peguei o projeto, se quiser restoura todos arquivo => git restore .

git restore --staged .  || ou o nome do arquivo ===  é utilizado para desfazer as mudanças que foram adicionadas à área de preparação (staging area) do Git

git commit --amend -m "Nome do commit" === vai ser modificado a descrição do ultimo commit

git reset --soft HEAD~1 === vai resetar, vai desfazer o ultimo commit

git remote add oringin 'link do repositorio' === adicionando pra qual endereço meu projeto vai ser hospedado

git remote --v === consulta qual enderço remoto está hospedado

git push -u origin main === para enviar meus arquivos para o repositorio GitHub

git push === quando já existe um repositorio

.gitignore === esse arquivo vai ignorar tudo que eu quiser que o git ignore 

git rm -r --cached . === limpar o cache

.gitkeep === vai manter uma pasta quando é iniciada e ela estiver vazia

git pull === vai trazer atualização de novas e códigos do meu repositorio