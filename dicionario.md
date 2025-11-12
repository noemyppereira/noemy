## rotina
git status
git add <nome do arquivo>
git commit -m "mensagem significativa"
git push

chegando o __status__ dos arquivos, add na staging area_, faz o _commit_ pra slavar na linha do tempo e faz o push para mandar para o Github


## dicionario de conceitos
untracked é um arquivo que a gente nunca viu antes
conceitos sobre histórico, que seria o comando commit
o que é uma staging area? combinar arquivos que sofreram motificações, o commit basicamente é para ter um relatório de tudo que vc esta fazendo
o comando add 
git log --graph --oneline --decorate --all: Este é um comando popular para visualizar o histórico em um formato de "linha do tempo" gráfico, mostrando os branches e merges de forma visual, o que ajuda a entender o fluxo do desenvolvimento.
git log: Este comando lista todos os commits do mais recente para o mais antigo, mostrando o hash SHA, autor, data e a mensagem do commit.
fiz o test para git
o arquivo .gitignore tudo que colocar lá dentro vai ignorar
o README é como um manual
quando colocamos .md é um arquivo organizado

git reset --hard HEAD~1 - para reverter um commit - pode perder todo o historico
git revert recupera o commit anterior, mais isso fica no histórico - é melhor se vc se arrepender pode voltar atras


git clone https://github.com/noemyppereira/noemy - vai clonar tudo do github de volta para o local, ai dei um cd noemy que é o nome do meu repositorio






## lista de comandos
Q para sair
git log --abbrev-commit
git diff para comparar os commit
git push comando para passar para o online 
git remote add oringing <ssh> para conectar com o site da githib
git init é para começar um novo projeto
git pull ferramentas de sincronização 