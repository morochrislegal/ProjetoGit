mkdir atividade-git && cd atividade-git
touch readme.txt
git config --global user.name "Christian Moro"
git config --global user.email "christian.moro@escola.pr.gov.br"
git init
echo "Atividade por Christian Moro" > readme.txt
git add readme.txt
git commit -m "primeiro commit"

git add .
git commit -m "primeiro commit: modificando arquivo"
