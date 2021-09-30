### Desfazendo modificações
git restore [nome_arquivo]

### Trazendo de volta do staged
git restore --staged [arquivo]
git restore --staged . -> tudo 

### Corrigindo o último commit
git commit --amend -m "delete arquivo"

### Recuperando arquvios
git checkou [RASH] do commit --[arquivo]
escolhe o que quer -> git restore -staged[arquivo]

### Renomeando arquivos não rastreados
git clean -n ou -f (F) -> força a deleção

### Revertendo um commit
git revert HEAD~5 -> ele vai pega o último commit -1, -2. Quantos tiver para baixo 

-> git log --online
-> git revert [RASH]
