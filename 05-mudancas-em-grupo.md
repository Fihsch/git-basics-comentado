# 05. Mudanças em grupo

> Nomeie uma série de commits e combine os esforços completos.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).

[⬅ Faça mudanças](04-faca-mudancas.md) · [Índice](../README.md) · [Refatore nomes de arquivos ➡](06-refatore-nomes-de-arquivos.md)

---

## Comandos desta seção (5)

### 1. `git branch`

```bash
git branch
```

**O que faz:**

Lista todas as branches locais.

**Quando usar / observação:**

Mostra apenas as branches locais, não vai listar as remotas.

---

### 2. `git branch [nome-do-branch]`

```bash
git branch [nome-do-branch]
```

**O que faz:**

Cria uma nova branch com o nome informado.

**Quando usar / observação:**

Sempre utilizar nomes padronizados e claros ao criar a branch.

---

### 3. `git switch -c [nome-do-branch]`

```bash
git switch -c [nome-do-branch]
```

**O que faz:**

Troca para a branch informada

**Quando usar / observação:**

Utilizar sempre que precisar ir para outro branch para fazer alterações.

---

### 4. `git merge [nome-do-branch]`

```bash
git merge [nome-do-branch]
```

**O que faz:**

Faz um merge da branch informada na branch atual.

**Quando usar / observação:**

Sempre prestar atenção antes de usar o comando para ver em qual branch estamos.

---

### 5. `git branch -d [nome-do-branch]`

```bash
git branch -d [nome-do-branch]
```

**O que faz:**

Deleta a branch informada.

**Quando usar / observação:**

com o `d` minúsculo é uma remoção segura, com o `D` maiúsculo é uma remoção `forçada`.

---

## Checklist deste arquivo

- [ x ] 1. `git branch`
- [ x ] 2. `git branch [nome-do-branch]`
- [ x ] 3. `git switch -c [nome-do-branch]`
- [ x ] 4. `git merge [nome-do-branch]`
- [ x ] 5. `git branch -d [nome-do-branch]`

---

[⬅ Faça mudanças](04-faca-mudancas.md) · [Índice](../README.md) · [Refatore nomes de arquivos ➡](06-refatore-nomes-de-arquivos.md)
