"# AGENTE01" 

git init
echo "# AGENTE01" >> README.md
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:cpm1163/AGENTE01.git
git push -u origin main

Ver todos os arquivos em cache
# huggingface-cli scan-cache

Para deletar modelos em cache:
# huggingface-cli delete-cache