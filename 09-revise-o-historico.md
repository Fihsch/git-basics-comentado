# 09. Revise o histórico

> Navegue e inspecione a evolução dos arquivos do projeto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)

---

## Comandos desta seção (4)

### 1. `git log`

```bash
git log
```

**O que faz:**

Lista todo o histórico de alterações dentro do branch atual.

**Quando usar / observação:**

Utilizar sempre que precisamos consultar o histórico de alterações.

---

### 2. `git log --follow [arquivo]`

```bash
git log --follow [arquivo]
```

**O que faz:**

Lista todo o histórico de alterações dentro do branch atual de algum arquivo específico.

**Quando usar / observação:**

Utilizar sempre que precisamos consultar o histórico de alterações de um arquivo em específico.


---

### 3. `git diff [primeiro-branch]...[segundo-branch]`

```bash
git diff [primeiro-branch]...[segundo-branch]
```

**O que faz:**

Mostra a diferença de conteúdo dos arquivos entre dois branches.

**Quando usar / observação:**

Utilizar sempre quando for necessário comparar dois branches, como por exemplo antes de um merge.

---

### 4. `git show [commit]`

```bash
git show [commit]
```

**O que faz:**

Mostra as mudanças de um commit específico.

**Quando usar / observação:**

Utilizar sempre que precisamos consultar um commit, como por exempçlo no caso de erro, encontrar o que foi alterado para causar o erro.

---

## Checklist deste arquivo

- [ x ] 1. `git log`
- [ x ] 2. `git log --follow [arquivo]`
- [ x ] 3. `git diff [primeiro-branch]...[segundo-branch]`
- [ x ] 4. `git show [commit]`

---

[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)
