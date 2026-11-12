entrar no powershell não precisa ser no administrador 


mkdir atividade-git 
cd atividade-git


git config --global user.name "Christian Moro"
git config --global user.email "christian.moro@escola.pr.gov.br"
(aqui coloque o seu nome e seu email)
git init
echo "Atividade por Christian Moro" > readme.txt
git add readme.txt
git commit -m "primeiro commit"

git add .
git commit -m "primeiro commit: modificando arquivo"
