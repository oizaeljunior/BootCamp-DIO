# DIO | Resumos Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub do curso Versionamento de Código com Git e GitHub da  
[Digital Innovation One](https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/599dd3dd-d189-474f-a55c-22f37b4472da?back=/track/coding-future-banco-pan-desenvolvimento-frontend-com-angular&tab=undefined&moduleId=undefined).

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc)
- [Documentação GitHub](https://docs.github.com/)

## 💻 Resumos das Aulas 

| Aulas | Resumos |
|-------|---------|
|Gravando Alterações no Repositório Local | [Resumos](https://github.com/oizaeljunior/BootCamp-DIO)|

## ⚙ Configurando o Git
```
git config --global user.name "Nome do usuario"
git config --global user.email email do usuario
git config --global init.defaultBranch main

AUTENTICAÇÃO VIA TOKEN

- Criar um token no site do GitHub
git clone URL do repositório
- Digite o nome do usuario
- Coloca o Token
git config --global credential.helper store
- Digite o nome do usuario
- Coloca o Token
```

## 🔠 Comandos
| Código | O que faz |
|--------|-----------|
| `mkdir nome da pasta` | cria uma pasta |
| `touch nome da pasta/nome do arquivo.md` | cria um arquivo |
| `cd nome do diretório/pasta`| muda o diretório |
| `git init` | inicia um repositório |         
| `git clone URL do repositório` | clona um repositório remoto pra um local |
| `git remote add origin URL do repositório` | conecta um repositório local com um remoto |                                                           
| `git add Nome do arquivo` | adiciona os arquivos modificados para área de preparação |                                                                     
| `git status` | status do repositório local |       
| `git commit -m"Nome do commit"` | adiciona um commit nos arquivos modificados |
| `git log` | histórico de modificações |          
| `rm -rf .git` | remove a pasta |      
| `git restore nome do arquivo` | restaura uma modificação feita |
| `git commit --amend -m"Nome do commit"` | modifica o nome do último commit criado |                                                        
| `git reset --soft codigo do commit` | exclui o último commit criado |
| `git reflog` | histórico de modificações mais aprofundadas |       
| `git reset nome da pasta/nome do arquivo.md` | remove o arquivo |
| `git push -u origin main` | envia o conteúdo local para o repositório remoto |
| `git pull origin main` | traz o conteúdo remoto para o repositório local |         
| `echo "#commit-1-branch-main" > Criar nome de um arquivo.txt` | cria um commit novo |                                     
| `git checkout -b Nome da Branch` | cria uma branch |
| `git checkout Nome da Branch` | muda de branch |
| `git branch -v` | lista o último commit de cada branch |   
| `git merge Nome da Branch` | mescla/junta a branch inserida com a branch principal/main |                                                                   
| `git branch` | lista as branch do repositório |    
| `git branch -d Nome da Branch` | exclui a branch |
| `git fetch origin main` | traz o conteúdo remoto sem mesclar/juntar com o local | 
| `git diff main origin/main` | visualiza o conteúdo trazido do repositório remoto |                                                                
| `git clone URL do repositório --branch Nome da Branch --single-branch` | clona somente a branch indicada |                           
| `git stash` | arquiva a modificação feita |      
| `git stash list` | lista as modificações arquivadas | 
| `git stash apply` | traz os arquivos pra branch e mantem a modificação |
| `git stash pop` | traz os arquivos e exclui as alterações mais recentes |  

## 🔍 Referências
- [Referências do site Git com comandos e explicações](https://git-scm.com/docs)
- [Inteligência Artificial Git](https://gitfluence.com/)
- [Sintaxe de Formatação de Texto](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)