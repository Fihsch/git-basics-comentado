# 11. Sincronize mudanças

> Registre um repositório remoto e troque o histórico de versão.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)

---

## Comandos desta seção (4)

### 1. `git fetch [nome-remoto]`

```bash
git fetch [nome-remoto]
```

**O que faz:**

Baixa todo o histórico de um repositório remoto.

**Quando usar / observação:**

Utilizar sempre que precisamos consultar alterações feitas que ainda não estão na nossa máquina.
Idealmente utilizar sempre antes de começar a trabalahar para manter o repositório local sincronizado.

---

### 2. `git merge [nome-remoto]/[branch]`

```bash
git merge [nome-remoto]/[branch]
```

**O que faz:**

Faz o merge do branch remoto ao branch local atual.

**Quando usar / observação:**

Utilizar sempre que o branch remoto e o branch local não estão soncronizados para evitar conflitos.

---

### 3. `git push [alias] [branch]`

```bash
git push [alias] [branch]
```

**O que faz:**

Envia todos os commits do branch local para o branch remoto.

**Quando usar / observação:**

utilizar sempre após um commit para manter o branch remoto sincronizado.

---

### 4. `git pull`

```bash
git pull
```

**O que faz:**

Baixa o histórico e incorpora as mudanças.

**Quando usar / observação:**

Parecido com o comando do fetch porém esse além de carregar as novas mudanças do branch remoto no histórico, também puxa as mudanças para os arquivos locais.

---

## Checklist deste arquivo

- [ x ] 1. `git fetch [nome-remoto]`
- [ x ] 2. `git merge [nome-remoto]/[branch]`
- [ x ] 3. `git push [alias] [branch]`
- [ x ] 4. `git pull`

---

[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)
