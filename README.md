# 📘 Guia de Comandos Git e Terminal

---

## 🖥️ Comandos Básicos de Terminal (Linux / Git Bash)

### 📂 Navegação e arquivos

ls
→ listar arquivos da pasta atual

ls -a
→ listar arquivos (incluindo ocultos)

cd OneDrive/Desktop
→ entrar na área de trabalho

cd ..
→ voltar uma pasta

pwd
→ mostrar o caminho absoluto atual

Exemplo:
$ pwd
/c/Users/Allan/OneDrive/Desktop

---

### 📁 Manipulação de arquivos e pastas

mkdir <nome_pasta>
→ criar uma nova pasta

cat <arquivo>
→ mostrar o conteúdo do arquivo

rm -rf <arquivo_ou_pasta>
→ remover arquivo ou pasta

---

## 🔧 Comandos Git

git init .
→ iniciar repositório na pasta atual

git status
→ mostrar estado dos arquivos

git add <arquivo>
→ adicionar arquivo para commit

git add .
→ adicionar tudo da pasta atual

git add *
→ adicionar todos os arquivos

git commit -m "mensagem"
→ criar um commit

git log
→ mostrar histórico de commits

git diff <arquivo>
→ mostrar alterações feitas

git reset
→ remover arquivos do stage

---

## 🌿 Branches

git checkout -b <branch>
→ criar e acessar uma nova branch

git branch
→ listar branches

git checkout <branch>
→ trocar de branch

git merge <branch>
→ unir alterações de outra branch

git branch -D <branch>
→ deletar branch

---

## 🚀 Fluxo de Trabalho Inicial (Local)

1. criar diretório do projeto
   → preparar ambiente do projeto

2. git init .
   → iniciar controle de versão

3. criar ou editar arquivos
   → desenvolver código

4. git status
   → verificar alterações

5. git add <arquivo>
   → preparar arquivos para commit

6. git status
   → confirmar arquivos adicionados

7. git commit -m "mensagem"
   → salvar alterações no histórico

8. git status
   → verificar estado final

---

## 🔁 Fluxo Git Local com Branch

1. git checkout -b <nova_branch>
   → criar nova branch

2. criar ou editar arquivos
   → realizar alterações

3. git status
   → verificar alterações

4. git add <arquivos>
   → adicionar arquivos

5. git status
   → confirmar stage

6. git commit -m "mensagem"
   → salvar alterações

7. git checkout main
   → voltar para branch principal

8. git merge <nova_branch>
   → unir alterações na main

---

## 🌐 Git + GitHub (Projeto Próprio / Empresa)

1. git clone <repo_url>
   → copiar repositório remoto

2. git checkout -b <nova_branch>
   → criar nova branch

3. criar ou editar arquivos
   → desenvolver alterações

4. git status
   → verificar mudanças

5. git add <arquivos>
   → adicionar arquivos

6. git status
   → confirmar stage

7. git commit -m "mensagem"
   → salvar alterações

8. git push origin <nova_branch>
   → enviar branch para o GitHub

9. abrir Pull Request no GitHub (para main)
   → solicitar merge

10. git push origin --delete <nova_branch>
    → deletar branch remota

11. git checkout main
    → voltar para main

12. git branch -D <nova_branch>
    → deletar branch local

---

## 🌍 Git + GitHub (Open Source)

1. fazer fork do projeto no GitHub
   → criar cópia do projeto

2. git clone <repo_fork_url>
   → clonar seu fork

3. git checkout -b <nova_branch>
   → criar nova branch

4. criar ou editar arquivos
   → realizar alterações

5. git status
   → verificar mudanças

6. git add <arquivos>
   → adicionar arquivos

7. git status
   → confirmar stage

8. git commit -m "mensagem"
   → salvar alterações

9. git push origin <nova_branch>
   → enviar alterações

10. abrir Pull Request (fork → projeto original)
    → contribuir com o projeto

11. git push origin --delete <nova_branch>
    → deletar branch remota

12. git checkout main
    → voltar para main

13. git branch -D <nova_branch>
    → deletar branch local

---

## ✅ Dicas rápidas

* Sempre rode `git status` antes de commitar
* Use nomes claros nas branches (`feature/login`, `fix/bug-x`)
* Escreva mensagens de commit descritivas
* Evite usar `rm -rf` sem ter certeza
* uma linha adicionada de teste

