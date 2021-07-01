Ou crie um novo repositório na linha de comando
echo "# digitalinnovation" >> README.md 
git init 
git add README.md 
git commit -m "first commit" 
git branch -M main 
git remote adicionar origem https://github.com/renatobertone/digitalinnovation.git
 git push - sua origem principal
… Ou envie um repositório existente a partir da linha de comando
git remote add origin https://github.com/renatobertone/digitalinnovation.git
 git branch -M main 
git push -u origin main





# Para subir arquivos para o git, use a sequência abaixo.

## git status
mostra o status dos arquivos.

## git add * 
modifica o estado de todos os arquivos para stage (arquivos Versionados, rastreados)

## git add .* 
modifica o estado de todos os arquivos Ocultos para stage

## git rm 
Vou entende melhor, para depois subir para o git.

## git commit
Cria um novo commit ( Explicar aqui!!!)

## git remote add origin "Url de origiem"
cria tipo um atalho para fazer os download's e upload's( quando enteder melhor, melhoro a explicação!!!) 

## git push - origin master
Empurra o arquivo para o github, de acordo com a Url passada no git remote add origin

## git pull origin master
Pucha o arquivo do github , de acordo com a Url passada no git remote add origin
