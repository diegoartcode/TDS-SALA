


# Comandos Git Principais

## 1. `git init`
Inicializa um repositório Git vazio ou recria um novo repositório em um diretório existente.

### Exemplo:
```bash
git init
```

### Variações:
- Não há variações específicas para esse comando.

---

## 2. `git clone`
Clona um repositório remoto para um diretório local.

### Exemplo:
```bash
git clone https://github.com/usuario/repositorio.git
```

### Variações:
- `git clone <URL> <diretório>`: Clona em um diretório específico.
  
---

## 3. `git add`
Adiciona mudanças ao índice (staging area), preparando-os para o próximo commit.

### Exemplo:
```bash
git add arquivo.txt
```

### Variações:
- `git add .`: Adiciona todas as mudanças no diretório atual e subdiretórios.
- `git add -A`: Adiciona todos os arquivos, incluindo remoções.

---

## 4. `git commit -m`
Cria um commit com as mudanças adicionadas, acompanhado de uma mensagem.

### Exemplo:
```bash
git commit -m "Mensagem do commit"
```

### Variações:
- `git commit -a -m "Mensagem"`: Comita automaticamente todos os arquivos rastreados que foram modificados.
  
---

## 5. `git status`
Exibe o estado atual do repositório, incluindo arquivos modificados, staged, ou não rastreados.

### Exemplo:
```bash
git status
```

### Variações:
- Não há variações específicas para esse comando.

---

## 6. `git branch`
Gerencia as branches (ramificações) do repositório.

### Exemplo:
```bash
git branch
```

### Variações:
- `git branch <nome-da-branch>`: Cria uma nova branch.
- `git branch -d <nome-da-branch>`: Deleta uma branch local.
  
---

## 7. `git checkout`
Muda para uma branch específica ou restaura arquivos do repositório.

### Exemplo:
```bash
git checkout nome-da-branch
```

### Variações:
- `git checkout -b <nome-da-branch>`: Cria e muda para uma nova branch.
- `git checkout -- <arquivo>`: Desfaz alterações em um arquivo específico.

---

## 8. `git merge`
Combina as mudanças de uma branch com a branch atual.

### Exemplo:
```bash
git merge nome-da-branch
```

### Variações:
- `git merge --no-ff nome-da-branch`: Força a criação de um commit de merge, mesmo quando um fast-forward seria possível.

---

## 9. `git pull`
Obtém e aplica as mudanças do repositório remoto para o repositório local.

### Exemplo:
```bash
git pull origin master
```

### Variações:
- `git pull --rebase`: Faz um rebase das mudanças antes de aplicar o pull.

---

## 10. `git push`
Envia os commits locais para o repositório remoto.

### Exemplo:
```bash
git push origin master
```

### Variações:
- `git push -u origin master`: Define o repositório remoto como padrão para futuras referências.

---

## 11. `git fetch`
Baixa mudanças do repositório remoto, mas não as aplica no repositório local.

### Exemplo:
```bash
git fetch origin
```

### Variações:
- Não há variações específicas para esse comando.

---

## 12. `git log`
Exibe o histórico de commits do repositório.

### Exemplo:
```bash
git log
```

### Variações:
- `git log --oneline`: Exibe o histórico de commits em uma linha por commit.
- `git log --graph`: Exibe o gráfico do histórico de commits.

---

## 13. `git diff`
Exibe as diferenças entre arquivos ou commits.

### Exemplo:
```bash
git diff
```

### Variações:
- `git diff --staged`: Exibe as diferenças entre os arquivos staged e o último commit.
- `git diff <commit1> <commit2>`: Compara dois commits específicos.

---

## 14. `git reset`
Desfaz commits ou mudanças no índice.

### Exemplo:
```bash
git reset HEAD~1
```

### Variações:
- `git reset --hard`: Reseta o repositório para o estado de um commit anterior, descartando mudanças locais.
- `git reset <arquivo>`: Remove um arquivo do índice, mas mantém as mudanças no diretório.

---

## 15. `git remote`
Gerencia repositórios remotos.

### Exemplo:
```bash
git remote -v
```

### Variações:
- `git remote add <nome> <URL>`: Adiciona um repositório remoto.
- `git remote remove <nome>`: Remove um repositório remoto.

---

## 16. `git rm`
Remove arquivos do repositório e do sistema de arquivos.

### Exemplo:
```bash
git rm arquivo.txt
```

### Variações:
- `git rm --cached <arquivo>`: Remove um arquivo do índice, mas mantém o arquivo localmente.
- `git rm -r <diretório>`: Remove diretórios e seu conteúdo.
`