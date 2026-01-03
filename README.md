Primeiros testes de criação de branchs paralelas e merging, e integrando o VS Code com o Git e o GitHub.



ciclo:

git add . (prepara todos os arquivos alterados pra serem comittados)
ou
git add nomedoarquivo (prepara um arquivo específico pra ser commitado)

git commit -m "resumo das alterações" (commit)
ou
git commit -a -m "outras alterações" (dá commit em todos os arquivos alterados)

git push (salva todos os commits no repositório remoto)


OBS: sempre mande o código-fonte, nunca o arquivo executável(.exe, .o, .out)





Para restaurar um arquivo modificado para o último commit: git restore nomedoarquivo
Para puxar alterações: git pull origin branch-em-que-vc-quer-salvar-as-modificações




"git branch" mostra a branch atual
"git fetch" puxa absolutamente todas as alterações da origin, incluindo novas branchs criadas lá
"git log" para ver todo o histórico de commits de um arquivo(do mais recente pro mais antigo)
"git diff" mostra no terminal as alterações não commitadas em relação ao último commit
